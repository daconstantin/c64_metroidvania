# c64_metroidvania

C64 game. Written in 6502 assembly.

sprites:  idle x 3    (3 sprites each) =9
          walk x 3    (2 sprites each, upper hi-res shared) =6
          run x 3     (3 sprites each) =9
          jump x 3    (3 sprites each) =9
          crouch x 2  (2 sprites each) =4
          attack x 15 (5 sprites each, lower hi-res shared) =75
          = 112 sprites * 64 bytes = 7kB
          + misc. sprites = 8kB
          * 2 directions = 16kB
 
enemy sprites:
          3-9 per enemy
          5 different enemies per map = 30 sprites
          + death animations x 20 = 50 sprites * 64 bytes = 3kB
          + 2 directions = 6kB
  
Charset * 2 = 4kB ?

Map_data = 8kB ?

Game logic = 4kB ?

Music & SFX = 20kB ?

TOTAL 58kB (too much...)

Stream more stuff to ram from datasette emulation / user port / expansion port




          
          
