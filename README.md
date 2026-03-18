# 🚀 PyTorch ile Derin Öğrenmeye Giriş - JetBrains Academy Mini Kursu

Bu depo, JetBrains Academy Plugin kullanılarak hazırlanmış, derin öğrenmeye yeni başlayanlar için interaktif bir **PyTorch** mini kursunu içermektedir. Kurs, öğrencilerin kendi IDE'leri içinde pratik yaparak öğrenmelerini hedefler.

## 📖 Kurs Hakkında

Bu mini kurs, Python geliştiricilerine PyTorch tensörlerinin temellerini interaktif bir şekilde öğretmek için tasarlanmıştır. Kurs boyunca teorik bilgileri okuyacak, öğrendiklerinizi quizlerle test edecek ve doğrudan IDE içinde kod yazarak pekiştireceksiniz.

**Hedef Kitle:** Temel Python bilgisine sahip, yapay zeka dünyasına adım atmak isteyen geliştiriciler.

## 🛠️ Kurs İçeriği (Ders Yapısı)

Kurs, 1 ana modül (Lesson) ve altındaki çeşitli görevlerden (Tasks) oluşmaktadır:

* **📚 Teori Görevleri:**
    * İlk Tensörümüzü Oluşturmak
    * Tensörler Üzerinde Matematiksel İşlemler
    * İşlemleri Hızlandırmak: CPU'dan GPU'ya Veri Taşıma
    * 
      <img width="1456" height="1382" alt="resim" src="https://github.com/user-attachments/assets/13d7092e-814e-46b5-8a85-48137d5f94ce" />

* **📝 Quiz Görevleri:**
    * Tensör Oluşturma Fonksiyonları (Çoktan Seçmeli)
    * Veri Tipi (dtype) Kontrolü (Tek Seçmeli)
    * Cihaz (Device) Yönetimi (Tek Seçmeli)
 
    <img width="1450" height="1406" alt="resim" src="https://github.com/user-attachments/assets/fcf150a8-1730-49a1-96eb-1104701df44e" />


* **💻 Kodlama Görevleri:**
    * `torch.zeros` ile Sıfırları Yakalamak
    * İki Tensörü Toplamak
    * GPU Kontrolü ve `.to("cuda")` Kullanımı
 
  <img width="1464" height="1000" alt="resim" src="https://github.com/user-attachments/assets/10d5b394-b39f-4b0e-b63d-8cf5408ba635" />


## ⚙️ Gereksinimler

Bu kursu kendi bilgisayarınızda çözebilmeniz için aşağıdakilere ihtiyacınız vardır:

* [PyCharm Educational Edition](https://www.jetbrains.com/pycharm-edu/) veya herhangi bir uyumlu JetBrains IDE'si.
* IDE'nizde kurulu **JetBrains Academy Plugin** (Eskiden EduTools).
* Bilgisayarınızda kurulu Python 3.8+ ortamı.

## 🚀 Nasıl Kullanılır?

1.  Bu depoyu bilgisayarınıza klonlayın:
    ```bash
    git clone git@github.com:MehmetAkifEmre/The-Fundamentals-of-PyTorch-Tensors.git
    ```
2.  PyCharm'ı açın ve karşılama ekranından **"Learn"** sekmesine geçin.
3.  **"Open Custom Course"** (Özel Kurs Aç) veya **"Open from Disk"** (Diskten Aç) seçeneğine tıklayın.
4.  Klonladığınız klasörü seçin.
5.  IDE kursu derleyecek ve görev pencereleri sağ tarafta açılacaktır. Kodlamaya başlayabilirsiniz!

## 💡 Geliştiriciler İçin (IDE Özelleştirmeleri)

Bu kurs projesinde, öğrencilerin temiz kod yazmasını teşvik etmek amacıyla belirli IDE denetimleri (inspections) zorunlu kılınmıştır:
* `PEP 8 coding style violation` (Uyarı seviyesinde)
* `PEP 8 naming convention violation` (Değişken isimlendirmeleri için)

---
*Bu kurs Mehmet Akif Emre tarafından JetBrains Academy Course Creator araçları kullanılarak tasarlanmıştır.*
