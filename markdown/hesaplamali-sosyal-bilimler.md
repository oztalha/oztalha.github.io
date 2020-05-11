---
title: Açık Veri & Hesaplamalı Sosyal Bilimler
date: 2015-03-18 10:11
author: Talha Oz
category: CSS, CSS Reading Notes, Turkish
slug: hesaplamali-sosyal-bilimler
status: published
...

<!-- pandoc --template=GitHub.html5 --self-contained hesaplamali-sosyal-bilimler.md -o ../posts/hesaplamali-sosyal-bilimler.html-->
Editör notu: Çevirmiş olduğum bu yazı, açık veri ve hesaplamalı sosyal bilimler üzerine olup, 2009 yılında Science makalesinde yayınlanmıştır. Yazarlar bu alanın kurucuları arasında sayılabilirler.

David Lazer, Alex Sandy Pentland, Lada Adamic, Sinan Aral, Albert Laszlo Barabasi, Devon Brewer, Nicholas Christakis et al. "Life in the network: the coming age of computational social science." *Science (New York, NY)* 323, no. 5915 (2009): 721.

Makaleyi PDF olarak buradan temin edebilirsiniz: <http://gking.harvard.edu/files/LazPenAda09.pdf>

Orjinal kaynak da burada mevcut: <http://www.sciencemag.org/content/323/5915/721>

Açık Veri & Hesaplamalı Sosyal Bilimler
---------------------------------------

Hayatımızı ağların içinde yaşıyoruz. Düzenli olarak e-postalarımızı kontrol ediyor, cep telefonlarımızla hemen her yerde konuşuyor, toplu taşıma araçlarında akıllı biletimizi kullanıyor, kredi kartlarımızla alışveriş yapıyoruz. Kamuya açık yerlerdeki hareketlerimiz video kaydına alınabildiği gibi sağlık durumumuz da dijital dosyalarda tutuluyor. Herkese açık blog yazıları yazabilir, arkadaşlıklarımızı çevirimiçi sosyal ağlarda sürdürebiliriz. Bu işlemlerimizin her biri dijital kırıntı bırakıyor ve bu kırıntılar birleştirilerek elde edilecek birey veya grup davranışları ile ilgili resimler, hayatımız, kurumlar ve toplumlar hakkındaki anlayışımızı değiştirecek potansiyeli barındırıyor.

Büyük miktarlardaki verileri toplama ve işleme kapasitesindeki artış biyoloji ve fizik gibi bilimleri dönüştürdü. Fakat, veri güdümlü “hesaplamalı sosyal bilimler”in gün yüzüne çıkması çok daha yavaş gerçekleşmekte. Ekonomi, sosyoloji ve siyaset biliminin önde gelen dergilerinde bu alanla ilgili pek çalışma göremiyoruz. Lakin, hesaplamalı sosyal bilimler gerçekleşiyor - Google ve Yahoo gibi İnternet şirketlerinde ve ABD Ulusal Güvenlik Dairesi (NSA) gibi devlet kurumlarında. \[Korkarız ki\] Hesaplamalı sosyal bilimler sadece bazı özel şirketlerin ve devlet kurumlarının çalışma alanı hale gelebilir; Veyahut, özel verilere erişip makaleler yayınlayan -fakat çalışmaları kritiğe tabi tutulamayan veya tekrar edilemeyen- seçkin bazı akademik araştırmacılar türeyebilir. Her iki senaryo da bilginin toplanması, doğrulanması ve yayılması açısından uzun vadede toplumun çıkarına sonuçlar doğurmaz.

-Açık akademik bir çevrede temellenen- hesaplamalı sosyal bilimler, topluma, birey ve topluluk anlayışını geliştirmekle ne gibi değerler sunabilir? Hesaplamalı sosyal bilimlerin ortaya çıkmasının önündeki engeller nelerdir?

Bugüne kadar insan etkileşimleri ile ilgili araştırmalar, genelde kişinin bir defaya mahsus vermiş olduğu kendi beyanatına dayalı verilerle yapılıyordu. Güvenlik kameraları (1), e-posta, akıllı kimlikler gibi yeni teknolojiler ise uzun-süreli etkileşimlerin anbean resimlerini veriyor, ilişkilerin hem yapısını hem de içeriğini görmemizi sağlıyor. Örneğin, e-posta verisinden grup etkileşimleri incelenebilir, insan ilişkilerinin zamansal dinamikleri ile ilgili sorular sorulabilir: çalışma grupları kısa sürede stabil hale geliyor mu yoksa zaman içinde çok mu değişiyor (2)? Üretken grupları ve bireyleri tanımlayan iletişim örüntüleri nelerdir? Aldığımız haberlerin veya içeriklerin çeşitliliği gücümüzü veya performansımızı belirler mi (3)? Yüzyüze grup etkileşimleri “sosyometre”ler ile zamanla ölçülebilir. Giyilebilir bu tarz teknolojiler fiziksel yakınlık, mekan, hareket ve sair cihetlerde bireysel davranışlar ve kollektif etkileşimleri kayıt altına alabilir. Bu veri, şirket içi yakınlık veya iletişim örüntüleri, yüksek performanslı birey ve gruplardaki akış örüntüleri gibi konularda ilginç sorular sormamızı sağlayabilir (4).

Ayrıca, toplumun makro sosyal ağının nasıl göründüğünü ve zaman içinde nasıl şekillendiği de incelenebilir (5). Telefon şirketleri yıllara ait telefon görüşmesi örüntülerine sahip olduğu gibi, Yahoo ve Google gibi e-portallar da dünya genelinde anlık mesajlajma verilerine sahipler. Bu veriler toplum düzeyinde, kuşatıcı bir şekilde iletişim örüntülerinin resmini çiziyor mu? Bu etkileşimler ekonomik üretkenliği veya toplum sağlığını ne şekilde etkiliyor? Dahası, insanların hareketlerini takip etmek de çok kolaylaştı (6). Cep telefonları büyük ölçekte insanların hareketlerini ve fiziksel yakınlıklarını takip etme olanağı sunuyor (7). Bu veriler, salgın hastalıklar bilimi (epidemiyoloji) adına kullanışlı bilgiler verebilir: Gripteki gibi fiziksel yakınlıkla bulaşan bir patojen toplumda nasıl yayılıyor?


| ![](../images/red-blue-blogs.gif) |
|:--:|
| **Blog dünyasından bir veri kümesi**. Kırmızılar: Muhafazakar bloglar, maviler: Liberal bloglar, turuncu linkler liberalden muhafazakara, mor linkler muhafazakardan liberale. Blogların boyutu diğer bloglardan aldığı linkle orantılı. (9) çalışmasından izinle tekrar üretilmiştir.|


İnternet insanların ne dediğini ve nasıl bağlandığını anlamamız adına tamamen farklı bir kanal sunuyor (8). Son siyasi atmosferi düşünün mesela, argümanların yayılışının, dedikoduların, politik veya diğer mevzularda alınan pozisyonların takip edildiği blog dünyası (9), seçmenin endişelerinin aramalarda görünür olduğu bir dünya. Sanal dünyalar, doğaları gereği bireyin her türlü davranışını kayıt altına alıyor, araştırma için de çok çeşitli fırsatlar sunuyor - normalde yapılması mümkün olmayan veya kabul edilemez deneyler gibi (11). Benzer şekilde, sosyal ağ siteleri, bireyin kendi ağındaki etkisinden tutun, zevklerini, oradan halini keyfini, hatta sağlık durumunu anlamaya olanaklar sunarken (12), doğal dil işleme (NLP) İnternetten ve diğer kaynaklardan edinilen metinleri organize ve analiz etme kapasitesini artırıyor (13).

Hasılı, emsali görülmemiş bir genişlik, derinlik ve ölçekte veriyi toplama ve işlemeyle gün yüzüne çıkıyor hesaplamalı sosyal bilimler. Ancak, kimiciddi bariyerler, bu gelişmeyi kısıtlayabilir. Bugün insan davranışlarını anlama adına kullandığımız yöntemler, toplumdaki neredeyse tüm bireylerin dakika dakika etkileşimlerinin ve lokasyonlarının tanımlı olduğu terabyte’larca veri henüz ortada yokken geliştirildi. Örneğin, bir kaç düzine insanın tek seferlik verileri ile temellenmiş günümüzdeki sosyolojik ağ teorisi, çok büyük boyutta ve uzun zaman boyunca, milyonlarca insanın lokasyon, finansal işlemler, iletişimsel bilgilerine dair bize ne verebilir? Elbette, insan etkileşimlerini barındıran, yeni ortaya çıkan bu büyük veri kümeleri, bize insan davranışları ile ilgili nitelikli bilgiler ve yeni perspektifler sunabilir, fakat şuanki paradigmalarımız bunu algılayacak ölçüde olmayabilirler.

Hesaplamalı sosyal bilimlerin gelişmesinin önünde devasa kurumsal engeller de var. Gözlemleme ve müdahele adına fizik ve biyolojinin konusu olan maddeler başka türlü zorluklar çıkarıyordur. Ama, ne quarklar ne de hücreler gizli yönlerinin keşfedilmesi veya bulundukları şartların değiştirilmesi sonucu protestoya kalkışırlar. Altyapı açısından da biyolojiden hesaplamalı biyolojiye geçişe nispeten daha ciddi bir uçurum var sosyal bilimler ile hesaplamalı sosyal bilimlere geçişte; çünkü, farklı noktalardan izleme, izin alma ve güvenlik şifrelemesi gibi gereksinimleri var. Sosyal bilimlerde kaynak daha az ve hatta mühendislik veya bilgisayar bilimleri ile sosyal bilimler bölümleri arasındaki fiziksel (ve idari) mesafe bile diğer bilimlerden daha fazla.

Belki de en dikenli zorluk işin veri kısmında, erişim ve mahremiyet itibarıyla. Zira verinin çoğu kişiye tescilli (cep telefonu kullanımı ve finansal işlemler bilgileri gibi). AOL tarafından ‘anonimize’ edilerek kamuya açılan müşterilerinin arama kayıtlarının fiyasko ile sonuçlanması bireylerin ve kurumların şahsi bilgileri özel şirketlerle paylaşmasındaki potansiyel risklerin farkındalığını artırdı (14). Araştırmayı kolaylaştıran, tüketici mahremiyetini koruyan, ve şirketlere de yükümlülük muafiyeti getiren, endüstri ve akademi işbirliğini ve veri paylaşımını sağlayacak sağlam modellere ihtiyaç var. Genel olarak, mahremiyet meselelerini düzgün bir şekilde idare etme en temel husus. ABD Ulusal Araştırma Konsülünün coğrafi bilgiişlem sistemleri raporunda ortaya koyduğu gibi dikkatlice anonimize edilmiş veriden bile kimlikleri tespit etme mümkün olabiliyor (15). Geçen sene, ABD Ulusal Sağlık Enstitüsü ve Wellcome Trust bazı genetik veritabanlarına çevirimiçi erişimi kesti (16). Her ne kadar veriler anonimize edilmiş, belli başlı genetik işaretçilerin toplu frekansı verilmişse de, araştırmalar her bir bireyin istatistiksel tüm bilgilerini içermesinden ötürü boyle veritabanlarinda deanonimizasyonun mümkün olabileceğini ortaya çıkardı (17).

Tek bir dramatik hadise henüz doğmakta olan hesaplamalı sosyal bilimleri boğacak kurallar ve yönetmelikler doğurabileceğinden, riski düşürecek ama araştırma potensiyelini koruyacak öz-düzenleme prosedürleri, kurallar ve teknolojiler gerekmekte. Bir köşe taşı mahiyetinde, ABD Enstitüsel Değerlendirme Kurumları (IRBs), yeni gelişen şartlarda gerçekleşebilecek saldırıları ve doğabilecek zararları anlama adına teknik bilgilerini artırmalı, çünkü halihazırdaki şartlar zarar paradigmalarına uygun düşmüyor. Çoğu IRB, kompleks verinin deanonimize edilebileceğini değerlendirebilecek donanıma sahip değiller. Dahası, güvenli ve merkezi bir veri altyapısının oluşturulması IRBler için bir gereklilik olabilir. Günümüz şartlarında veriler, veri güvenliği ve muhtelif protokolleri anlaması farklı yetilerde olan gruplar arasında dağınık bir vaziyette bulunuyor. Araştırmacıların kendileri çalışmaları için gerekli veriyi tutarken mahremiyeti koruyacak teknolojiler geliştirmelidir. Bu sistemler, nihayetinde, müşteri mahremiyeti ve veri güvenliği için endüstriler için faydalı olabilir (18).

Son olarak, diğer yeni doğan bilimler gibi (örn., sürdürebilirlik bilimi) hesaplamalı sosyal bilimler de yeni bilim adamlari yetiştirmek için bir paradigma geliştirmeli. Üst düzey komiteler ve editöryal heyetler disiplinler arası çalışmaları anlamalı ve ödüllendirmeli. Başlangıçta, hesaplamalı sosyal bilimler, sosyal ve bilgisayar bilimcilerden oluşan takımların ortak çalışması olmalı. Uzun vadede ise akademi, hesaplamalı sosyal bilimciler mi yetiştirmeli, yoksa hesaplamadan anlayan sosyal bilimciler ya da sosyal bilimlerden anlayan bilgisayar bilimciler mi, karar vermeli. Bilişsel bilimin (cognitive science) oluşumu bize hesaplamalı sosyal bilimlerin gelişimi için güçlü bir model sunuyor. Bilişsel bilim nörobiyolojiden filozofiye, ordan bilgisayar bilimine geniş bir alanla ilgileniyor. Bilişsel bilim ortak bir alan oluşturmak için ciddi miktarda kaynak yatırımı çekti, ve geçtiğimiz çağda toplum yararına büyük ilerlemer kaydetti. Hesaplamalı sosyal bilimlerin de benzer bir potansiyele sahip olduğunu ve benzer yatırımları hak ettiğini ifade edebiliriz.

### Referans ve Notlar

1.  D. Royet al., “The Human Speech Project,” Proceedings of the 28th Annual Conference of Cognitive Science Society, Vancouver, BC, Canada, 26 to 29 July 2009
2.  J. P. Eckmannet al., Proc. Natl. Acad. Sci. U.S.A. 101, 14333 (2004)
3.  S. Aral, M. Van Alstyne, “Network Structure & Information Advantage,” Proceedings of the Academy of Management Conference, Philadelphia, PA, 3 to 8 August 2007
4.  A. Pentland, Honest Signals: How They Shape Our World (MIT Press, Cambridge, MA, 2008)
5.  J.-P. Onnelaet al., Proc. Natl. Acad. Sci. U.S.A. 104, 7332 (2007)
6.  T. Jebara, Y. Song, K. Thadani, “Spectral Clustering and Embedding with Hidden Markov Models,” Proceedings of the European Conference on Machine Learning, Philadelphia, PA, 3 to 6 December 2007
7.  M. C. González, Nature 453, 779 (2008)
8.  D. Watts, Nature 445, 489 (2007)
9.  L. Adamic, N. Glance, in Proceedings of the 3rd International Workshop on Link Discovery (LINKDD 2005), pp. 36–43; http://doi.acm.org/10.1145/1134271.1134277
10. J. Teevan, ACM Trans. Inform. Syst. 26, 1 (2008)
11. W. S. Bainbridge, Science 317, 472 (2007)
12. K. Lewiset al., Social Networks 30, 330 (2008)
13. C. Cardie, J. Wilkerson, J. Inf. Technol. Polit. 5, 1 (2008)
14. M. Barbarao, T. Zeller Jr., “A face is exposed for AOL searcher No. 4417749,” New York Times 9 August 2006, p. A1
15. National Research Council, Putting People on the Map: Protecting Confidentiality with Linked Social-Spatial Data, M.P. Gutmann, P. Stern, Eds. (National Academy Press, Washington, DC, 2007)
16. J. Felch, “DNA databases blocked from the public,” Los Angeles Times 29 August 2008, p. A31
17. N. Homer, S. Szelinger, M. Redman, D. Duggan, W. Tembe, PLoS Genet. 4, (2008) e1000167
18. M.V.A. has applied for a patent on an algorithm for protecting privacy of communication content
