# Dünyayı Yemek
*Teknik olmayan insanlar için programlamaya giriş*

*(programcılar hakkındaki şakaları açıklayarak)*

Okumaya başla

![Dino](https://github.com/maidis/eat-the-world-tr/raw/master/dino.jpg "Dino")

Yazar: [Dawid Andrzejewski](https://medium.com/@kemyd)

Rusça çeviri: [devSchacht/Eat-the-World](https://github.com/devSchacht/Eat-the-World)

Türkçe çeviri: [maidis/eat-the-world-tr](https://github.com/maidis/eat-the-world-tr)

İçindekiler

## BÖLÜM I. Tüm bu nüktelerdeki rollerin açıklaması
> Bilgiyi bir çeşit semantik ağaç gibi görmek önemlidir — yapraklara/ayrıntılara girmeden önce temelleri, yani gövde ve büyük dalları anladığınızdan emin olun yoksa onların tutunabileceği hiçbir şey olmayacaktır.
>
> \-Elon Musk

### Açıklama 1. Programcılar gerçekten ne yapar
> Bir ampulü değiştirmek için kaç programcı gerekir?*
>
> \- Hiç. Bu bir donanım problemidir.

Donanımların bakımı ve yapılandırması servis teknisyenleri veya BT uzmanları tarafından gerçekleştirilirken, programcılar yazılım oluşturmayla ilgilenirler.

\*çevirmenin notu: Farklı meslekler için kaç kişi gerekiyor esprilerini görmek için bir [Google araması](https://www.google.com.tr/search?q=ampülü+değiştirmek+için+kaç) yapabilirsiniz.

### Açıklama 2. Doğru ürünü nakletmek

> Proje yöneticisi, dokuz kadının bir ay içinde bebek doğurabileceğini düşünen kişidir.

Yazılım geliştirme, artan kaynakların nadiren doğrusal verimlilik artışını sağladığı yaratıcı bir süreçtir ve proje yöneticisi, doğru projeyi (ürünü) zamanında teslim etmekle yükümlüdür.

### Açıklama 3. Beni düşündürtmeyin

> Bir kullanıcı arabirimi şaka gibidir. Onu açıklamak zorunda kalıyorsanız o kadar da iyi değil demektir.

Kullanıcı arabirimi, yazılımla insan etkileşiminin oluştuğu alandır (ör. bir çevrimiçi web sitesi formu). İyi tasarlanmış arayüz, kullanıcıları için sezgisel ve anlaşılabilir olmalıdır.

Tanınmış bir kullanıcı deneyimi uzmanı olan Steve Krug, kullanıcı arayüzlerini tasarlarken temel ilkenin "Beni Düşündürtmeyin!" olduğunu söyler.

### Açıklama 4. Daima çevrimiçi

> Ubuntu, "Ben Debian’ı yapılandıramam" anlamına gelen çok eski bir Afrikaanca kelimedir.

Ubuntu ve Debian, açık kaynak topluluğu tarafından geliştirilen özgür GNU/Linux işletim sistemleridir[1]. Ubuntu dağıtımının kullanımı ve yapılandırması yeni başlayanlar için daha kolaydır. Ubuntu kelimesi Güney Afrika kabilelerinin dilinden gelir ve "başkalarına karşı insanlık" anlamına gelir.

Sunucu ve ağ yapılandırması genellikle sistem yöneticisi veya ağ yöneticisi tarafından gerçekleştirilir.

[1] robertmassaioli, Ubuntu'nun Debian üzerine kurulu olduğunu [hatırlatıyor](https://www.reddit.com/r/programming/comments/62szbn/an_introduction_to_programming_for_nontechnical/dfpzimr/).

### Açıklama 5. Organize edilmiş bir veri koleksiyonu

> Bir SQL sorgusu bir müzeye gider, iki çok ünlü tablonun yanına yaklaşır ve "Bunları birleştirebilir miyim?" diye sorar.

SQL (Structured Query Language, Yapısal Sorgulama Dili), veritabanları oluşturmak, bunları değiştirmek ve gelecekte alınabilecek verileri yerleştirmek için kullanılır. SQL veritabanları, ilgili verileri içeren tablolara bölünür ve örneğin SQL sorguları sayesinde bunlar tekrar birleştirilebilir.

### Açıklama 6. Ürününüzü test etmekten hoşlanmıyorsanız, müşterileriniz de test etmeyi sevmeyeceklerdir

> Bir ampulü değiştirmek için kaç yazılım testçisi gerekir?
> 
> \- Hiç. Yazılım testçileri sadece odanın karanlık olduğunu fark eder. Testçiler problemleri düzeltmez, onları bulurlar.

Yazılım testçilerinin rolü, programı çeşitli ortamlarda (web tarayıcıları, işletim sistemleri) çalıştırmak ve hata aramaktır.

### Açıklama 7. Sözcükleri akıllıca seçmek iyi bir uygulamadır

> Bir SEO uzmanı bir bar, barlar, bira bahçesi, mekan, salon, gece kulübü, mini bar, bar taburesi, taverna, pub içinde bira ile dolaşır.

SEO uzmanı, arama sonuçlarında üst sıralarda yer almak adına web sitelerini (Google, Bing gibi) arama motorları için optimize eder.

Birincil görevlerinden biri, web sitesini içerisindeki içeriğe uygun olarak doğru bir şekilde tanımlamak ve web sitesi konumlandırması için hangi anahtar kelimelerin kullanılması gerektiğini belirlemektir.

### Açıklama 8. Ödemeyi kim yapıyor

> Gördüğümde ne istediğimi bileceğim

Kendiniz, arkadaşlarınız, çalıştığınız firma veya kendi müşterileriniz için yazılımlar oluşturabilirsiniz (freelance, serbest çalışma).

Yazılım geliştirme süreci boyunca en iyi spesifikasyonu oluşturmayı başarıyor olsak bile, emin olabileceğimiz tek şey değişimdir.

## BÖLÜM II. Programcının çalışmalarıyla ilgili nüktelerin açıklaması

> Yazılım Dünyayı Yiyor
>
> \-Marc Andreessen

### Açıklama 1. İlk sözcükleriniz

> Bir yeni programcı bara girer, etrafına bakar ve "Merhaba Dünya!" der.

Programlama kitaplarında ve eğitsellerde, ekrana "Merhaba Dünya!" yazarak dilin temellerini gösteren programın kodlanması yaygın bir uygulamadır.

[Hello World Quiz](http://helloworldquiz.com/) sitesinde, "Merhaba Dünya" mesajı gösteren mini program kodlarına bakarak kullanılan programlama dilini tahmin etmeye çalışabilirsiniz.

### Açıklama 2. Hangi programlama diline ihtiyacınız var?

> \- “Tak, tak.”
>
> \- “Kim o?”
>
> çok uzun duraklama...
>
> \- “Java.”

Java'nın ilk sürümlerinde yazılmış programlar yavaştı; bu, diğer şeylerin yanı sıra, o dilde yazılmış kodu yürüten ağırkanlı sanal makinenin başlatılmasıyla ilgiliydi.

Pazarlama ortamında, insanların 6,5 mm’lik matkap ucu istemediklerini, 6,5 mm’lik delik istediklerini anlatan çok popüler bir ifade vardır. Matkap ucu, yalnızca görevleri yerine getirmek için kullanılır ve aynısı düzinelerce programlama dili için de geçerlidir.

Geliştirilen projeye bağlı olarak popüler programlama dilleri:
* **WWW**: Python, PHP, Ruby, JavaScript
* **iOS için mobil uygulama (iPhone, iPad)**: Objective-C, Swift
* **Android için mobil uygulama**: Java
* **İşletim sistemleri**: C, C++
* **Oyunlar**: C++

### Açıklama 3. Programlar okuyacak insanlar için yazılmalıdır

> Bunu yazdığımda, yalnızca tanrı ve ben ne yaptığımı anlıyorduk. Şimdi, yalnızca tanrı biliyor.

Programcılar kodları okuma ve anlama konusunda çok zaman harcarlar; bu nedenle, bunu onlar için kolaylaştırmak çok önemlidir.

Kullanılan çözüm açıkça görülüyor olsa bile sonraki haftalarda veya aylarda da böyle olacağı anlamına gelmez – özellikle de yeni insanlar projeye katılırken.

Windows XP sisteminde bulunan 3B tilt oyunu, düşük kod kalitesi ve belge eksikliği nedeniyle yeni Windows sürümlerine dahil edilmedi. Microsoft programcıları oyunun nasıl çalıştığını anlayamadılar, bu nedenle diğer görevlerle bağlantılı olarak oyunu yeni işletim sistemi sürümüne aktarma fikrinden vazgeçtiler[2].

[2] https://blogs.msdn.microsoft.com/oldnewthing/20121218-00/?p=5803




