<div align="center">

# 🐢 slow3r

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/abdulrahmanqdev/slow3r?style=flat-square&color=yellow"/>
  <img src="https://img.shields.io/github/forks/abdulrahmanqdev/slow3r?style=flat-square&color=green"/>
  <img src="https://img.shields.io/github/last-commit/abdulrahmanqdev/slow3r?style=flat-square&color=orange"/>
</p>

<p align="center">
  <strong>İstek hızını kontrol altına alan hafif bir rate limiter / throttle aracı.</strong><br/>
  API çağrılarını, görevleri veya herhangi bir işlemi kolayca yavaşlat ve yönet.
</p>

</div>

---

## 📖 Genel Bakış

**slow3r**, aşırı yüklemeyi önlemek için istek ve işlem hızını kontrol eden minimalist bir araçtır. API rate limit hatalarıyla boğuşmadan işlemlerini güvenli bir şekilde yönetmeni sağlar.

---

## ✨ Özellikler

- ⏱️ Özelleştirilebilir gecikme süresi
- 🔁 Toplu işlem desteği
- 🪶 Sıfır bağımlılık, ultra hafif
- 🔧 Basit ve anlaşılır API
- ✅ Promise tabanlı async/await desteği

---

## 🛠️ Teknoloji Yığını

| Teknoloji | Amaç |
|---|---|
| JavaScript | Dil |
| Node.js | Çalışma Ortamı |

---

## 🚀 Başlarken

```bash
git clone https://github.com/abdulrahmanqdev/slow3r.git
cd slow3r
npm install
```

### Kullanım

```js
import { slow3r } from './slow3r';

// Her istekte 500ms gecikme
await slow3r(islemListesi, 500);
```

---

## 🤝 Katkıda Bulunma

1. Repoyu fork'la
2. Yeni dal oluştur (`git checkout -b ozellik/yeni-ozellik`)
3. Değişiklikleri kaydet ve Pull Request aç

---

## 👤 Geliştirici

**@abdulrahmanqdev**
