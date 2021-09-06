# Reloj
El codigo utilizado y ejecutado para la elaboración del reloj fue 

## Codigo
def setup():
    size(600,300)

def draw():
    background(89)
    

    s = map(second(),0,59,0,width)
    
    noStroke()
    fill(600,89,10)
    rect(0,0,s,150)
    stroke(321)
    
    
    m = map(minute(),0,59,0,width)

    noStroke()
    fill(600,0,100)
    rect(0,150,m,100)
    stroke(56)
    
    
    h = map(hour(),0,23,0,width)
    
    noStroke()
    fill(130,250,10)
    rect(0,250,h,50)
    stroke(89)
