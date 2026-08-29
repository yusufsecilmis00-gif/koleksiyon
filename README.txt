PARA KOLEKSİYONUM — WEB SÜRÜMÜ

Bu sürüm gerçek üyelik/giriş sistemi için Supabase kullanır.
Her kullanıcının kayıtları user_id + Row Level Security ile ayrıdır.

KURULUM
1) Supabase'te yeni bir proje oluştur.
2) SQL Editor'ü açıp schema.sql içeriğini çalıştır.
3) Project URL ve Publishable Key değerlerini al.
4) config.js içindeki iki alanı doldur.
5) index.html + config.js dosyalarını GitHub Pages / Cloudflare Pages gibi statik hosting'e yükle.
6) Supabase Authentication ayarlarında e-posta doğrulama kullanıyorsan yayınladığın sitenin adresini Redirect URL / Site URL ayarlarına ekle.

GİRİŞ
- Üye Ol: e-posta + şifre + ad
- Giriş Yap: e-posta + şifre
- Çıkış Yap

KOLEKSİYON
- Ülke
- Yıl
- Değer
- Birim
- Arama
- Ülke filtresi
- Sil

GÜVENLİK
Tarayıcıya service_role anahtarı koyma. Sadece Supabase'in publishable key'ini kullan.
