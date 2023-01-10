[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] - Binary-Search-Tree

- Yukarıdaki sayı dizisinin Binary Search tree'ye göre sıralanma aşamaları;


                  (7)
               (5)   (8)
             (1) (6)    (9)
           (0) (3)
             (2) (4)

root = 7'dir.

       -Aşamalar-

- 5, 7'den küçük olduğu için 7'nin soluna yazılır

- 1, 7'den ve 5'den küçük olduğu için en sola yazılır

- 8, 7'den büyük olduğu için sağ tarafa yazılır.

- 3, 7'den ve 5'den küçük ama 1'den büyük olduğu için 1'in sağ tarafına yazılır.

- 6, 7'den küçük 5'den büyük olduğunu için 5'in sağ tarafına yazılır.

- 0 en küçük olduğu için sol en alta yazılır.

- 9, 7'den ve 8'den büyük olduğu için 8'in sağına yazılır.

- 4, 7 ve 5'den küçük 1 ve 3'den büyük olduğu için 3'ün sağına yazılır.

- 2, 7 ve 5'den küçük 1'den büyük ve 3'den küçük olduğu için 3'ün sol tarafına yazılır.