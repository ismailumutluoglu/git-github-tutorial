# 🎬 Sıfırdan Git & GitHub Projesi – Uygulamalı Video Rehberi

Bu örnekte, sıfırdan bir proje klasörü oluşturup Git ile takip altına alacak, GitHub’da yeni bir repo açacak ve tüm süreci adım adım komutlarla göstereceğiz. Aynı zamanda yeni bir branch açıp değişikliği GitHub’a göndererek Pull Request oluşturmayı da uygulayacağız.

---

## 1️⃣ Yerel Proje Klasörü Oluşturma

```bash
mkdir benim-ilk-git-projem
cd benim-ilk-git-projem
echo "# Benim İlk Git Projem" > README.md
```

---

## 2️⃣ Git Başlatma ve İlk Commit

```bash
git init
git add .
git commit -m "İlk commit: README eklendi"
```

---

## 3️⃣ GitHub’da Yeni Repo Açma

1. GitHub hesabına gir.
2. Sağ üstteki ➕ işaretinden **New repository** seç.
3. Repo ismini gir: `benim-ilk-git-projem`
4. README oluşturma kutusunu işaretleme (çünkü yerelde eklendi).
5. **Create repository** butonuna tıkla.

---

## 4️⃣ Yerel Repoyu GitHub’a Bağlama ve Push Etme

```bash
git remote add origin https://github.com/KULLANICIADIN/benim-ilk-git-projem.git
git branch -M main
git push -u origin main
```

> Not: "KULLANICIADIN" kısmını kendi GitHub kullanıcı adınla değiştir.

---

## 5️⃣ Yeni Branch Oluşturma ve Değişiklik Yapma

```bash
git checkout -b yeni-ozellik
echo "\nBu projeye yeni bir özellik eklendi." >> README.md
git add README.md
git commit -m "Yeni özellik eklendi"
```

---

## 6️⃣ Branch’i GitHub’a Gönderme

```bash
git push -u origin yeni-ozellik
```

---

## 7️⃣ GitHub’da Pull Request (PR) Oluşturma

1. GitHub’daki repo sayfana git.
2. “Compare & pull request” veya “New pull request” butonuna tıkla.
3. Açıklama ekle, “Create pull request” de.

---

## 8️⃣ Pull Request’i Birleştirme (Merge Etme)

1. PR sayfasında "Merge pull request" butonuna tıkla.
2. Sonra "Confirm merge" ile onayla.

---

## 9️⃣ Ana Branch’i Yerelde Güncelleme

```bash
git checkout main
git pull origin main
```

---

## 🎥 Ekstra Video İpuçları

- Tüm adımları terminalde ve GitHub arayüzünde göster.
- Komutların ne işe yaradığını kısa kısa anlat.
- İşlemler bittikten sonra GitHub’daki repoyu ve yerel dosyalarını kontrol et.

---

> Bu rehberle sen de adım adım bir projeyi Git ve GitHub ile yönetmeyi öğrenebilirsin! 🚀
