# last-survive
Binary search project
  
  
 [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.
  
  
  
                                                  7  -> Dizinin ilk elemanı olan 7 root seçilir. 
                                                 /
                                                5    -> root'tan küçük olan sayılar root'un sağına, büyük olanları ise root'un sağına yazılır.
                                                 
                                                 
                                                 7
                                                /      
                                               5   
                                              /
                                             1       - > 1 rakamı 7'den küçüktür,5'ten de küçüktür. 5'in sağına yazılır.
                                                
                                                
                                                 7
                                                / \
                                               5   8   -> Dizideki sırada  8 vardır. 8 7'den büyük olduğu için 7'nin soluna yazılır.
                                              /
                                             1   
                                                  
                                                  
                                               7
                                             /   \ 
                                           5       8
                                         /          
                                        1 
                                         \
                                          3           -> Dizideki sırada 3 vardır. 3, 7'den küçüktür, 5'ten de küçüktür 5'in sağına yazılması gerekir ancak orada 0 bulunduğuiçin 0 rakamının soluna yazılır.
                                          
                                                      -> Dizideki tüm elemanlar sıralanana kadar adımlar tekrar eder.
                                                      
     
                                               7 
                                             /   \ 
                                           5       8
                                         /   \      \ 
                                        1      6      9 
                                       /  \    / 
                                     0    3  4
                                         /
                                        2               -> Binary search tree'ye göre sıralanması
                                        
    www.patika.dev                                    
                                        
                                        
                                        
