# Windows 
Microsoft tarafından geliştirilen bir işletim sistemidir ve ilk versiyonu 1985 
yılında piyasaya sürülmüştür. Zaman içinde birçok sürüm geliştirmiştir: 

#### • Ev Sürümleri:
Windows 95, Windows XP, Windows 7, Windows 10, Windows 11 
gibi. 
#### • Kurumsal Sürümleri:
Windows NT, Windows Server sürümleri (2000, 2003, 
2008, 2012, 2016, 2019, 2022). 


## Temel Farklılıklar: 
### • Windows 10 ve Windows 11:
Kullanıcı arayüzünde ve güvenlik özelliklerinde yenilikler. Windows 11, daha modern bir arayüz, yeni güvenlik özellikleri,
performans iyileştirmeleri sunar. 

### • Windows Server:
Kurumsal ağ yönetimi, sanallaştırma ve yüksek güvenlik gerektiren senaryolar için optimize edilmiştir. 
Örneğin, Active Directory hizmeti sunar. 


## Dosya Sistemi Tipleri: 
### • NTFS (New Technology File System): 
Modern Windows sürümlerinin varsayılan dosya sistemi. Güçlü güvenlik özellikleri, büyük disk desteği ve dosya sıkıştırma 
gibi özellikler sunar. 

### • FAT32:
Daha eski bir dosya sistemi, küçük diskler için uygundur ama NTFS kadar güvenli değildir. 

### • exFAT:
USB sürücüler ve SD kartlar gibi taşınabilir depolama cihazları için tasarlanmıştır, FAT32'nin sınırlamalarını aşar. 
NTFS, dosya ve klsaör izinleri tutar bu yüzden FAT32 ve exFAT’e göre daha güvenlidir. 
Ayrıca FAT32 bireysel dosya boyutu 4 gb ile sınırlarken, NTFS ve exFAT bu sınırı aşar. 


## Temel Güvenlik Özellikleri 
### Windows Defender 
Windows Güvenliği ile korunma. Windows Defender Güvenlik Duvarı, ağ üzerinden 
bilgisayarınıza veya bilgisayarınızdan hangi ağ trafiğine izin verilip verilmediğini 
denetleyen, Windows'ta yerleşik olarak bulunan bir güvenlik duvarı yazılımıdır. 

### Windows Update 
Microsoft Windows işletim sistemleri için güvenlik güncelleştirmeleri sağlar. Microsoft 
Update Web sitesi, Microsoft Office gibi diğer Microsoft programlarındaki 
güncelleştirmelere ek olarak bu güncelleştirmeleri de sağlar. 

### Kullanıcı Hesabı Denetimi (UAC) 
Kullanıcı Hesabı Denetimi (UAC), Windows'ta yetkisiz değişiklikleri önlemek için 
tasarlanmıştır. Bir eylem yönetici düzeyinde izinler gerektirdiğinde UAC, değişikliği 
onaylamanızı veya reddetmenizi ister. Bu, Windows cihazınızı kötü amaçlı yazılımlardan 
ve yetkisiz değişikliklerden korumaya yardımcı olur. 

### Güvenlik Duvarı (Firewall) 
Firewall açık olduğu sürece bilgisayarınızı korur ve zararlı yazılımları ya da virüsleri 
engeller. Belirli aralıklarla güvenlik duvarınızı taradığınızda bir gün içerisinde bile 
Firewall'un pek çok saldırıyı önlediğini görebilirsiniz. 


## Kullanıcı ve Grup Yönetimi 
### Yerel Kullanıcı Profilleri (Local User Profiles) 
Windows tabanlı sistemlerde her kullanıcıya özel ayar ve dosyaların saklanmasını 
sağlayan bir mekanizmadır. 

### Yerel Grup (Local Group) 
Yerel grup, bir bilgisayarın yerelinde oluşturulan ve yönetilen kullanıcı gruplarıdır. Bu 
gruplar sadece o bilgisayar üzerinde geçerlidir ve o bilgisayarın kaynaklarına erişim 
izinlerini kontrol eder. 

### Etki Alanı Kullanıcısı (Domain User) 
Genellikle bir kurumsal ağ içerisinde, Active Directory (AD) gibi bir merkezi yönetim 
sistemiyle yönetilen kullanıcı hesaplarıdır. Bu kullanıcılar, domain controller (etki alanı 
denetleyicisi) tarafından tanımlanır ve yönetilir. 

### Active Directory 
Active Directory, Microsoft tarafından özellikle Windows Server ve Client işletim 
sistemlerini merkezi olarak yönetebilmek amacıyla tasarlanmış; içerisinde sunucu, 
client bilgisayar, kullanıcı ve yazıcı gibi bilgileri tutan bir dizin hizmetidir. Kısaca; Active 
Directory yönetimi merkezileştirir ve kolaylaştırır. 


## Kurumsal Kullanım ve Güvenlik 
Kurumsal Windows sürümleri, özellikle Windows Server, büyük ölçekli ağ yönetimi, veri 
koruma ve kullanıcı kimlik doğrulama süreçlerini kolaylaştırır. Örneğin, bir şirket, Active 
Directory kullanarak çalışanların erişimini ve izinlerini yönetebilir. 
Siber güvenlik açısından, NTFS'nin güvenlik ayarları, UAC ve güncel yamalar kritik 
öneme sahiptir. Özellikle veri kaybını veya yetkisiz erişimi önlemek için dosya sistemleri 
ve kullanıcı yönetimi dikkatle yapılandırılmalıdır. 
### Siber Güvenlikte Kritik Noktalar:
#### • Dosya Sistemi:
NTFS'in kullanılması, dosya seviyesinde şifreleme ve izinlerle veri 
güvenliğini artırır. 

#### • Kullanıcı Yönetimi:
Güçlü parola politikaları, iki faktörlü doğrulama (2FA) ve 
kullanıcı yetkilerinin sıkı kontrolü, siber saldırılara karşı savunmayı güçlendirir.

# Zayıf Parola
# Zayıf Parola Politikası Sonucu Sistem Hesabının Ele Geçirilmesi 
Bir şirket içi bilgisayar ağında, kullanıcılar zayıf parolalar kullanmaktadır (örneğin, 
"123456" veya "password"). Bu durum, saldırganların brute-force saldırılarıyla yönetici 
hesabını ele geçirmesine olanak tanımıştır. Saldırgan, sistemde yetkili bir kullanıcı olarak 
çeşitli kötü niyetli faaliyetlerde bulunabilir, önemli verilere erişebilir veya fidye yazılımı 
dağıtabilir. 
## Analiz ve Önlemler 
• Parola Uzunluğu ve Karmaşıklığı minimum 12 karakter uzunluğunda, büyük
küçük harf, sayı ve özel karakterler içeren parolalar zorunlu kılınmalı. 
• Parolaların belirli aralıklarla (örneğin her 90 günde bir) değiştirilmesi zorunlu 
tutulmalı. 
• Kullanıcıların son kullandıkları birkaç parolayı tekrar kullanmaları engellenmeli. 
• Çalışanlara, güçlü parolaların önemi, sosyal mühendislik saldırıları ve temel siber 
güvenlik önlemleri hakkında düzenli eğitimler verilmelidir. 
• Özellikle yönetici hesapları için 2FA uygulanarak, ek bir güvenlik katmanı 
eklenmelidir.