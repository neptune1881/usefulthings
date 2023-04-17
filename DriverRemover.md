Komut İstemi'ni yönetici olarak çalıştırın . Ara'ya cmd yazın, sağ tıklayın ve Yönetici olarak çalıştır'ı seçin. İstendiğinde Evet'e basın.

DISM kullanarak yüklenen sürücü listesini tablo biçiminde almak için aşağıdaki komutu girin .

Eşzamanlı olarak, Sütundaki yayıncının adını, Bellek Bütünlüğünü engelleyen sürücünün adının karşısına not edin.

dism /online /get-drivers /format:table

Aşağıdaki komutu kullanarak sürücü izlerini kaldırmak için PNPUtil aracı komutunu kullanın . Ayrıca, değiştirdiğinizden emin olunDISM komutundan.

pnputil /delete-driver <Publisher Name> /uninstall /force

Bilgisayarı yeniden başlatın.

Örneğin, yayıncı adından oem11.sys alırsanız, komut şu şekilde yürütülür.

Pnputil /delete-driver oem11.sys /uninstall /force
