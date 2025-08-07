# 🐞 Sık Karşılaşılan Hatalar & ✅ Çözümleri

```
╔══════════════════════════════╗
║     HATA & ÇÖZÜM REHBERİ     ║
╚══════════════════════════════╝
```

---

## 💢 **1. Merge Conflict (Birleştirme Çakışması)**

- **Sorun:** İki branch aynı satırda değişiklik yaptı.
- **Çözüm:** Dosyayı aç → Çakışan alanı düzelt → Kaydet.

```bash
git add .
git commit -m "Çakışma çözüldü"
```

---

## ⏪ **2. Yanlış Commit’i Geri Alma**

```bash
git reset --soft HEAD~1    # Son commit’i geri alır, değişiklikler korunur
git revert <commit-id>     # Belirli bir commit’i geri alır
```

---

## 🔗 **3. Uzak Repo Hatası (pull ile ilgili)**

```bash
git pull --rebase
```

---

## 🧹 **4. Untracked Files Temizleme**

```bash
git clean -f
```

---

> 📙 Daha fazla hata ve çözüm için: [Git Troubleshooting](https://www.atlassian.com/git/tutorials/undoing-changes)
