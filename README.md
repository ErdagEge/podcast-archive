![Acik Bufe Diyalog Header](https://github.com/user-attachments/assets/4a3aef48-b4b9-4938-8196-bc84cf13358f)

# Açık Büfe Diyalog Podcast Arşivi

Bu web sitesi Açık Büfe Diyalog'un tüm bölümlerine, notlarına ve ekstra içeriklerine ev sahipliği yapmaktadır. İster yeni bir dinleyici olun, ister uzun zamandır aramızda olun, şu ana kadar yaptığımız her sohbete göz atabilir ve ekstra içeriklerin keyfini çıkarabilirsiniz.

[Siteye erişmek için buraya tıklayın](https://erdagege.github.io/podcast-archive/)

[Spotify'da dinlemek için buraya tıklayın](https://open.spotify.com/show/5IkatgeB5ZBbbAADZC9Tty?si=e9630574a6014c1b)

## Siteyi Yerelde Çalıştırma

Açık Büfe Diyalog arşivini yerel ortamda görüntülemek için herhangi bir statik dosya sunucusu kullanabilirsiniz. Python kuruluysa proje dizininde aşağıdaki komutu çalıştırmak yeterlidir:

```bash
python3 -m http.server
```

Bu komut sunucuyu varsayılan olarak `http://localhost:8000` adresinde başlatır. Tarayıcınızdan bu adrese giderek siteyi yerelde inceleyebilirsiniz.

## Bölüm Eklemek

Bu depo genel erişime açıktır ancak dış katkılara kapalıdır. Depoyu kendi
çatallayıp geliştirmek isterseniz, yeni bölümleri `episodes.json` dosyasına
aşağıdaki biçimde ekleyebilirsiniz:

```json
{
  "title": "Yeni Bölüm Başlığı",
  "description": "Bölümün kısa açıklaması",
  "spotifyId": "Spotify bölüm kimliği"
}
```

Eklediğiniz nesnenin dizide uygun yere geldiğinden ve virgülle ayrıldığından
emin olun. Orijinal depoya yeni bölüm eklemek için lütfen pull request
göndermeyin.

## Katkılar

Bu proje portföy amacıyla herkese açıktır, ancak kod veya içerik değişiklikleri
kabul edilmez. Yeni bölümler eklemek ya da mevcut dosyaları değiştirmek için
pull request göndermemenizi rica ederiz.

## Lisans

Bu depo MIT lisansı ile dağıtılmaktadır. Ayrıntılar için `LICENSE` dosyasına göz atabilirsiniz.
