# 🌿 Branch (Dal) & 🔗 Merge (Birleştirme)

```
   \   ^__^
    \  (oo)\_______
       (__)\       )\/\
           ||----w |
           ||     ||
```

---

## 🌱 **Branch (Dal) Nedir?**

- Ana koddan bağımsız geliştirme yapmak için kullanılır.
- Özellik eklerken ya da hata düzeltirken ana kodu bozmadan çalışmanı sağlar.

---

## 🌟 **Yeni Branch Oluşturma**

```bash
git branch yeni-ozellik
git checkout yeni-ozellik
# veya kısaca:
git checkout -b yeni-ozellik
```

---

## 🔄 **Branch'ler Arası Geçiş**

```bash
git checkout main
```

---

## 🔗 **Merge (Birleştirme) Nedir?**

- Farklı branch’lerde yapılan değişiklikleri tek bir branch’te toplamak için kullanılır.

```bash
git checkout main
git merge yeni-ozellik
```

---

## 🚨 **Merge Conflict (Çakışma) Çözümü**

> 💥 İki branch aynı satırı değiştirirse çakışma olur!

- Dosyayı aç, çakışan satırları düzenle.
- Sonra:

```bash
git add .
git commit -m "Çakışma çözüldü"
```

> 🧩 Çakışma çözmek ekip işinin bir parçasıdır!
