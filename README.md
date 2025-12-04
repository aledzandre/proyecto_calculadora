TALLER: Git, Python y GitHub (por consola)
Presentado Por  Jhon Alexander Martinez
Objetivos
•	Usar los comandos básicos de Git desde la terminal.
•	Subir un proyecto a GitHub.
•	Actualizar el código y versionarlo correctamente.
Requisitos
•	Visual Studio Code instalado
•	Python 3 instalado
•	Git instalado
•	Cuenta en GitHub

ACTIVIDAD FINAL: Calculadora básica

1.	Crear una nueva carpeta e inicializa un repositorio de Git:  git init
2.	Crear el archivo calculadora.py en Visual Studio Code y escribe este código base:
 # calculadora.py
# Script básico para operaciones matemáticas
numero_1 = float(input("Primer número: "))
numero_2 = float(input("Segundo número: "))
operacion = input("Operación (+, -, *, /): ")
if operacion == '+':
print("Resultado:", numero_1 + numero_2)
elif operacion == '-':
print("Resultado:", numero_1 - numero_2)
elif operacion == '*':
print("Resultado:", numero_1 * numero_2)
elif operacion == '/':
if b != 0:
print("Resultado:", numero_1 / numero_2)
else:
print("Error: no se puede dividir por cero.")
else:
print("Operación no válida.")

3.	Guardar, hacer commit y subir a GitHub:
git add .
git commit -m "Primer commit: calculadora básica"
git remote add origin https://github.com/tuusuario/calculadora_basica.git
git push -u origin main

4.	Agregar mejoras y subir una segunda versión:
git add .
git commit -m "Explica la mejora que hiciste"
git push

5.	Entregar la URL del repositorio.

https://github.com/aledzandre/mi_primer_proyecto.git
https://github.com/aledzandre/proyecto_calculadora.git

