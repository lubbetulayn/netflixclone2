# Netflix Benzeri Sekme (Tab) Bileşeni README
- - Bu README belgesi, HTML, CSS ve JavaScript kullanarak oluşturulan bir Netflix benzeri sekme (tab) bileşenini açıklamaktadır. Bu bileşen, bir web sayfasında farklı sekmelere tıkladığınızda ilgili içeriği görüntülemenizi sağlar. Netflix benzeri bir başlık, sekmeler ve içerikler içerir.

* İçindekiler
Başlangıç
Kullanım
HTML Yapısı
CSS Stili
JavaScript İşlevselliği


- - Başlangıç
Bu sekme bileşenini kullanmaya başlamak için aşağıdaki adımları izleyin:

Bu kodları kendi HTML, CSS ve JavaScript dosyalarınıza ekleyin.
HTML yapısını düzenleyerek sekme öğelerini ve içeriklerini özelleştirin.
CSS stilini değiştirerek bileşeni projenizin tasarımına uyarlayın.
JavaScript kodu, sekmeler arasında geçiş işlevselliğini yönetir.
Kullanım
Bu bileşen, aşağıdaki gibi bir kullanımı destekler:

Başlık bölümü: Netflix benzeri bir başlık ve "Sign In" bağlantısı içerir.
Sekmeler: Üç sekme bulunur - "Cancel at any time", "Watch anywhere" ve "Pick your price".
İçerikler: Her sekme, ilgili içeriği ve açıklamaları içerir.
Tablo: Fiyatlandırma planlarını gösteren bir tablo vardır.
Alt Bilgi: İletişim bilgileri ve bağlantılar içeren bir alt bilgi bölümü bulunur

- - CSS Stili
Bileşenin CSS stilleri aşağıdaki gibi görünmektedir:

Başlık bölümü, sekmeler, içerikler ve diğer öğeler özelleştirilmiş stil özelliklerine sahiptir.
Sekmeler arasında geçiş yapılırken seçilen sekme altı çizgisi eklenir.
İçerikler gizli olarak başlar ve seçilen sekme tıklanarak görüntülenir.
CSS stillerini projenizin tasarımına uyacak şekilde özelleştirebilirsiniz.

- - JavaScript İşlevselliği
Bileşenin JavaScript kodu, sekme tıklamalarını dinler ve ilgili içeriği gösterir. İşte JavaScript işlevselliğinin özeti:

selectItem(e): Sekme öğelerine tıklamaları dinler ve seçilen sekme öğesinin alt çizgisini ekler, ilgili içeriği görüntüler.
removeBorder(): Tüm sekme öğelerinden alt çizgiyi kaldırır.
removeShow(): Tüm içerik öğelerinden "show" sınıfını kaldırır.