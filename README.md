Kare Kapan oyunu 2 kişi ile oynanan bir strateji oyunudur. Oyun alanında, 7 yatay ve 8 dikey çizginin oluşturduğu 42 adet kare bulunmaktadır.
Oyun, 28 beyaz ve 28 siyah taş ile oynanır. Oyunun amacı rakibin taş sayısını 3’e indirmektir.

Beyaz taşlarla oynayan oyuncu önce başlar. Sırası gelen oyuncu çizgilerin kesiştiği herhangi bir noktaya taş yerleştirerek kare elde etmeye çalışır. 
Oyuncuların ellerindeki taşlar bitene kadar sıra ile taşlar yerleştirilmeye devam edilir. Bütün taşlar yerleştirilinceye kadar oyunda hiçbir taş hareket ettirilemez veya taşlarla hamle yapılamaz.

Bütün taşlar yerleştirildikten sonra oyuncular elde ettikleri kareleri sayarlar ve elde ettikleri kare sayısı kadar seçecekleri rakip taşını oyun dışına çıkarırlar. 
Oyunun herhangi bir aşamasında, dışarı çıkarılacak bir rakip taşı seçilirken oluşmuş kareler bozulamaz.

Daha sonra hamle sırası gelen oyuncu, kendi taşlarından birisini hareket ettirerek kare oluşturmaya çalışır. 
Önü boş olan taş istenildiği kadar yatay ya da dikey hareket ettirilebilir ancak taşların üzerinden hiçbir durumda atlanamaz.
Yeni bir kare oluşturulduğu anda, seçilen bir rakip taşı dışarı çıkarılır. Rakibin taş sayısını 3’e düşüren oyuncu oyunu kazanır.

PROBLEMİN TANIMI
Yukarıda tarif edilen Kare Kapan oyununun simüle edilmesini sağlayacak bir program geliştirilmesi istenmektedir.
Oyun alanı en az 3, en çok 7 yatay çizgiden ve yatay çizgi sayısından 1 fazla sayıda dikey çizgiden oluşmalıdır.
Oyun alanındaki yatay çizgiler sayma sayıları, dikey çizgiler büyük harfler (yalnız İngilizce harfler) ile temsil edilmelidir.

Oyunun başında, oyun alanındaki yatay çizgi sayısı [3-7] kullanıcıdan alınarak boş oyun alanı görüntülenmelidir. 
Örneğin 4 yatay, 5 dikey çizgiden oluşan bir oyun alanı başlangıçta aşağıdakine benzer şekilde görüntülenebilir:

![image](https://github.com/user-attachments/assets/af8154ad-6e3f-49ba-92fc-afd41dd7066c)

Oyuncular oyun alanına yerleştirmek istedikleri kendi taşının konumunu veya oyun dışına çıkarmak istedikleri rakip taşının konumunu, ilgili konumun bulunduğu 
yatay çizginin numarasını (örnekte [1-4]) ve dikey çizginin harfini (örnekte [A-E]) bitişik olarak (örneğin 2D) girmelidir.


Benzer şekilde oyuncular hareket ettirmek istedikleri kendi taşının şimdiki konumunu ve hedef konumunu, şimdiki konumun bitişik yatay çizgi numarası ve dikey çizgi
harfi ile hedef konumun bitişik yatay çizgi numarası ve dikey çizgi harfi arasında bir boşluk bırakarak (örneğin 3C 1C) girmelidir.

Oyun alanında değişikliğe yol açan her bir adımdan/hareketten sonra oyun alanı tekrar görüntülenmelidir. Örneğin örnekteki oyun alanı, 
oyunun herhangi bir aşamasında aşağıdakine benzer şekilde görüntülenebilir:

![image](https://github.com/user-attachments/assets/ecb161ec-3f6e-4b8f-bec4-9c25a09be996)

Oyun sonunda, kazanan oyuncunun hangi renk ile oynadığı ekrana yazdırılmalıdır.
