q=2
w=1000
o=1
p=1
l=1
def setup():
    size(1200,1000)
    
def draw():
    background(0)
    global q,w,o,p,l
    push()
    img = loadImage("8.png")
    image(img,500,500,300,300)
    pop()
    push()
    img = loadImage("TARHUN.jpg")
    image(img,560,620,60,60)
    pop()
    if mousePressed:
        if mouseButton == LEFT:
            fgf = loadImage("PELIMEN.jpg")
            image(fgf,120,120)
        img = loadImage("PELIMEN.jpg")
        image(img,random(0,1200),q,50,50) 
        q+=10
        img = loadImage("PELIMEN.jpg")
        image(img,random(0,1200),q,50,50) 
        q+=10
        img = loadImage("PELIMEN.jpg")
        image(img,random(0,1200),q,50,50) 
        q+=10
        img = loadImage("PELIMEN.jpg")
        image(img,random(0,1200),q,50,50) 
        q+=10
        img = loadImage("PELIMEN.jpg")
        image(img,random(0,1200),q,50,50) 
        q+=10
        img = loadImage("PELIMEN.jpg")
        image(img,random(0,1200),q,50,50) 
        q+=10
        img = loadImage("PELIMEN.jpg")
        image(img,random(0,1200),q,50,50) 
        q+=10
        img = loadImage("PELIMEN.jpg")
        image(img,random(0,1200),q,50,50) 
        q+=10
        img = loadImage("PELIMEN.jpg")
        image(img,random(0,1200),q,50,50)
        
         
        q+=10
        q= q + 20
        if q >= 1000:
            q=1
        
            
    
            if mouseButton == RIGHT:
                bimg = loadImage("buter.jpg")
                image(bimg,random(0,1200),q,50,50) 
                q+=10
                bimg = loadImage("buter.jpg")
                image(bimg,random(0,1200),q,50,50) 
                q+=10
                bimg = loadImage("buter.jpg")
                image(bimg,random(0,1200),q,50,50) 
                q+=10
                bimg = loadImage("buter.jpg")
                image(bimg,random(0,1200),q,50,50) 
                q+=10
                bimg = loadImage("buter.jpg")
                image(bimg,random(0,1200),q,50,50) 
                q+=10
                bimg = loadImage("buter.jpg")
                image(bimg,random(0,1200),q,50,50) 
                q+=10
                bimg = loadImage("buter.jpg")
                image(bimg,random(0,1200),q,50,50) 
                q+=10
                bimg = loadImage("buter.jpg")
                image(bimg,random(0,1200),q,50,50) 
                q+=10
                q= q + 20
                if q >= 1000:
                    q=1
                
                
                    if mouseButton == RIGHT:
                        simg = loadImage("tarhuun.jpeg")
                        image(simg,random(0,1200),q,50,50) 
                        q+=10
                        simg = loadImage("tarhuun.jpeg")
                        image(simg,random(0,1200),q,50,50) 
                        q+=10
                        simg = loadImage("tarhuun.jpeg")
                        image(simg,random(0,1200),q,50,50) 
                        q+=10
                        simg = loadImage("tarhuun.jpeg")
                        image(simg,random(0,1200),q,50,50) 
                        q+=10
                        simg = loadImage("tarhuun.jpeg")
                        image(simg,random(0,1200),q,50,50) 
                        q+=10
                        simg = loadImage("tarhuun.jpeg")
                        image(simg,random(0,1200),q,50,50) 
                        q+=10
                        simg = loadImage("tarhuun.jpeg")
                        image(simg,random(0,1200),q,50,50) 
                        q+=10
                        simg = loadImage("tarhuun.jpeg")
                        image(simg,random(0,1200),q,50,50) 
                        q+=10
                        q= q + 20
                        if q >= 1000:
                            q=1
                    
            
