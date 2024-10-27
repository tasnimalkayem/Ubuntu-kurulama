# VirtualBox Üzerinde Ubuntu 24.04 Kurulumu

Bu repo, VirtualBox üzerinde Ubuntu 24.04 kurulumunu adım adım açıklayan bir rehber sunmaktadır. Her adım, görsellerle desteklenmiştir.

## İçindekiler

- [Gerekli Ön Hazırlıklar](#gerekli-ön-hazırlıklar)
- [Kurulum Adımları](#kurulum-adımları)
- [Sonuç](#sonuç)

## Gerekli Ön Hazırlıklar

1. **VirtualBox** programını indirip kurun. İndirme linki: [virtualbox.org](https://www.virtualbox.org/).
2. **Ubuntu 24.04 Desktop ISO** dosyasını indirin. İndirme linki: [ubuntu.com](https://ubuntu.com/download/desktop).

## Kurulum Adımları

### Adım 1: Yeni Sanal Makine Oluşturma
- **VirtualBox**’ı açın ve yeni bir sanal makine oluşturmak için **New** butonuna tıkladım.
- Makine adını "Ubuntu 24.04" olarak girdim, sistem türünü **Linux** ve sürümünü **Ubuntu (64-bit)** olarak seçtim.
- ![Yeni Sanal Makine Oluşturma](images/adim1.png)

### Adım 2: Bellek (RAM) Ayarlama
- Sanal makine için 4 GB RAM ayırdım.
- ![Bellek Ayarlama](images/adim2.png)

### Adım 3: Sanal Sabit Disk Oluşturma
- **Create a virtual hard disk now** seçeneğini seçtim, disk türünü **VDI** ve **Dynamically allocated** olarak ayarladım.
- Disk boyutunu 20 GB olarak belirledim.
- ![Sanal Sabit Disk Oluşturma](images/adim3.png)

### Adım 4: Ubuntu ISO Dosyasını Bağlama
- **Settings** bölümüne gidip **Storage** kısmından **Empty**’ye tıkladım ve **Ubuntu ISO** dosyasını yükledim.
- ![ISO Dosyasını Bağlama](images/adim4.png)

### Adım 5: Kuruluma Başlama
- Sanal makineyi başlatmak için **Start** butonuna tıkladım.
- Açılan pencerede **Install Ubuntu** seçeneğini seçtim.
- ![Kuruluma Başlama](images/adim5.png)

### Adım 6: Dil ve Klavye Düzeni Seçme
- Kurulum dilini Türkçe olarak seçtim ve uygun klavye düzenini belirledim.
- ![Dil ve Klavye Düzeni Seçme](images/adim6.png)

### Adım 7: Kurulum Türünü Belirleme
- **Normal Installation**’ı ve **Erase disk and install Ubuntu** seçeneğini seçtim, bu sadece sanal disk için geçerli.
- ![Kurulum Türünü Belirleme](images/adim7.png)

### Adım 8: Saat Dilimi Seçimi
- Saat dilimini bulunduğum yere göre ayarladım.
- ![Saat Dilimi Seçimi](images/adim8.png)

### Adım 9: Kullanıcı Hesabı Oluşturma
- Kullanıcı adı ve parola bilgilerini girerek bir kullanıcı hesabı oluşturdum.
- ![Kullanıcı Hesabı Oluşturma](images/adim9.png)

### Adım 10: Kurulumun Tamamlanmasını Bekleme
- Kurulumun bitmesini bekledim, işlem tamamlanınca **Restart Now** ile yeniden başlattım.
- ![Kurulumun Tamamlanmasını Bekleme](images/adim10.png)

### Adım 11: ISO Dosyasını Çıkarma
- Tekrar **Settings** > **Storage** bölümüne gidip ISO dosyasını kaldırdım.
- ![ISO Dosyasını Çıkarma](images/adim11.png)

### Adım 12: Ubuntu'yu Kullanma
- Yeniden başlattıktan sonra Ubuntu’ya giriş yaptım ve sistem sorunsuz çalışmaya başladı.
- ![Ubuntu'yu Kullanma](images/adim12.png)

## Sonuç
Bu adımlarla **Ubuntu 24.04**’ü başarıyla VirtualBox üzerinde kurmuş oldum ve sistemi kullanıma hazır hale getirdim.
