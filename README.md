# Lynx IP Logger

💀 Basit bir IP logger sistemi. Ziyaretçi siteyi açtığında IP adresi alınır ve Telegram üzerinden bildirim gönderilir.

## Özellikler

- Flask web sunucusu
- Ziyaretçi IP adresi ve tarayıcı bilgisi loglanır
- Telegram bot ile anında bildirim gönderilir
- Railway ile 7/24 açık çalışır

---

## Kurulum

1. GitHub hesabınızdan bu depoyu klonlayın veya çatallayın.
2. Railway hesabı oluşturun: https://railway.app/
3. Railway üzerinden yeni proje oluşturun.
4. Projenizi GitHub ile bağlayın.
5. **Environment Variables (Çevresel Değişkenler)** kısmına şu değişkenleri ekleyin:
   - `BOT_TOKEN` → Telegram bot tokeniniz
   - `CHAT_ID` → Telegram kullanıcı ID'niz

---

## Telegram Bot Ayarları

1. Telegram’da [@BotFather](https://t.me/BotFather) ile yeni bot oluşturun.
2. Bot tokeninizi alın.
3. @userinfobot ile kendi `CHAT_ID`’nizi öğrenin.
4. Railway’e bu bilgileri girin.

---

## Kullanım

1. Projenin dağıtım linkini (örnek: `https://lynx-ip-logger.up.railway.app`) açan herkesin IP’si Telegram’a iletilir.
2. Loglar `ip_log.txt` dosyasına da yazılır.

---

## Güvenlik Uyarısı ⚠️

Bu uygulama yalnızca **eğitim ve test amaçlıdır**. İzinsiz kişisel veri toplamak KVKK, GDPR ve diğer yasalara aykırıdır. Lütfen etik kurallara uyun.
