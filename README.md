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

print ("Cristian David Salas De La O 3-W") #Esta linea define el nombre del programador 
def ultima_palabra(s): #Esta linea define la funcion

    palabras = s.strip().split() #Esta linea define como saber cuantas palabras teine 

    if palabras: #Esta linea dice que hacer 
        return len(palabras[-1]) #Esta linea concluye la efecucion
    return 0 #Esta linea concluye la ejecucion

texto = input("Ingresa un texto ") #Esta linea define el texto
print("La longitud de la ultima palabra es:", ultima_palabra(texto)) #Esta linea dice el resultado

![image](https://github.com/user-attachments/assets/d3fa79a0-f29a-4f56-b219-d36ecfcecfcd)


![image](https://github.com/user-attachments/assets/e12ffb75-7372-46ce-9351-cdbd59fb00e5)
print ("Cristian David Salas De La O 3-W") #Esta linea define el nombre del programador 
def mayor_de_tres(): #Esta linea define la funcion 
    num1 = float(input("Ingresa el primer numero: ")) #Esta linea solicita el primer numero 
    num2 = float(input("Ingresa el segundo numero: "))#Esta linea solicita el segundo numero 
    num3 = float(input("Ingresa el tercer numero: ")) #Esta linea solicita el tercer numero 
    return max(num1, num2, num3) #Esta linea cocluye parte de la funcion 

resultado = mayor_de_tres() #Esta linea define el resultadoo
print("El mayor de los tres numeros es:", resultado) #Esta linea muestra el resultado 
![image](https://github.com/user-attachments/assets/ec9d16a8-2af7-48bc-be53-128681d905a5)
![image](https://github.com/user-attachments/assets/99e1e05e-d5d3-42d2-9bb7-5d34469e6ffc)
def sum(numbers): #esta linea define la funcion 
    total = 0 #esta linea define el total 
    for number in numbers: #esta linea pone el valor de numeros 
        total += number #esta linea define el total 
    return total #esta linea concluye parte de la funcion 

def multip(numbers): #esta linea define la funcion 
    product = 1#esta linea define el producto 
    for number in numbers: #esta linea pone el valor de los numeros 
        product *= number #esta linea define el producto 
    return product #esta linea concluye parte de la funcion 

input_values = input("Ingrese los numeros separados por comas: ") #esta linea solicita los numeros
numbers = [int(x) for x in input_values.split(',')] #esta linea procesa los valores

print("La suma es:", sum(numbers)) #esta linea muestra el resultado 
print("El producto es:", multip(numbers)) #esta linea muestra el resultado 
![image](https://github.com/user-attachments/assets/33867b51-5293-43ed-a917-ca5ffc65adaf)
![image](https://github.com/user-attachments/assets/de762201-3536-4acb-b15a-e51e422b3e32)

print ("Cristian David Salas De La O 3-W") #Esta linea define el nombre del programdor 
def es_vocal(caracter): #Esta linea define la funcion 

    vocales = 'aeiouAEIOU' #Esta linea define la vocales
    return caracter in vocales #Esta linea concluye la funcion 

caracter = input("Ingrese un carácter: ") #Esta linea solicita el caracter

if len(caracter) == 1: #Esta linea define el caracter

    if es_vocal(caracter): #Esta linea define el if de la vocal
        print("Es una vocal.") #Esta linea muestra que es una vocal
    else: #Esta linea dice que hacer si no se cumpla las peticiones 
        print("No es una vocal.") #Esta linea meustra que no es una vocal
else: #Esta linea muestra que hacer si no se cumplen con las peticiones 
    print("Por favor, ingrese solo un carácter.") #Esta linea muestra que no es solo un caracter
![image](https://github.com/user-attachments/assets/5f8cb707-4c53-4967-87de-c0b647a48697)
![image](https://github.com/user-attachments/assets/e74e73db-a2b6-4112-943e-a4d998543197)




