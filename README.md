# Random-3D-Terrain\
Random terrain using noise (Built on pyEngine3D).\
Run terrain.py to generate the land.\
\
You can change the landmass distribution through the n1div variable in the terrain.py file\
\
Example of high n1div: <img width="955" alt="landdist70boulderdist5rockdist1" src="https://user-images.githubusercontent.com/99492215/171438283-830f040b-b872-478c-b127-37202bff82b7.png">\
Example of low n1div: <img width="953" alt="landdist20boulderdist5rockdist1" src="https://user-images.githubusercontent.com/99492215/171438463-faf473b2-0058-4c14-ada8-a8315074a2b3.png">\
n1div makes the terrain more contiguous the more high it is\
\
You can also change the boulder distribution through the n2div variable found under the same file\
\
Example of high n2div: <img width="953" alt="landdist20boulderdist40rockdist1" src="https://user-images.githubusercontent.com/99492215/171450393-7333f4cc-7972-45e2-9a91-a4fa01b1b5d2.png">\
Example of low n2div: <img width="953" alt="landdist20boulderdist5rockdist1" src="https://user-images.githubusercontent.com/99492215/171450604-2f8e23d0-f301-4fb2-b3dc-d89c9ac8e9bc.png">\
n2div makes the terrain more rough the higher it is\
\
n3div has a similar effect to n2div but more extreme\
Example of high n3div: <img width="953" alt="landdist20boulderdist5rockdist40" src="https://user-images.githubusercontent.com/99492215/171451420-2002aba3-9a0a-49a6-9a28-e6eb77f231a8.png">\
Example of low n3div: <img width="953" alt="landdist20boulderdist5rockdist1" src="https://user-images.githubusercontent.com/99492215/171451612-67dcb8e8-4d34-4607-9fef-52b60dca31da.png">
