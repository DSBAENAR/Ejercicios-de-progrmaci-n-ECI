n=int(input(" Ingresa un número positivo que sea mayor que cero "))
while n<1:
    n=int(input(" Error el número ingresado no es mayor que cero, ingresa un número mayor que cero "))
cont=1
repin=1
veces=0
pos=0
valorsolicitado=0
while pos<n:
    cont2=0
    if cont==1:
        valorlim=1
    else:
        if valorlim==1:
            valorlim=2
        else:
            if veces<valorlim-1:
                valorlim=valorlim
                veces+=1
            else:
                valorlim+=1
                veces=0
    while cont2<valorlim:
        cont3=0
        while cont3<repin:
            pos+=1
            if (pos==n):
                valorsolicitado=cont
            cont3+=1
        cont2+=1
        cont+=1
    repin+=1
print(valorsolicitado)
