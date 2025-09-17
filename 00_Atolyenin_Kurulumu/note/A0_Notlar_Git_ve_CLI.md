# Git & GitHub Notlarım

## Git'in Üç Aşamalı Yapısı
Git, bir projenin geçmişini kaydederken üç temel alan kullanır:

1. **Çalışma Alanı (Working Directory)**  
   Dosyaların üzerinde aktif olarak değişiklik yaptığımız alandır.

2. **Hazırlık Sahnesi (Staging Area / Index)**  
   `git add` ile değişiklikleri buraya ekleriz.  
   Yani "bu dosyanın bu hali commit edilecek" demiş oluruz.

3. **Depo (Repository)**  
   `git commit` ile staging alanındaki değişiklikler kalıcı olarak kaydedilir.  
   Geçmiş commit'ler burada tutulur.

---

## Temel Git Komutları

| Komut | Açıklama |
|-------|----------|
| `git init` | Bulunduğun klasörde yeni bir git deposu oluşturur. |
| `git clone <url>` | Uzak bir depoyu bilgisayarına kopyalar. |
| `git status` | Dosyaların durumunu gösterir (değişti mi, staged mi?). |
| `git add <dosya>` | Dosyayı staging alanına ekler. |
| `git add .` | Tüm değişiklikleri staging alanına ekler. |
| `git commit -m "mesaj"` | Staging alanındaki değişiklikleri kaydeder. |
| `git log` | Commit geçmişini listeler. |
| `git log --oneline --graph --all` | Commit geçmişini özet ve dallarıyla gösterir. |
| `git diff` | Henüz commit edilmemiş değişiklikleri gösterir. |
| `git branch` | Tüm branch'leri listeler. |
| `git branch <isim>` | Yeni branch oluşturur. |
| `git checkout <branch>` | Belirtilen branch'e geçiş yapar. |
| `git switch <branch>` | Branch değiştirmek için alternatif komut. |
| `git merge <branch>` | Belirtilen branch'i mevcut branch ile birleştirir. |
| `git push` | Yerel commit'leri uzak depoya gönderir. |
| `git pull` | Uzak depodaki değişiklikleri indirip birleştirir. |
| `git fetch` | Uzak depodaki değişiklikleri indirir ama birleştirmez. |
| `git reset --hard <commit>` | Projeyi belirtilen commit'e geri döndürür. (Dikkatli kullan!) |
| `git revert <commit>` | Belirtilen commit'in değişikliklerini geri alır. |
| `.gitignore` | Takip edilmeyecek dosya/klasörleri belirtmek için dosya. |

---

# Temel CLI (Command Line Interface) Notlarım

## Klasör & Dosya İşlemleri
| Komut                 | Açıklama                                            |
| --------------------- | --------------------------------------------------- |
| `pwd`                 | Hangi klasörde olduğumu gösterir.                   |
| `ls`                  | Bulunduğum klasördeki dosya ve klasörleri listeler. |
| `ls -a`               | Gizli dosyaları da listeler.                        |
| `cd <klasör>`         | Belirtilen klasöre geçiş yapar.                     |
| `cd ..`               | Bir üst klasöre çıkar.                              |
| `cd ~`                | Ana dizine (home) gider.                            |
| `mkdir <isim>`        | Yeni klasör oluşturur.                              |
| `touch <dosya>`       | Yeni boş dosya oluşturur.                           |
| `rm <dosya>`          | Dosya siler.                                        |
| `rmdir <klasör>`      | Boş klasör siler.                                   |
| `rm -r <klasör>`      | İçinde dosya olan klasörü siler.                    |
| `cp <kaynak> <hedef>` | Dosya kopyalar.                                     |
| `mv <kaynak> <hedef>` | Dosya taşır veya yeniden adlandırır.                |

## Dosya Görüntüleme & Düzenleme
| Komut | Açıklama |
|-------|----------|
| `cat <dosya>` | Dosyanın içeriğini gösterir. |
| `nano <dosya>` | Dosyayı basit editörde açar. |
| `vim <dosya>` | Dosyayı gelişmiş editörde açar. |

## Kullanışlı Ek Komutlar
| Komut | Açıklama |
|-------|----------|
| `history` | Önceki komutları listeler. |
| `clear` | Ekranı temizler. |