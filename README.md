print ("Cristian David Salas De La O 3'W") #Esta linea muestra el nombre del progrmador
def saludo(): #Esta linea define la funcion del saludo
    print("Hey amigos!") #Esta linea define lo que se va mostrar de la funcion 

for _ in range(5): #Esta funcion define cuantas veces se mostrara la funcion, esto se puede cambiar
    saludo() #Esta linea define el final de la funcion
![image](https://github.com/user-attachments/assets/bbb58bfc-1e6e-4a80-8bbf-aeef7a1832a8)
![image](https://github.com/user-attachments/assets/edc358f9-a994-407c-8b96-743f0f55700b)
print ("Cristian David Salas De La o 3-W") #Esta linea define el nombre del programador
def saludar(nombre): #esta linea define la funcion 
    return f"¡Hola {nombre}!" #esta linea concluye la funcion

nombre = input("Introduce tu nombre: ") #esta linea solicita que el usuario ingrese su nombre 

print(saludar(nombre)) #Esta linea muestra el saludo y tu nombre
![image](https://github.com/user-attachments/assets/709bc3c0-7dee-46f8-ac80-0be21b339858)
![image](https://github.com/user-attachments/assets/3b9f3822-cb41-417c-86e1-f63b7e4b98de)
print ("Cristian David Salas De La O 3-W") #Esta linea define le nombre del programador
def calcular_total_factura(cantidad_sin_iva, porcentaje_iva): #Esta linea define la funcion 
    iva = cantidad_sin_iva * (porcentaje_iva / 100) #Esta linea define como sacar el iva
    total = cantidad_sin_iva + iva #Esta linea define el total 
    return total #Esta linea cocluye la funcion 

cantidad_sin_iva = float(input("Ingrese la cantidad sin IVA: ")) #Esta linea solicita la cantidad sin iva
porcentaje_iva = float(input("Ingrese el porcentaje de IVA: ")) #Esta linea solicita el porcentaje del iva

total_factura = calcular_total_factura(cantidad_sin_iva, porcentaje_iva) #Esta linea muestra el total de la factura

print(f"El total de la factura incluyendo IVA, es: {total_factura:.2f}") #Esta linea muestra el resultado 
![image](https://github.com/user-attachments/assets/3df5e597-7138-47e9-b894-cc528347ed49)
![image](https://github.com/user-attachments/assets/b2f7868b-94bd-47ce-a2e4-8549891da1a6)
print ("Cristian David Salas De La O 3-W") #Esta linea define el nombre del programador 
import math #Esta linea importa mas funciones de suma

def area_circulo(radio): #Esta linea calcula el area del circulo en la funcion 

    return math.pi * (radio ** 2) #Esta linea conclute la funcion

def volumen_cilindro(radio, altura): #Esta linea define la funcio 

    area_base = area_circulo(radio) #Esta linea calcula el area 
    return area_base * altura #Esta linea concluye la funcion 

radio = float(input("Ingrese el radio del circulo: ")) #Esta linea solicita el radio 
altura = float(input("Ingrese la altura del cilindro: "))#Esta linea solicita la altura 

area = area_circulo(radio) #Esta linea saca el area
print(f"El area del circulo es: {area:.2f}") #Esta linea muestra el area

volumen = volumen_cilindro(radio, altura) #Esta linea saca el volumen
print(f"El volumen del cilindro es: {volumen:.2f}") #Esta linea nuestra el volumen
![image](https://github.com/user-attachments/assets/cf0cf642-e0bf-4789-b5f5-0757c3bd0151)
![image](https://github.com/user-attachments/assets/046bd085-eb1b-468d-8d0c-55741825d177)
print ("Cristian David Salas De La O 3-W") #Esta linea define el nombre del programador
def es_email_valido(email): #Esta linea define la funcion 

    return '@' in email #Esta linea concluye la funcion 

email = input("Ingrese una direccion de email: ") #Esta linea solicita el email

if es_email_valido(email): #Esta linea sala el proceso de el resultado
    print("La direccion de email es valida.") #Esta linea muestra que se cumple la peticion 
else: #Esta linea  define que hacer si no se cumple la condiccion
    print("La direccion de email no es valida.") #Esta linea  avisa que no es correcto el email
![image](https://github.com/user-attachments/assets/481d2c86-f50e-46fe-a36f-dc387f52ef3a)
![image](https://github.com/user-attachments/assets/8126aee5-c046-4d4d-b70f-7b077e1786a2)




