# Orochi-Network


Bu repo, Orochi-Network ağını sunucuda çalıştırma adımlarını içerir.

## **Sistem Gereksinimleri**
## **Sistem Gereksinimleri**

| Bileşenler  | Minimum      | **Önerilen**  |
|-------------|--------------|---------------|
| CPU         | 4            |               |
| RAM         | 8 GB         |               |
| Depolama    | --- GB       |               |

---

## Kurulum Adımları

### 1. Bağımlılıkları Yükle

```
sudo apt update && sudo apt upgrade -y
```


```
sudo apt install ubuntu-gnome-desktop -y
```

```
sudo apt install gnome-core -y
```

Kurulum sırasında ekran yöneticisi seçmen istenecek. Orada gdm3 seçin:

🔘 gdm3

Rebootluyoruz...

```
sudo reboot
```

```
sudo apt install xrdp -y
```

```
sudo systemctl enable xrdp
```

```
sudo systemctl start xrdp
```

Kullanıcı adı oluşturucaz. şifre girin ardından size bikaç bişey sorar enterlayın en sonunda y yapın.

```
sudo adduser kullanıcıisminiz
```

![Ekran görüntüsü 2025-04-19 023543](https://github.com/user-attachments/assets/b3e4c13f-4b51-4360-a710-ed1ec7804fc6)


# Burdan sonraki işlemlere pcmizden devam ediyoruz.

Başlata gelip uzak masaüstü yazın. Ardından Çalıştırın. 

Gelişmişe Gelin.


![Ekran görüntüsü 2025-04-19 015101](https://github.com/user-attachments/assets/730c60ea-88c7-4260-a44e-3620d1accae1)

Bağlan Ve Beni uyarmayı seçin.

![Ekran görüntüsü 2025-04-19 015228](https://github.com/user-attachments/assets/d0bf281b-e58b-4c2f-b46a-38a5227ba769)


Ardından Genele Gelip Bilgisayar yazan kısma sunucu İP'nizi yazın.
Kullanıcı adına oluşturduğunuz kullanıcı adını yazın.
Şifre soracak Şifrenizi Girip Bğlanın.

En Son yapacağımız işlem Sunucu Ekran ayarını Kapamak olacak.
APPS Kısmına Giriyoruz.

![Ekran görüntüsü 2025-04-19 020107](https://github.com/user-attachments/assets/56f221ac-79b3-4439-9a10-871f7246d5f8)

Ayarlara giriyoruz.

![Ekran görüntüsü 2025-04-19 020236](https://github.com/user-attachments/assets/ea8fdd17-c09e-4281-aa6e-514f489a83b6)

En Sol bölümden powere giriyoruz. Screen blank'ı Never yapıyoruz.

Ve Artık chromeye girip işlemlerinizi yapabilirsiniz.
