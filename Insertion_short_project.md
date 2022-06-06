# Insertion-Sort-Projesi
    [22,27,16,2,18,6] 
# 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    1-[22,27,16,2,18,6]                        
    
	2-[22,16,27,2,18,6] > [16,22,27,2,8,16]   
		
	3-[16,22,2,27,18,6] > [16,2,22,27,18,6] > [2,16,22,27,18,6]
    
    4-[2,16,22,27,18,6] > [2,16,22,18,27,6] > [2,16,18,22,27,6] 
	
  	5-[2,16,18,22,6,27] > [2,16,18,6,22,27] > [2,16,6,18,22,27] > [2,6,16,18,22,27]
   
		
1.Adım: İlk eleman olan 22 sayısı ondan sonra gelen 27 sayısından küçük olduğu için herhangi bir değişiklik olmaz. 	

2.Adım: İkinci eleman olan 27 sayısı 16'dan büyük olduğu için yer değiştirirler. 22 sayısı da 16'dan büyük olduğu için bir daha yer değiştirme işlemi yapılır.

3.Adım: Dördüncü eleman olan 2 sayısı 27'den küçük olduğu için yer değiştirilir. 16 ve 22 sayılarından da küçük olduğu için dizinin en başına atılır.

4:Adım: Beşinci eleman olan 18 sayısı 27 ve 22 sayılarından küçük olduğu için dizinin üçüncü sırasına yerleştirilir.

5:Adım:Son eleman olan 6 sayısı 27,22,18 ve 16 sayılarından küçük olduğu için dizinin ikinci sırasına yerleştirilir.

# 2-Big-O gösterimini yazınız.
	O(n²)

# 3-Time Complexity;

	Average Case: Dizinin normal dağılımda olması durumudur.

	Worst Case: Dizinin tam tersi sırada olması durumudur.

	Best Case: Dizinin sıralı olması durumudur.

# 4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
	Dizi sıralandıktan sonra son  18 sayısı dizinin ortasında olduğu için Average Case kapsamına girer.
	
	
# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
	1-[7,3,5,8,2,9,4,15,6]

	2-[7,3,5,8,2,9,4,15,6]

	3-[3,7,5,8,2,9,4,15,6]

	4-[3,5,7,8,2,9,4,15,6]


	
