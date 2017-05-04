Journal For May Fourth 2017
==========================

---

>This is for the AP Java symposium

__*First Entry*__

Today I will be learning how Processing works and trying to create a sphere, I will also find an image for the background. 

__*Second Entry*__

Today I was able to create a 3D sphere, and make my window fullscreen and I downloaded bash so I can commit my `.pde` files directly onto github.

### Sample Code:

```Processing
  void settings(){
    //this piece of code replaces the defaut 'size()' function
    //but only when writtin in 'settings()' rather then 'setup()'
    fullScreen(P3D);
  }
  
  void setup(){
    //code is writtin in settings rather then here
  }
  
  void draw(){
    background(0);
    stroke(255,255,255);
    fill(255,255,255);
    ambientLight(255,255,255);
    sphere(100);
  }
```
