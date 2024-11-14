---
{"publish":true,"path":"1 anno/Programmazione e Laboratorio/Lezioni/Casting Inplicito.md","permalink":"/1 anno/Programmazione e Laboratorio/Lezioni/Casting Inplicito/","PassFrontmatter":true}
---


Ogni qual volta avviene un assegnamento tra 2 tipi diversi C++ svolge un casting (in C++ tutti i tipi sono compatibili) 
Esempio:  
```c++
int a=2; 
double b=3.14 
a=b;
```
in memoria `a=3` -> #Narrowing del dato (perdita di informazioni)