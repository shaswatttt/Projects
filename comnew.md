# Projects
a=[[0 for i in range(5)] for j in range(5)]
for i in range(5):
    for j in range(5):
        a[i][j]=(input("place the hero, princess and villian and leave other space blank with - "))
test=a
for j in test:
    print(j)
for i in range(5):
    for j in range(5):
        if a[i][j]=="h":
           t=i
           u=j
           print(t,u)
        if a[i][j]=="p":
           f=i
           k=j
           print(f,k)
        if a[i][j]=="v":
           n=i
           x=j
           print(n,x)
v=t
z=u
           
if t==f and t==n:
    if t==0:
        print("down")
        t=t+1
        r=f-t
        d=k-u
        if d>0:
            print("right"*d)
        else:
            print("left"*-d)
        if r>0:
            print("down"*r)
        else:
            print("up"*-r)
    elif t==4:
        print("up")
        t=t-1
         r=f-t
        d=k-u
        if d>0:
            print("right"*d)
        else:
            print("left"*-d)
        if r>0:
            print("down"*r)
        else:
            print("up"*-r)
    else:
        print("up")
        t=t-1
        
        r=f-t
        d=k-u
        if d>0:
            print("right"*d)
        else:
            print("left"*-d)
        if r>0:
            print("down"*r)
        else:
            print("up"*-r)
            
elif u==k and u==x:
    if u==0:
        print("right")
        u=u+1
        r=f-t
        d=k-u
        if r>0:
            print("down"*r)
        else:
            print("up"*-r)      
        if d>0:
            print("right"*d)
        else:
            print("left"*-d)
    elif u==4:
         print("left")
         u=u-1
         r=f-t
         d=k-u
         if r>0:
            print("down"*r)
         else:
            print("up"*-r)      
         if d>0:
            print("right"*d)
         else:
            print("left"*-d)
    else:
        print("left")
        u=u-1
        r=f-t
        d=k-u
        if r>0:
            print("down"*r)
        else:
            print("up"*-r)      
        if d>0:
            print("right"*d)
        else:
            print("left"*-d)
if t==n and t!=f:
    if t==0:
        print("down")
        t=t+1
        r=f-t
        d=k-u
        if d>0:
            print("right"*d)
        else:
            print("left"*-d)
        if r>0:
            print("down"*r)
        else:
            print("up"*-r)
    elif t==4:
        print("up")
        t=t-1
        r=f-t
        d=k-u
        if d>0:
            print("right"*d)
        else:
            print("left"*-d)
        if r>0:
            print("down"*r)
        else:
            print("up"*-r)
    else:
        print("up22")
        t=t-1
        r=f-t
        d=k-u
        if d>0:
            print("right"*d)
        else:
            print("left"*-d)
        if r>0:
            print("down"*r)
        else:
            print("up"*-r)
        
elif u==x and u!=k:
    if u==0:
        print("right")
        u=u+1
        r=f-t
        d=k-u
        if r>0:
            print("down"*r)
        else:
            print("up"*-r)      
        if d>0:
            print("right"*d)
        else:
            print("left"*-d)
    elif u==4:
         print("left")
         u=u-1
         r=f-t
         d=k-u
         if r>0:
            print("down"*r)
         else:
            print("up"*-r)      
         if d>0:
            print("right"*d)
         else:
            print("left"*-d)
    else:
         print("left")
         u=u-1
         r=f-t
         d=k-u
         if r>0:
            print("down"*r)
         else:
            print("up"*-r)      
         if d>0:
            print("right"*d)
         else:
            print("left"*-d)
             
else:
    if v!=n:
        if z!=x:
            r=f-t
            d=k-u
            if r>0:
               print("down"*r)
            else:
               print("up"*-r)
            if d>0:
               print("right2"*d)
            else:
               print("left"*-d)
            
            
              
                 
        
    
    
         
            
  

