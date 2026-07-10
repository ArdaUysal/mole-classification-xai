# mole-classification-xai
TÜBİTAK 2209-A kapsamında geliştirilen, MobileNetV2 mimarisiyle desteklenmiş, Grad-CAM (XAI) tabanlı cilt lezyonu sınıflandırma araştırması.

# Skin Lesion Classification (Mole vs. No Mole) 🔬

Bu depo, TÜBİTAK 2209-A Üniversite Öğrencileri Araştırma Projeleri Destekleme Programı kapsamında yürütülen cilt lezyonu analizi ve sınıflandırma projesinin araştırma ve teknik geliştirme süreçlerini içermektedir. 

Temel amaç, bilgisayarlı görme teknikleri kullanarak deri üzerindeki lezyonların "ben (mole)" veya "ben olmayan (no mole)" şeklinde sınıflandırılması ve bu kararların tıbbi görüntüleme standartlarına uygun şekilde açıklanabilirliğinin (XAI) sağlanmasıdır.

## 🚀 Proje Özeti ve Teknolojiler

Projenin merkezinde yer alan `baseline_v2.ipynb` dosyası, derin öğrenme modellerinin eğitilmesi, test edilmesi ve sonuçların görselleştirilmesi adımlarını barındırır. 

* **Derin Öğrenme Mimarileri:** Sınıflandırma performansını optimize etmek amacıyla **MobileNetV2** modeli kullanılmıştır.
* **Açıklanabilir Yapay Zeka (XAI):** Modelin aldığı kararların kara kutu (black-box) olmaktan çıkarılıp yorumlanabilmesi için **Grad-CAM** entegrasyonu yapılmıştır. Bu sayede modelin görüntünün hangi bölgelerine odaklanarak sınıflandırma yaptığı görselleştirilmiştir.

## 📊 Proje Durumu
Bu proje, bir bitirme / araştırma çalışması olarak yürütülmüş olup; veri işleme, model kurulumu ve XAI (Grad-CAM) süreçlerinin teknik altyapı analizlerini tamamlamıştır. Geliştirilen süreçler ticari bir son üründen ziyade, derin öğrenme algoritmalarının tıbbi görüntüler üzerindeki araştırma ve teknik fizibilite çıktılarını temsil etmektedir.

👉 **[Jupyter Notebook'u Tarayıcıda Görüntülemek İçin Tıklayın (nbviewer)](https://nbviewer.org/github/ArdaUysal/mole-classification-xai/blob/main/baseline_v2.ipynb)**
