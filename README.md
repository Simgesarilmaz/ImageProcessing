# ImageProcessing
1.Normalizasyon ile standardizasyon arasındaki farklar.
Normalizasyon: Verileri belirli bir aralığa (genellikle 0 ile 1 arasına) ölçeklemek amacıyla kullanılır. Bu, verilerin orijinal dağılımını korumak istediğinizde tercih edilir.
Standardizasyon: Verileri ortalama değeri 0, standart sapması 1 olacak şekilde dönüştürmeyi amaçlar. Bu, verilerin dağılımını merkezileştirir ve standart sapmayı birim yapar.


Normalizasyon: Genellikle veri noktasını minimum ve maksimum değerlere göre normalize etmek için kullanılan formül, (x - min) / (max - min) şeklindedir.
Standardizasyon: Veri noktasını ortalama ve standart sapmaya göre standardize etmek için kullanılan formül, (x - mean) / std şeklindedir.


Normalizasyon: Verilerin dağılımını sıkıştırmaz ve orijinal veri aralığını korur.
Standardizasyon: Verilerin dağılımını merkezileştirir ve standart sapma biriminde ifade eder.


Normalizasyon: Aykırı değerlere karşı daha duyarlıdır, çünkü minimum ve maksimum değerlere bağlıdır.
Standardizasyon: Aykırı değerlere daha dayanıklıdır, çünkü ortalama ve standart sapma kullanılır.
2.Bit plane slicing
Bit-plane slicing, görüntü işleme alanında kullanılan bir tekniktir ve bir görüntünün her pikselinin biner tabanındaki değerini, yani her pikselin bitlerini ayrı ayrı incelemek ve işlemek anlamına gelir. Bu işlem, görüntünün farklı bit düzeylerindeki bilgileri analiz etmek, görselleştirmek veya işlemek için kullanılır. Her bir bit düzeyi, görüntünün belirli bir detay seviyesini temsil eder.
