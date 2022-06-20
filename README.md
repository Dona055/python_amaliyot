# python_amaliyot 
Funksiya 1 darsining amaliyoti 
def tug_yil_hisoblash(ismi,yoshi,yil=2022):
    '''Foyfalanuvhining yoshini hisoblash funksiya'''
    print(f"Foydalanuvchinig ismi:{ismi.title()}\nFoydalanuvchinig yoshi:{yil-yoshi}")
    1
def son_kvadrati(son):
    '''Sonning kvadratini chiqaruvchi funksiya'''
    print(f"Sonimiz kvadrati:{son**2}\nSonimizni kubi:{son**3}")
    
son_kvadrati(5)

def juft_toq_son(son):
    '''Sonining juft yoki toqligini aniqlovchi funksiya'''
    if son%2:
        print(f"{son} toq")
    else:
        print(f"{son} juft")
        
juft_toq_son(1)
juft_toq_son(125458)


def son_tengligi(x,y):
    '''sonning katta yooki kichigligini aniqlovchifunksiya'''
    if x<y:
        print(f"{x}<{y} ")
    elif x>y:
        print(f'{x}>{y}')
    else:
        print(f"{x}={y}")
son_tengligi(45, 55)
son_tengligi(-999, 215634)
son_tengligi(55**2, 4*8)        
son_tengligi(55, 55)




def x_ndaraja(x,n=2):
    '''X ning n darajasini aniqlovchi funksiya'''
    print(f"{x**n}")
    
x_ndaraja(5, )
x_ndaraja(x=103, )
x_ndaraja(5,7)


def qoldiqsiz_bolish(son):
    '''qoldiqsiz bolish'''
    for n in range(2,11):
        if not son%n:
            print(f"{son} {n} qoldiqsiz bolinadi")
    
qoldiqsiz_bolish(20)
