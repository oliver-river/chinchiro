#1と2が出るサイコロ
from vpython import*
import random
a=random.randint(1,2)
b=random.randint(1,2
                )
if a==1:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(0,0,0),axis=vector(0,0,1),radius=1,color=color.red)
# elif a==2:
else:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),color=color.black)
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),color=color.black)
    
#bに対応するサイコロ 
if b==1:
    
    box(pos=vector(0-1.1,0,0),length=1,width=0.1,hight=1,color=color.white)
    cylinder(pos=vector(0-1.1,0,0),axis=vector(0,0,0.1),radius=0.1,color=color.red)
    
else:    
    box(pos=vector(0-1.1,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(2.5-1.1,2.5,0),axis=vector(0,0,1),color=color.black)
    cylinder(pos=vector(-2.5-1.1,-2.5,0),axis=vector(0,0,1),color=color.black)
    
#bに対応するサイコロ    
