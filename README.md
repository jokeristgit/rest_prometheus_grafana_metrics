Uygulama için gerekli servisler ve containerlar:
1) Prometheus container, port : 9090
2) Python için kurulu olması gereken (pip install kütüphane_adi)
  a)Python için prometheus_exporter kütüphanesi
  b)Python Rest Servisleri için Flask kütüphanesi
3) Grafana image 
4) Request generator, pyhton rest requestleri oluşturur 
5) Dosyaları bir klasöre çıkarıp cmd'de o klasör içerisinde
   docker compose up -d 
   yazılmalı
6) performans sonuçlarını aşağıdaki url üzerinden görebilirsiniz.
  http://localhost:3000/d/ornek
7) Tüm servisleri kapatmak için ise
    docker compose down 

