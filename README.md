# Binary-Search-Tree-Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

#### Root:7
#### 5'i inceleyelim:
  5<7 sola yazılır                

             7 
            /
           5
    
#### 1'i inceleyelim:
  1<7, 7'nin soluna yazılır, 5 ile karşılaştırılır;
  
  1<5, 5'în soluna yazılır

             7
            / 
           5
          /
         1
         
#### 8'i inceleyelim:
  
  8>7, 7'nin sağına yazılır

               7
              / \
             5   8
            /
           1
          
#### 3'ü inceleyelim:
  3<7, 7'nin soluna yazılır, 5 ile karşılaştırılır;
  
  3<5, 5'în soluna yazılır, 1 ile karşılaşılır;
  
  3>1, 1'in sağına yazılır 

              7
             / \
            5   8
           /
          1
           \
            3
            
#### 6'yı inceleyelim:
  6<7, 7'nin soluna yazılır, 5 ile karşılaştırılır;

  6>5, 5'în sağına yazılır

               7
              / \
             5   8
            / \
           1   6
            \
             3
            
#### 0'ı inceleyelim:
  0<7, 7'nin soluna yazılır, 5 ile karşılaştırılır;

  0<5, 5'în soluna yazılır, 1 ile karşılaşılır;

  0<1, 1'in soluna yazılır

               7
              / \
             5   8
            / \
           1   6
          / \
         0   3
        
#### 9'u inceleyelim:
  9>7, 7'nin sağına yazılır, 8 ile karşılaşılır;
  
  9>8, 8'in sağına yazılır 

                7
               / \
              5   8
             / \   \
            1   6   9
           / \
          0   3
         
#### 4'ü inceleyelim:
  4<7, 7'nin soluna yazılır, 5 ile karşılaştırılır;
  
  4<5, 5'în soluna yazılır, 1 ile karşılaşılır;
  
  4>1, 1'in sağına yazılır, 3 ile karşılaştırılır;
  
  4>3, 3'ün sağına yazılır
         
                 7
                / \
               5    8
              / \    \
             1   6    9
            / \
           0   3
                \
                 4
                
#### 2'yi inceleyelim:
  2<7, 7'nin soluna yazılır, 5 ile karşılaştırılır;
  
  2<5, 5'în soluna yazılır, 1 ile karşılaşılır;
  
  2>1, 1'in sağına yazılır, 3 ile karşılaştırılır;
  
  2<3, 3'ün soluna yazılır

                   7
                  / \
                 5   8
                / \    \
               1   6    9
              / \
             0   3
                / \
               2   4
               

  [Patika.dev](https://app.patika.dev/)
