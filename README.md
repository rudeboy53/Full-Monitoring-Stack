# 🚀 Full Monitoring Stack (Grafana + Prometheus + Loki + Promtail + Node Exporter)

![Grafana Ekran Görüntüsü](https://raw.githubusercontent.com/rudeboy53/Full-Monitoring-Stack/refs/heads/main/screenshots/grafana-dashboard.png)

Docker Compose ile hazırlanmış güçlü, hafif ve genişletilebilir bir izleme altyapısı. Tüm sistem içgörüsünü (loglar, metrikler, paneller) tek yerden sunar. Geliştiriciler, sistem yöneticileri ve DevOps mühendisleri için birebir.

---

## ✨ Özellikler

- 📈 Gerçek zamanlı metrik takibi (Prometheus + Node Exporter)
- 📃 Merkezi log toplama (Loki + Promtail) [Henüz aktif değil]
- 📊 Özelleştirilebilir paneller (Grafana)
- 🐳 Tamamen Docker Compose ile container bazlı
- 💡 Yerel geliştirme, sunucular, Raspberry Pi gibi ortamlara uygun

---

## 🧱 Bileşenler

| Bileşen       | Açıklama                                  |
|---------------|--------------------------------------------|
| Grafana       | Şık görseller ve uyarı sistemleri          |
| Prometheus    | Metrik toplayıcı ve zaman serisi veritabanı|
| Node Exporter | Sistem kaynaklarını izleyen ajan           |
| Loki          | Grafana için optimize edilmiş log veritabanı|
| Promtail      | Log toplayıcı ve Loki’ye yönlendirici      |

---

## 🚀 Hızlı Başlangıç

```bash
git clone https://github.com/rudeboy53/Full-Monitoring-Stack.git
cd Full-Monitoring-Stack
docker compose up -d
```

Ardından tarayıcında şu adrese git: [http://localhost:3000](http://localhost:3000)

- Kullanıcı adı: `admin`
- Şifre: `admin`

> ⚠️ Üretim ortamında şifreni mutlaka değiştir.

---

## 🔧 Dosya Yapısı

```
Full-Monitoring-Stack/
├── docker-compose.yml
├── prometheus/
│   └── prometheus.yml
├── promtail/
│   └── promtail-config.yaml
├── loki/
│   └── loki-config.yaml
├── devlogs/
│   └── app.log ← test log dosyası
└── grafana/
    └── provisioning/
        ├── datasources/
        └── dashboards/
```


## 🗺️ Yol Haritası

- [x] Sistem metrikleri toplansın ✅
- [ ] Loglar Loki ile toplansın ✅
- [ ] Örnek dashboardlar eklensin ✅
- [ ] Mobil takip uygulaması 📱
- [ ] Discord/Telegram bildirim entegrasyonu 🔔
- [ ] CPU/Disk kullanımı için eşik uyarıları ⚠️

---

## 🤘 Katkıda Bulunan Projeler

- [Grafana](https://grafana.com)
- [Prometheus](https://prometheus.io)
- [Loki](https://grafana.com/oss/loki)
- [Node Exporter](https://github.com/prometheus/node_exporter)

---

## 🪄 Geliştirici

Bu proje ❤️ ile [rudeboy53](https://github.com/rudeboy53) tarafından hazırlanmıştır.

> Katkılar, yıldızlar ⭐ ve geri bildirimler her zaman beklenir!
