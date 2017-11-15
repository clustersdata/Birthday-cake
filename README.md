# Birthday-cake

Birthday cake

Description

7月17日是Mr.W的生日，ACM-THU为此要制作一个体积为Nπ的M层生日蛋糕，每层都是一个圆柱体。 
设从下往上数第i(1 <= i <= M)层蛋糕是半径为Ri, 高度为Hi的圆柱。当i < M时，要求Ri > Ri+1且Hi > Hi+1。 
由于要在蛋糕上抹奶油，为尽可能节约经费，我们希望蛋糕外表面（最下一层的下底面除外）的面积Q最小。 
令Q = Sπ 
请编程对给出的N和M，找出蛋糕的制作方案（适当的Ri和Hi的值），使S最小。 
（除Q外，以上所有数据皆为正整数） 
Input

有两行，第一行为N（N <= 10000），表示待制作的蛋糕的体积为Nπ；第二行为M(M <= 20)，表示蛋糕的层数为M。

Output

仅一行，是一个正整数S（若无解则S = 0）。

Sample Input

100
2

Sample Output

68

Hint

圆柱公式 
体积V = πR2H 
侧面积A' = 2πRH 
底面积A = πR2 
