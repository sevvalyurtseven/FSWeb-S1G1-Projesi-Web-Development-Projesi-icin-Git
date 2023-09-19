# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazilim gelistirme sureclerinde kullanilan bir versiyon kontrol sistemidir. Yani bizim kodlarimizda kimin ne yazdigini satir bazinda takip eder ve insanlar ayni dosyaya işlem yaptığı zaman çakışma olmasını engelliyor ya da çakışma olduğunda düzeltmemiz için bize araçlar sağlar.

2. Git ile GitHub arasında ne fark var?

Git bir versiyon kontrol yazilimidir. Projemizde yaptığımız değişiklikleri adım adım kaydetmemizi sağlar ama bunu bizim bilgisayarımızda yani yerel de yapar. İnternet bağlantısı olmadan veya kayıt olmadan kullanabiliriz. Bunun için bu yazılımı bilgisayarımıza indirmemiz lazım. Github ise projelerimizin cloud (bulut) tabanlı bir sistemde online olarak yer aldığı bir servistir. Bunun için www.github.com’a üye olmamız gerekir. GitHub ile başkalarının projelerine bakabiliriz, projelerine destek verebiliriz. GitHub'i çevrimdışı iken kullanamayız.


3. Neden bir branch oluşturuyoruz?

Üzerinde çalışılan kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız olarak ilerlemesini sağlayabilmek için bir branch olustururuz.


4. Pull Request'in amacı nedir?

Pull Request, bir kodun bir projeye katılması için kullanılan bir yöntemdir. Bu yöntem, projenin diğer üyelerinin kodunuzu inceleyip onaylamalarını veya değişiklik önermelerini içerir.



5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout - main dediğimiz zaman main branchine geçmiş oluruz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch, başka bir sunucunun projesindeki her türlü içeriği veya veriyi yerel sisteminize indirmek için kullanılan bir komuttur. Sistemde zaten mevcut olan yerel kodların üzerine yazılmaz.

git merge komutu, git branch tarafından oluşturulan bağımsız geliştirme satırlarını almanızı ve bunları tek bir branch'ta birleştirmenizi sağlar.

 git pull, bir deponun yerel sürümünü remote olarak güncellemek için kullanılan bir git komutudur. Varsayılan olarak, git pull geçerli yerel çalışma branch’ını (o an için kullanılan branch’ı) günceller ve diğer tüm branch’lar için remote-tracking branch’larını (uzaktan takip branch’ları) günceller.

git pull komutu, git fetch ve git merge komutlarının bir kombinasyonudur, bu nedenle başlangıçta git fetch komutunun işlevini yerine getirir ve daha sonra commit’i birleştirir ve yeni bir merge commit oluşturur.

7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. Buna merge conflict denir.

8. Merge conflict'i nasıl çözeriz?

Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.