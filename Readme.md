![Repo1](https://raw.githubusercontent.com/OgnitorenKs/Toolbox/main/.github/Repo-SS/Title.png)

#### Prepared by: Hüseyin UZUNYAYLA / OgnitorenKs
- ► Discord: https://discord.gg/7hbzSGTYeZ
- ► Mail: ognitorenks@gmail.com
- ► Site: [https://ognitorenks.blospot.com](https://ognitorenks.blospot.com)
- Supported languages = English │ Turkish
- Multiboot Manager hakkında (Türkçe): 

All rights of the work belong to Hüseyin UZUNYAYLA. It is forbidden to develop, copy, change the content of the work. If you want to share the application on different platforms, you need to get permission from me.

# Multiboot Manager

![Tool0](https://raw.githubusercontent.com/OgnitorenKs/Multiboot_Manager/main/.github/Manager/0.png)

- Multiboot manager works on Windows 10/11 systems.

<details><B><summary> 1- Create VHD</B></summary>

- Bu bölüm VHD (Virtual Hard Disk) oluşturmanızı sağlar. 
- "Define the VHD Path:" bölümünde VHD'yi oluşturacağınız konumu ve adını yazmanız gerekiyor. Uzantısını yazmasanızda olur kendisi otomatik tamamlayacaktır. Yazarsanız da sorun olmaz.
- "Write disk size in GB" bu bölümde VHD'nin boyutunu isteyecektir. GB olarak istediğiniz boyutu yazın. Tavsiyem 30 GB altına düşmeyin.
- "VHD configuration type" bölümünde disk yapılandırma türünü soracaktır. UEFI desteği varsa "GPT", yoksa "MBR" seçmeniz gerekiyor.
- Daha sonrasında VHD'yi oluşturup ana menüye geri dönecektir.

![Tool1](https://raw.githubusercontent.com/OgnitorenKs/Multiboot_Manager/main/.github/Manager/1.png)

</details><details><B><summary> 2- Windows installation</B></summary>


- Bu bölümde elinizde bulunan ISO'yu sisteme takıp veya herhangi bir klasöre çıkarıp yolunu tanımlayarak hızlıca Windows kurulumu yapabilirsiniz. İmajın klasör yolunu veya doğrudan install.wim/esd dosyasının yolunu verebilirsiniz.

![Tool2.1](https://raw.githubusercontent.com/OgnitorenKs/Multiboot_Manager/main/.github/Manager/2.1.png)

- İmajı tanımladıktan sonra içerdiği sürümler hakkında detaylı bilgi veren bir menüye aktaracaktır. Bu bölümde imaj içerisinde yer alan sürümlerden hangisini kurmak istiyorsanız Index numarasını tuşlamanız gerekmektedir. 

![Tool2.2](https://raw.githubusercontent.com/OgnitorenKs/Multiboot_Manager/main/.github/Manager/2.2.png)

- Kurulumu yapılacak Windows'un index numarasını seçtikten sonra sizi VHD'yi seçmeniz için disk seçim menüsüne atayacaktır. VHD diski oluştururken VHD ismi ve random sayı tanımlıyorum. Aşağıdaki ekran görüntüsünde VHD'miz "J" harfine atanmış ve ismi "VHD-17438" tanımlanmış. Buradan VHD'mizi tespit ettikten sonra solunda yer alan rakamı tuşluyoruz. Harf tuşlamayın.

![Tool2.3](https://raw.githubusercontent.com/OgnitorenKs/Multiboot_Manager/main/.github/Manager/2.3.png)

- Seçim yaptıktan sonra Dism ile VHD'ye Windows kurulumunu yapmaya başlayacaktır. İşlem bitince sizi ana menüye atacaktır. Sistem kurulumunu tamamlamak için sistemi yeniden başlatmanız gerekmektedir. Burada kalan işlemleri Windows tamamlayıp sizi dil seçme, hesap oluşturma menülerine aktaracaktır.

![Tool2.4](https://raw.githubusercontent.com/OgnitorenKs/Multiboot_Manager/main/.github/Manager/2.4.png)

</details><details><B><summary> 3- Redefine VHD</B></summary>

- VHD dosyasını yedekleyip ana sisteminize temiz kurulum yaparsanız. Daha sonrasında VHD'yi bu bölümden tanımlayarak multiboot sisteminizi kullanmaya devam edebilirsiniz.
- Bu bölüme girdikten sonra VHD dosyasının yolunu tanımlamanız gerekmektedir. Tanımlama işleminden sonra VHD dosyasını görünür hale getirip varsayılan olarak açılacak sistem olarak ayarlar. Sistemi yeniden başlatırsanız VHD diskteki sistemden başlayacaktır.

![Tool3](https://raw.githubusercontent.com/OgnitorenKs/Multiboot_Manager/main/.github/Manager/3.png)

</details>