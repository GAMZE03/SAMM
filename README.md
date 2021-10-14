# SAMM ÖDEV
# Array Manipulation Python
    N= 10 boyutunda bir dizi oluşturulmalıdır. a ve b  2 index; k ise değerdir. Örnek verilecek olursa:
    a=1 b=5 ve k=3 
    a=4 b=8  ve k=7  
                      ifadelerinde n=10 a kadar değerler bulunmaktadır. 1 ile 5 arasındaki değerler 3 olarak tanımlanmıştır.
                      5'ten sonra 10 a kadar ise 0 değeri almıştır. 2. ifadeye gelecek olursak; 4'ten 8'e kadar olan kısma 7
                      değeri eklenmeli diğer kısımlar olduğu gibi kalmalıdır. İşlem bu şekilde devam edecektir. Sonunda en
                      büyük değer 10 olacağı için 10 değeri dönecektir.
                      
# Array Manipulation C++ 

Yukarıda bahsedilen ödev C++ kullanılarak da gerçekleştirilmiştir.

 A[Start_Index] = A[Start_Index] + k ,
 
 A[End_index+1] =  A[End_index+1] –  k    tekniği kullanılmıştır.
    
#Border Security System
Ödev projesinden kısaca bahsedilecek olursa Başkentler ve ülkeler için GEOJSON dosyalarında depolanan geometrik verileri kullanarak, başkentteki ana denetleyici ile en yakın sınır arasında ölçülen sınır çevrelerini ve kablo uzunluklarını hesaplamak amaçlanmıştır.
JSON formatında hesaplanılmalıdır. 

MS Visual Studio kullanılarak C++ ile yazılır ve Linux terminalinde çalıştırılmıştır. GASON kütüphanelerinin yardımıyla .geojson uzantılı dosya içerikleri ayrıştırılmıştır. 
Çalışan bir bağımlılık zinciri kurulmasına yardımcı olarak programın çalıştırıldığı ve yürütülmesine yardımcı olan Linux tabanlı Makefile kullanılır. Komut bağımsız değişkenleri -c ve -t, aynı dizinde depolanan tüm dosyalar, kitaplıklar ve üçüncü taraf araçlarla çalışmak üzere program için komut terminali üzerinden ayrıştırılan iso_a3 kodlarla kullanılır.

Programın çalıştırılması kısmına gelinirse ayrıştırılan dosya içerikleri JSON nesneleri olarak gerçekleştirmeye yardımcı olan ve öğelerine erişmeyi kolaylaştıran  "lib_geojson" için başlık ve kaynak dosyalarda bazı değişiklikler yapılır.  C++'ta uygulanması planlanan işlevler, mesafe hesaplaması, çevre hesaplaması ve kablo uzunluğu hesaplamasını algılamaktır. Bunlara uygun adlandırmalar yapılmıştır. Makefile ana derleyici olarak çalışır ve kaynak dizini yükledikten sonra terminalde "make" çalıştırılarak kullanıma hazırlanır. Daha sonra uygun komut verilir. 

Yapılması planlanan algoritma aşağıdaki gibidir.

Terminali Linux'ta açma (Herhangi bir uygulama ile Windows'ta da kullanılabilir.)
Kaynak dizini kitaplıklara, .geojson dosyalarına ve kaynak kod dosyalarına yükleme
Projeyi derlemek için terminalde "make" çalıştırma
Uygun komutu yazma ve sonuçları alma.
