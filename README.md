# Dünyayı Yemek
*Teknik olmayan insanlar için programlamaya giriş*

*(programcılar hakkındaki şakaları açıklayarak)*

Okumaya başla

![Dino](https://github.com/maidis/eat-the-world-tr/raw/master/dino.jpg "Dino")

Asıl çalışma: [Eat the World](http://eattheworldbook.com/)

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

\* çevirmenin notu: Farklı meslekler için kaç kişi gerekiyor esprilerini görmek için bir [Google araması](https://www.google.com.tr/search?q=ampülü+değiştirmek+için+kaç) yapabilirsiniz.

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

### Açıklama 4. Sayıları sıralamadan düşünen makinelere

algoritma

> Programcıların yaptıklarını açıklamak istemediklerinde kullandıkları kelime.

Algoritmalar, doğru sırada izlenmesi gereken kesin talimatlardır. Doğru uygulanan algoritmanın sonucu daima aynıdır.

İlk başta alıştırma yapmaya değer popüler algoritmalar, verileri sıralamak ve bulmak için kullanılanlardır.

Algoritma bilgisi her yerde kullanışlıdır.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=k4RRi_ntQc8
" target="_blank"><img src="http://img.youtube.com/vi/k4RRi_ntQc8/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

### Açıklama 5. Mantık sizi A'dan B'ye götürür

> Bir kadın, programcı olan kocasını eline talimatlarını vererek markete gönderir
>
> "Bir ekmek al ve yumurta varsa bir düzine olsun".
>
> Adam bir düzine ekmekle gelir ve “Yumurtaları vardı.” der.

Yukarıda bahsedilen şakadaki anahtar sözcük "if [...]" olup, hemen hemen her programlama dili için temel kontrol talimatıdır.

Bu talimatları kullanan çay yapma algoritmasına bir örnek[3]:

1. Su ısıtıcı su içermiyorsa, su ısıtıcısını doldurun
2. Su ısıtıcısının fişini prize takın ve çalıştırın.
3. Çaydanlık boş değilse çaydanlığı boşaltın.
4. Çay yapraklarını çaydanlığa koyun.
5. Su ısıtıcısındaki su kaynar değilse adım 5'e gidin.
6. Su ısıtıcısını kapatın.
7. Su ısıtıcısından çaydanlığa su dökün.

[3] http://users.evtek.fi/~jaanah/IntroC/DBeech/3gl_algorithm1.htm

### Açıklama 6. Biri sizinle aynı sorunu yaşadı

> Chuck Norris her zaman kendi tasarım desenlerini kullanır ve en sevdiği döner tekmedir.

Tasarım desenleri, tipik sorunları çözmenin kanıtlanmış yollarıdır. Bunlar, projeye yapıştırılabilecek hazır kod parçaları değil, sorunun nasıl çözülmesi gerektiğini gösteren açıklamalar veya şablonlardır.

Algoritma, takip edilecek bir talimatlar dizisiyken tasarım desenleri, bileşenler arasındaki ilişkiyi açıkça göstermek için kodun nasıl yapılandırılacağını açıklar. Bu yönüyle tasarım desenleri algoritmalardan ayrılır.

### Açıklama 7. Sinemaya yalnız gidecekseniz iki bilet satın almazsınız

> İyimser biri bardağın yarım dolu olduğunu söyleyecektir; karamsar biri, yarısı boş diyecektir; ve mühendis sana bardağın olması gerektiğinden iki kat büyük olduğunu söyleyecektir.

Yazılım yazarken çalıştırılacağı aygıtları ve sınırlamalarını (işlemci özellikleri, mevcut bellek) dikkate alırsınız.

Günümüzde, bilgisayarlarda bulunan bellekler ucuz ve işlemciler birkaç yıl önce yapılmış olanlardan çok daha verimlidir ancak yazılımlar da genellikle daha karmaşıktır.

1991 yılında bir iPhone inşa etmenin yaklaşık 3,5 milyon dolar maliyete sahip olacağı ve mevcut belleğin 1,44 milyon dolara mal olacağı hesaplandı![4]

[4] http://www.businessinsider.com/iphone-35-million-1991-2014-2?IR=T

### Açıklama 8. Neredeyse her zaman ekip çalışmasıyla ilgilidir

> GIT şakalarıyla ilgili sorun, herkesin kendi sürümünün olmasıdır.

GIT, popüler bir sürüm kontrol sistemidir. GIT’in özelliklerinden biri, kod deposunun yerel bir kopyasını saklayabilme ve kendi sürümüne sahip olma özelliğidir.

Sürüm kontrol sistemlerini kullanmak, kodu düzgün bir şekilde saklayarak ve önceki sürümlerden birini geri yüklemenin kolay bir yolunu sunarak diğer ekip üyeleriyle olan işbirliğini kolaylaştırır.

### Açıklama 9. Çalışma ortamı

> Neden programcılar UNIX sever?
>
> unzip, strip, touch, finger, grep, mount, fsck, more, yes, fsck, fsck, fsck, umount, sleep

UNIX, 1969'da Bell Labs'ta geliştirilen bir işletim sistemidir. unzip, strip vb. bu sistemde mevcut komutların listesidir. Örneğin, unzip komutu, dosya arşivini açmak için kullanılır.

Tercih edilen işletim sistemi genellikle üzerinde çalıştığınız teknolojiye bağlıdır. Örneğin, iPhone uygulamaları oluşturmak isterseniz OS X sistemini kullanmanız gerekir; ancak Windows Phone uygulamalarını oluştururken en kolay yol Windows sistemini kullanmanızdır.

Çalışma ortamı ayrıca Bütünleşik Geliştirme Ortamı (Integrated Development Environment, IDE), sürüm kontrol sistemi ve proje yönetimi araçları (örneğin Jira) içerir.

### Açıklama 10. Problemler nasıl çözülür

> ;
>
> Saklambaç şampiyonu.

Noktalı virgül ";" birçok programlama dilinde bir yönerge ayracı olarak kullanılır.

Günümüzde, iyi gelişmiş programlama ortamları bu ayracın eksikliğini kolayca tespit eder, ancak önceki yıllarda programcılar metin düzenleyiciler kullanırdı. Programlama maceranızı başlatıyorsanız, kullanmak istediğiniz teknoloji için uygun bir bütünleşik geliştirme ortamı seçmelisiniz (örneğin Xcode, iPhone uygulamaları oluşturmak için doğal seçenektir).

İnternette, diğer programlama sorunlarını çözmenize yardımcı olacak çok sayıda kaynak vardır. En popülerlerinden biri [Stack Overflow](http://stackoverflow.com/) sitesidir. Doom ve Quake gibi oyunların yaratıcısı John Carmack, bu web sitesinin geliştiricilerin verimliliğini artırarak milyarlarca dolar tasarruf sağladığını düşünüyor[5].

[5] https://twitter.com/id_aa_carmack/status/380018564792455168

### Açıklama 11. Yapılmış olması mükemmel olmasından iyidir

> Domuz ve tavuk yolda yürüyormuş.
> 
> Tavuk şöyle demiş: "Hey domuz, bence bir restoran açmalıyız!"
> 
> Domuz cevap verir: "Hım, olur belki, ne isim vereceğiz?"
> 
> Tavuk yanıtlar: "Beykın ve Yumurta’ya ne dersin?"
> 
> Domuz bir an düşünür ve "Hayır, sağol. Ben kendimi adamış olurum, ancak sen sadece işe karışmış olursun" der.

Bu fabl, scrum uygulama geliştirme yöntemindeki iki tip proje üyesini tanımlamaya yöneliktir: projeye tamamen bağlı olan ve projenin sonuçlarından mesul olan domuzlar ve projede danışılacak ve projenin gelişimi hakkında bilgilendirilecek olan tavuklar. Bu benzetme, pastırma sağlayabilecek domuz (sunulması için domuzun ölmesinin gerektiği fedakar bir bağış) ile yumurta sağlayacak tavuğun (kurban olunmayan) karşılaştırılmasına dayalıdır.

Bir scrum projesi için, ürün sahibi, scrum yöneticisi ve geliştirme ekibi, projeye adamış insanlar olarak kabul edilirken müşteriler ve üst düzey yöneticilerse projeye dahil ancak projeye bağlı olmayan kişiler olarak görülür[6].

[6] https://en.wikipedia.org/wiki/The_Chicken_and_the_Pig

### Açıklama 12. Kitlelerin Bilgeliği*

> Sarışın, sarhoş ve uzaylı bir bara gider, ancak bu bir Microsoft barıdır ve bu yüzden kapalıdır.

1990'lı yıllarda ve 2000'lerin başında, Microsoft kapalı bir şirketti ve sırlarını kesinlikle koruyordu. Microsoft ve büyük şirketlerin aksine, kodları açık kaynak olarak sunulan projeler geliştirildi.

Şu anda bu değişiyor ve Microsoft, açık kaynak projelerde de yoğun şekilde yer alıyor. Bu, şirkete benzersiz avantajlar sağlar, çünkü çalışanlara ek olarak, gönüllüler yazılım geliştirmede yer alabilir. Bu, hata bulma, yeni işlevsellik ekleme ve yeni sürümleri yayımlama süreçlerini hızlandırır.

\* çevirmenin notu: başlık, asıl ismi The Wisdom of Crowds olan bir James Surowiecki kitabından geliyor.

### Açıklama 13. Kaybettiğim her şey içinde aklımı özlüyorum en çok

> İnsanlar iki gruba ayrılabilir: yedekleme yapan ve yapacak olanlar.

Yedekleme, örneğin bir arızadan sonra yazılımı geri yüklemek için kullanılabilen bir veri kopyasıdır. Yedekleme oluşturmak çok iyi bir uygulamadır.

2017'deki ciddi bir olay, GitLab'daki veri kaybıydı. Yedekleme oluşturulmasına rağmen, yedeklerin iyi test edilmediği ve bazı verilerin geri yüklenemediği ortaya çıktı[7].

Yedeklemeler oluşturun ve mümkün olduğunca sık bir şekilde bunlardan veri kurtarıp kurtaramadığınızı kontrol edin.

[7] https://about.gitlab.com/2017/02/01/gitlab-dot-com-database-incident/

## BÖLÜM III. Bilgisayarların çalışmasıyla ilgili nüktelerin açıklaması

> Bilgisayarlar işe yaramaz. Sana sadece cevaplar verebilirler.
>
> \- Pablo Picasso

### Açıklama 1. Bilgisayarlarla gerçekte nasıl konuşuruz

> Dünyada sadece 10 tür insan vardır: ikilikten anlayan ve anlamayan kişiler.

İkilik sayı, bit denilen öğelerden oluşur ve bunlar, iki durumdan birini (0 veya 1) alabilir. İkilik sayı 10, ondalık olarak 2'dir ve bu nedenle, yukarıdaki şakada iki tür insandan bahsedilmektedir.

İkilik sayılar ondalık sayılara aşağıdaki gibi dönüştürülür:

* **10**: 1*(2^1) + 0*(2^0) = 2
* **1001**: 1*2^3 + 0*2^2 + 0*2^1 + 1*2^0 = 9
* **1101**: 1*2^3 + 1*2^2 + 0*2^1 + 1*2^0 = 13

Bilgisayarlarda ikilik kod kullanımı çok etkilidir. Durum 0 (bit kapalı) ve 1 (açık), düşük ve yüksek gerilimle gösterilebilir.

### Açıklama 2. Bilginin temsili
> Adamın biri bara girer ve 1.4 kök bira ister. Barmen, "Sizden fazladan ücret almak zorundayım, bu kök birası kayan nokta."
> 
> Adam "Bu durumda, en iyisi sen onu double yap" demiş.

Bilgisayarlar, bellekte bir ve sıfır akışları olarak depolanan ikili kod kullanır. Yazılım oluştururken, programcının görevi bilgisayara bu akışı nasıl yorumlayacağını anlatmaktır.

Örneğin, bilgisayarın belleğinde saklanan 1000001 ikili kodu bir A harfi veya 65 değerinde bir tam sayı anlamına gelebilir.

Şakaya geri dönersek, kayan nokta ve double, bilgisayar belleğindeki sayıları kesirli olarak depolamanın bir yoludur. Bir double, hassasiyeti ve boyutu iki katına çıkarır. Adam 1.4 istediği için bu bir tamsayı olamaz (kesirli bir bileşen içermeyen sayı), ancak bir kayan nokta veya double olabilir.

Double sayılar, kesirli sayılar için neredeyse her zaman daha iyi bir seçimdir çünkü daha hassastır (ancak daha çok bilgisayar belleği kullanır) [1].

[1] xRmg ve evrae'ye yorumları için teşekkürler.

### Açıklama 3. İnsanlar saymaya birden başlar
> Bilgisayar biliminde iki zor şey vardır: önbellekten kaldırma, bir şeylerin isimlendirilmesi ve off-by-one hataları [1].

Off-by-one, 0'dan başlamanız gerekirken 1'den başlamak gibi bir hata yaptığınızda meydana gelen bir programlama hatasıdır [2]. Modern programlama dillerinde bir dizinin ilk elemanı genellikle 0 indeksine atanır.

[1] Lampshadish2'nun işaret ettiği gibi bu şaka, Phil Karlton'un "Bilgisayar Biliminde sadece iki zor şey vardır: önbelleği geçersiz kılma ve isimlendirme işleri" adlı ünlü alıntıdan gelmektedir.
[2] knome, bu hatanın çoğunlukla bir programcının bir dizinin sınırlarını yanlış olarak kontrol ettiğinde (örneğin, yalnızca iki elemanlı bir listenin üçüncü maddesini almaya çalışırken) meydana geldiğini belirtti.

### Açıklama 4. Sınıf ne söyleyeceğini bilmektir

> Nesne yönelimli olarak varlıklı olmanın yolu nedir?

> Miras

**Jeff Goodell**: Basitçe, nesne yönelimli yazılımın tam olarak ne olduğunu açıklar mısınız?

**Steve Jobs**: Nesneler insanlar gibidir. Onlar yaşar, bir şeylerin nasıl yapılacağı hakkındakki bilgileri nefes alır gibi içlerine çekip sahip oldukları hafızayla bir şeyleri hatırlayabilirler. Ve onlarla çok düşük bir seviyede etkileşim kurmaktan ziyade, burada yaptığımız gibi, çok yüksek bir soyutlama seviyesinde etkileşime girebiliyorsunuz.

İşte bir örnek: Eğer senin çamaşır nesnen olsaydım, bana kirli kıyafetlerini verebilir ve bana "Çamaşırlarımı yıkatabilir misin lütfen" diye bir mesaj yollayabilirsin. San Francisco'daki en iyi çamaşırhanenin nerede olduğunu öğrenirim. İngilizce konuşurum ve cebimde dolar olar. Bu yüzden dışarı çıkıp bir taksiye binip şoföre San Francisco'daki bu yere gitmesini söylerim. Kıyafetlerini yıkatırım, tekrar taksiye atlarım ve buraya geri dönerim. Sana da temiz kıyafetlerini verip "işte temiz kıyafetlerin" derim.

Bunu nasıl yaptığımı bilmezsin. Çamaşırhanenin yeri hakkında hiçbir bilgin yoktur. Belki de Fransızca konuşabiliyorsundur sadece ve hatta bir taksi bile durduramazsın. Durdursan bile ödeme yapamazsın, cebinde hiç dolar yoktur. Yine de ben bunların hepsini nasıl yapacağımı bilirim. Ve bunların hiçbirini sen bilmek zorunda değilsin. Bütün bu karmaşıklık içimde gizliydi ve çok yüksek bir soyutlama seviyesinde etkileşim kurabiliyorduk. Nesneler budur. Karmaşıklığı kapsüllerler ve bu karmaşıklığa yönelik arayüzler yüksek seviyelidir [1].

[1] https://www.rollingstone.com/culture/culture-news/steve-jobs-in-1994-the-rolling-stone-interview-231132/

### Açıklama 5. Her teknede bir cankurtaran teknesi bulunmaz*

> Bunu mu demek istediniz? özyineleme

Google'da "özyineleme" kelimesini ararsanız Google size aynı sözcüğü ifade edip etmediğinizi sorup duracaktır... Bu bir hata değil, kendisini çağıran bir fonksiyonu tanımlayan özyineleme fikrini gösteren Google programcıları şakasıdır.

\* çevirmenin notu: Başlığın aslı not every boat has a lifeboat ve Edsger W. Dijkstra'nın oğlunun özyinelemeyi nasıl anladığıyla ilgili [hikayede](https://stackoverflow.com/questions/46612470/could-i-ask-for-physical-analogies-or-metaphors-for-recursion/46882956#46882956) geçiyor: "Birkaç yıl sonra, beş yaşındaki oğlum bana, özyineleme fikrinin bozulmamış zihne ne kadar sorunsuz girdiğini gösterecekti. Kasabanın ortasında benimle birlikte yürürken bana birdenbire şunu söyledi: Baba, her teknede bir cankurtaran teknesi yoktur, değil mi? Bu fikre nereden kapıldın dedim. Baba cankurtaran teknesinin daha küçük bir cankurtaran teknesinin olması mümkündür, ancak o zaman da bu cankurtaransız tekne olurdu."

### Açıklama 6. Bir eşleşme aramak
> Soru: Bir düzenli ifade ötekine ne demiş?
> 
> Cevap: .+

Düzenli ifadeler, bir dizi eşleşen string'i tanımlayabilen veya bir string'in önemli kısımlarını belirtebilen kalıplardır.

.+ deseni, "her şey" anlamına gelir, daha belirgin olarak ifade etmek gerekirse . herhangi bir karakter, + ise bir veya birkaç kez demektir.

### Açıklama 7. Verilerinizi güvende tutmak

> Two hashes walk into a bar, one was a salted.

Temel güvenlik kurallarından biri, kullanıcı parolalarını şifrelenmemiş biçimde (kolay görülebilir ve kopyalanabilir) saklamamaktır.

"Düz" metinde yazılmış parolalar yerine, veritabanlarında hash'lar (sabit uzunluğa dönüştürülmüş metinler) saklanır. Bir hash ile kullanıcı tarafından ayarlanan parolayı yeniden oluşturmak çok zordur, ancak parolaya sahip olununca oluşturulan hash değerinin veritabanında saklananla aynı olup olmadığı karşılaştırabilir.

Salt, oluşturulan hash'ı koruyan, kullanıcı parolasına eklenen ek bir parametredir.

### Açıklama 8. Dil engelini aşmak
> S: Sigmund Freud'a göre, fear ve sex arasında ne vardır?
> 
> A: Fünf.*

Dile özgü harfler (örneğin ü) gibi dilsel farklılıkları göstermek için kullanılan bir şaka.

Günümüzde, yazılım oluştururken dünya çapında erişim çok önemli bir konu olarak görülüyor, dolayısıyla yazılım birçok dilde kullanılabilir olmalıdır. Karakter kodlama şeması genellikle belirli bir dil veya dil grubu için tasarlanmıştır. Örneğin, Windows sisteminde kullanılan Windows-1250, Orta Avrupa dillerindeki metinleri temsil edecek şekilde tasarlanmıştır.

Bu durumu çözmenin bir yolu, farklı alfabe ve 😂 benzeri emoji simgeleri içeren UTF-8 gibi daha geniş bir karakter aralığı içeren bir kodlama şeması kullanmaktır.

\* çevirmenin notu: Almanca'da dört, beş, altı: vier, fünf, sechs. İngilizce'de dört, beş, altı: four, five, six.
