# 🎒 Alisizm Configurable Gather & Process System

[![Tebex Store](https://img.shields.io/badge/Purchase-Tebex-orange?style=flat-square&logo=tebex)](https://alisizm.tebex.io/package/7470363)
[![Framework](https://img.shields.io/badge/Framework-QBCore%20%7C%20ESX%20%7C%20Standalone-blue?style=flat-square)](#)
[![YouTube Channel](https://img.shields.io/badge/YouTube-Subscribe-red?style=flat-square&logo=youtube)](https://www.youtube.com/@Alisizmsc)

A highly versatile, fully config-driven gathering and processing system for FiveM servers. Tailor every interaction, location, and reward without touching the core code.

---

## 🔗 Links
*   **🛒 Purchase:** [Tebex Store](https://alisizm.tebex.io/package/7470363)
*   **📺 YouTube Channel:** [Alisizm Development](https://www.youtube.com/@Alisizmsc)
*   **🛍️ My Store:** [View all scripts](https://alisizm.tebex.io/package/)

---

## 🇬🇧 English Description

### 📖 Overview
This script is a comprehensive gathering and processing system that is fully customizable through the configuration file. Players interact at locations you define; actions are displayed with a progress bar, and configured items are either added to or removed from their inventory.

### ✨ Features
*   **Config-Driven Locations:** Coordinates, zones/radius, blips, markers, and interaction points are entirely set in the config. Easily move activities to different map areas without editing the core code.
*   **Config-Driven Items:** Required materials, rewards, amounts, chance rates, and item names are defined in the config. Tailor the loop to fit any custom item setup.
*   **Universal Framework Support:** Can be seamlessly set up for **QBCore**, **ESX**, or **Standalone** servers (easily selectable via config).
*   **Multiple Progress Bar Support:** One script supports several popular progress bar libraries. Simply pick the progress bar resource your server runs from the config.

### ⚙️ Customization via Config
*   **Locations:** 
    *   Define `vector3` / `vector4` coordinates for gather/process spots.
    *   Set interaction distances or PolyZone/target zones.
    *   Optional blips (customize label, sprite, color, and scale).
    *   Marker customization (type, color, and visibility).
*   **Items:** 
    *   Set required items and amounts needed to start an action.
    *   Define reward items and amounts on success (fixed numbers or min–max ranges).
    *   Configure remove/add order and refund rules upon cancellation or failure.
    *   Adjust cooldowns, action durations, animation syncs, and prop settings.
*   **Progress Bar:** 
    *   Select your active library in one place (e.g., `Config.ProgressBar = 'ox_lib'`).
    *   Manage duration, label, cancel behavior, and animation synchronization.

### 📋 Dependencies (Example)
*   **Framework:** `qb-core` or `es_extended`
*   **Target (Optional):** `ox_target` / `qb-target`
*   **Progress:** Your selected library (e.g., `ox_lib`)
*   **Inventory:** `ox_inventory` / `qb-inventory` (depending on your server setup)

### 🚀 Installation
1.  Place the resource in your `resources` folder.
2.  Set your framework, locations, items, and progress bar type in `config.lua`.
3.  Ensure your chosen progress bar resource is started.
4.  Add `ensure [resource-name]` to your `server.cfg`.

---
---

## 🇹🇷 Türkçe Açıklama

### 📖 Genel Bakış
Bu script, yapılandırma dosyası (`config.lua`) üzerinden tamamen özelleştirilebilen gelişmiş bir toplama ve işleme sistemidir. Oyuncular belirlediğiniz konumlarda etkileşime girer; süreç progress bar ile gösterilir ve tanımladığınız eşyalar (item) envantere eklenir veya envanterden silinir.

### ✨ Özellikler
*   **Config Tabanlı Konumlar:** Koordinatlar, yarıçap/zone, blip, marker ve etkileşim noktaları config üzerinden değiştirilir. Kodu düzenlemeden haritada farklı bölgeler yaratabilirsiniz.
*   **Config Tabanlı Eşyalar (Items):** Gerekli malzemeler, verilen ödüller, miktarlar, şans oranları ve eşya isimleri config’de tanımlanır. İstediğiniz meslek veya hobi setine göre süreci özelleştirebilirsiniz.
*   **Framework Uyumu:** **QBCore**, **ESX** veya **Standalone** kurulumlara göre yapılandırılabilir (sunucunuzun altyapısına göre config içerisinden seçim yapmanız yeterlidir).
*   **Çoklu Progress Bar Desteği:** Sunucunuzda hangi progress bar resource’u aktifse config’den onu seçebilirsiniz. Tek script ile farklı kütüphaneler desteklenir.

### ⚙️ Config ile Özelleştirme
*   **Konum:** 
    *   Toplama / işleme noktalarının `vector3` / `vector4` koordinatları.
    *   Etkileşim mesafesi veya PolyZone / target bölgesi ayarları.
    *   İsteğe bağlı harita blip'leri (isim, ikon, renk, boyut).
    *   Marker tipi, rengi ve görünürlük ayarları.
*   **Eşyalar (Items):** 
    *   İşleme başlamak için gerekli eşyalar ve miktarları.
    *   İşlem sonunda verilecek ödüller ve miktarları (sabit sayı veya min–max aralığı).
    *   Eşya silme / ekleme sırası ve işlem iptalinde/başarısızlığında iade kuralları.
    *   Bekleme süresi (cooldown), işlem süresi (duration), animasyon ve prop ayarları.
*   **Progress Bar:** 
    *   `Config.ProgressBar = 'ox_lib'` gibi tek bir satırla aktif kütüphaneyi seçme.
    *   Süre, etiket (label), iptal edilebilirlik ve animasyon senkronizasyonu.

### 📋 Bağımlılıklar (Örnek)
*   **Framework:** `qb-core` veya `es_extended`
*   **Target (Varsa):** `ox_target` / `qb-target`
*   **Progress:** Seçtiğiniz kütüphane (örn. `ox_lib`)
*   **Envanter:** `ox_inventory` / `qb-inventory` (sunucu ayarınıza göre)

### 🚀 Kurulum
1.  Resource klasörünü sunucunuzun `resources` dizinine koyun.
2.  `config.lua` dosyasını açarak framework, konumlar, eşyalar ve progress bar tipini ayarlayın.
3.  Kullandığınız progress bar eklentisinin (resource) aktif (ensure edilmiş) olduğundan emin olun.
4.  `server.cfg` dosyanıza `ensure [resource-adi]` satırını ekleyin.

---

## ⚖️ License Information / Lisans Bilgilendirmesi

### English
**This software is NOT Open Source.** 
This product is a commercial resource licensed and distributed exclusively via the official Tebex store. This resource is protected by the FiveM Asset Escrow system and copyright laws.

*   **Usage:** By purchasing this resource from the official Tebex store, you are granted a non-exclusive license to use it on your own FiveM server.
*   **Customization:** You are **ALLOWED** to modify the unencrypted configuration files (`config.lua`) to tailor the locations, items, and settings for your server.
*   **Transfer:** You may transfer the asset license to another Keymaster account using the official transfer feature provided by the Cfx.re Keymaster system. Reselling the asset outside of this official system is strictly prohibited.
*   **Redistribution:** You may **NOT** redistribute, share, publish, resell, or leak any part of this software to third parties. Others must acquire their own license via the official Tebex store.
*   **Enforcement:** Hidden cryptographic markers and watermarks are securely embedded within the software files to track unauthorized redistribution. Unauthorized distribution or tampering with the escrow system will result in an official DMCA takedown notice submitted directly to **Cfx.re (FiveM)** and **Tebex**, leading to permanent account bans and server blacklisting.

### Türkçe
**Bu yazılım Açık Kaynak (Open Source) DEĞİLDİR.**
Bu eklenti, ticari bir üründür ve yalnızca resmi Tebex mağazası üzerinden lisanslanarak dağıtılmaktadır. Bu ürün, FiveM Asset Escrow sistemi ve telif hakkı yasalarıyla korunmaktadır.

*   **Kullanım:** Bu ürünü resmi Tebex mağazasından satın alarak, yalnızca kendi FiveM sunucunuzda kullanmak üzere münhasır olmayan bir kullanım hakkı elde edersiniz.
*   **Özelleştirme:** Sunucunuzun yapısına göre konumları, eşyaları ve ayarları düzenlemek için şifrelenmemiş yapılandırma dosyalarını (`config.lua`) düzenlemenize **İZİN VERİLİR**.
*   **Transfer:** Lisansınızı resmi Cfx.re Keymaster sistemi üzerinden başka bir Keymaster hesabına transfer edebilirsiniz. Bu resmi sistem haricinde ürünün üçüncü şahıslara satılması kesinlikle yasaktır.
*   **Dağıtım:** Bu yazılımın herhangi bir parçasını üçüncü şahıslarla dağıtmak, paylaşmak, yayınlamak, satmak veya sızdırmak **YASAKTIR**. Diğer kullanıcılar kendi lisanslarını resmi Tebex mağazası üzerinden edinmelidir.
*   **Yaptırım:** İzinsiz dağıtımları tespit edebilmek amacıyla eklenti dosyalarının içerisine gizlenmiş şifreler yerleştirilmiştir. Escrow sistemini kırmaya çalışmak, izinsiz dağıtım veya sızıntı durumunda doğrudan **Cfx.re (FiveM)** ve **Tebex** platformlarına resmi telif ihtarı (DMCA) gönderilecek olup; hesaplarınız kalıcı olarak kapatılacak ve sunucunuz kara listeye alınacaktır.
