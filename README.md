# Insertion Sort Projesi

# [22,27,16,2,18,6] -> Insertion Sort

## Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

## step0 = [22,27,16,2,18,6] (n)

## step1 = [2|,27,16,22,18,6] (n-1)

## step2 = [2,6|,16,22,18,27] (n-2)

## step3 = [2,6,16,18,22|,27] (1)

## Big-O gösterimini yazınız.

## Big-O : n+(n-1)+(n-2)...+1

## n^2*(n+1)/2 => Big-O : O(n^2)

## Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

## step4 = [2,6,16,18,22,27] == 18 : Average case

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## step0 = [7,3,5,8,2,9,4,15,6]

## step1 = [2|,3,5,8,7,9,4,15,6]

## step2 = [2,3,4|,8,7,9,5,15,6]

## step3 = [2,3,4,5|,7,9,8,15,6]

## step3 = [2,3,4,5,6|,9,8,15,7]
