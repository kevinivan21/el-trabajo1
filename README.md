# el-trabajo1
#defines la variable "nombre" y lo ejecutas con una pregunta
nombre = input("Ingresa tu nombre: ")
#leemos la variable 
print(nombre)
#defines la variable "apellido" y lo ejecutas con una pregunta
apellido = input("Ingresa tu primer apellido: ")
#leemos la variable
print(apellido)
#defines la variable "edad" y lo ejecutas con una pregunta
edad = input("Ingresa tu edad: ")
#leemos la variable
print(edad)
#hacemos que se ejecuten las variables y solo lena las primeras letras que tienen escritas por el usuario siendo [0] el numero del lugar que va a leer 
# y upper surve para que cualquier palabra escrita sea leida en mayusculas
inicial_nombre = nombre[0].upper()
inicial_apellido = apellido[0].upper()
# Utiliza el formato correcto para concatenar las letras en la CURP
curp = f"{inicial_apellido}{inicial_nombre}{edad}"
print("Tu CURP es:", curp)
