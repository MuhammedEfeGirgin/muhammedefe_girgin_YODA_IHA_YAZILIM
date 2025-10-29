# muhammedefe_girgin_YODA_IHA_YAZILIM
Git yazdığımız dosyaların farklı versiyonlarını kaydedip , daha önceki versiyonlara ulaşabilmemizi sağlar.
Github ise bu dosyaları internet ortamında kaydetmemizi ve paylaşabilmemizi sağlıyor
cd ile hangi dosyada .git dosyası oluşturulacak seçilir.
pwd ile bu yol kontrol edilebilir.
git commit komutu seçtiğin dosyaya git tarafından benzersiz bir kimlik atar ve bu sayede takibe almış olur.
(-m ekleyip kendin de atayabilirsin)
git diff komutu ile dosyalarda yapılan değişiklikler görüntülenebilir.
git add komutu ile yapılan değişiklikler geçici alana eklenir.
git diff --staged ile geçici alandaki değişiklikler görülebilir.
git restore ile değişikleri geri alır ve dosyanın en son commit edilmiş haline geri döndürür 
git reset dosyaları geçici alandan çıkartır ama çalışma alanındaki değişiklikleri silmez 
git remote add origin ile github'daki linkimizi ana link olarak atıyoruz
git push ile yerel repoyu githuba gönderiyoruz.
git clone (proje linki) ile çalışma alanınıza githubdan proje indirebilirsiniz.
git remote -v uzak bağlantıları görüyoruz.
git log ile commit geçmişlerini görüyoruz.
git fetch ile githubdaki yapılan değişiklikler yerel depoya çekilir.
git merge ile githubdaki güncellemeler yereldeki çalışma alanınıza alınır.
git pull ile merge+fetch yapılır.
branch ile ana dosyaya başka bir dal açılır ve halihazırda ana dosyaya müdahale edilmemiş olunur.
git branch ile hangi branch'dayız o görünür
git switch ile branch'lar arası geçiş yapılır.
git commit --amend ile commit değiştirilebilir.
git checkout (kod) ile önceki commitleri gezebiliyoruz.
git reset --soft HEAD-1 ile son commit silinir.
git reset --mixed HEAD-1 commit silinir ama dosyadaki değişiklikler korunur.
git push --force ile silinme işlemi githuba da yanısr
git revert (kod) commit geri almak için yeni bir commit oluşturur.
git reflog ile silinmiş dahil bütün commitler görünür. (90 gün)
git reset --hard (kod) ile kaybolan commite geri dönülebilir. 
git fork ile proje üzerinde yapılan değişiklikler githuba da yansır.
(sona . konursa tüm dosyalara etki eder.)
