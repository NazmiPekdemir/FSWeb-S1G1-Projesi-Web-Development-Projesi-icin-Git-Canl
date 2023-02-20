## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
c- Açık kaynak kontrol sistemidir. Terminalden kodlar ile çalışır. 

2. Git ile GitHub arasında ne fark var?
c- Github bulut tabanlı bir sistemdir. Git yerel bir bilgisayara ihtiyaç duyarken Github`ın böyle bir ihtiyacı yoktur. Github Git
kodlarını çalıştırsa bile bu kodları bazıları arayüzden oluşturulabilir. Örnek:Branch

3. Neden bir branch oluşturuyoruz? 
c- Fork ile bir clone oluuşturduktan sonra kendimizie daha rahat kod oynayabileceğimiz ekstra bir kod alanı oluşturuyoruz. 
Bu sayde ana koda hiç bir zarar gelmeden kod ile oynayabiliyoruz? 

4. Pull Request'in amacı nedir?
c- Ana sahibin paylaştığı open-source kodtaki hataları düzenleyen kişiler kodun sahibini düzeltilmiş halini gönderip koda 
katkıda bulunuyorlar. Ama her kod ana kodu düzlemeyeceği için kodun sahibi kendi isteğine bağlı olarak pull requestleri kontrol ediyor.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
c- Emin değilim ama Merge komutunu kullanırsak "ad-soyad" branch`i main branche dönebilir.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
c- git fetch Uzak bir depodan yapılan değişiklikleri çakışma yapmadan yerel bilgisayara yükler.
   git pull Uzak depodan yapılan değişiklikleri çakıştırır. Bu da soruna yol açar.
   git merge Başka bir branchte çalışılan değişiklikleri kendi çalıştığınız branch`e entegre eder.

7. Merge conflict nedir?
c- İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?
c- Merge Conflict yaşayan kişiler ortak çalışıp bu sorunu çözebilir.


