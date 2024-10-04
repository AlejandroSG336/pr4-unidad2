# pr4-unidad2 sepulveda gonzalez angel alejandro
# 2. Almacenar materias en una lista y desplegar en pantalla.

materias = ["Pensamiento matemático", "Español", "Inglés", "Química", "Civismo", 
"Francés"]  # Lista de materias

print("Materias del curso:")  # Mensaje inicial antes de mostrar las materias

for materia in materias:  # Recorro la lista de materias

    print(materia)  # Despliego en pantalla cada materia

# 3. Mensaje personalizado para cada materia.

for materia in materias:  # Recorro la lista de materias nuevamente

    print(f"Estoy cursando {materia}")  # Despliego un mensaje indicando que estoy cursando cada materia

# 4. Solicitar calificaciones para cada materia y desplegar resultados.
calificaciones = []  # Inicializo una lista vacía para almacenar las calificaciones

for materia in materias:  # Recorro la lista de materias

    calificacion = input(f"Ingrese la calificación para {materia}: ")  # Solicito 
    al usuario la calificación de cada materia
    
    calificaciones.append(calificacion)  # Agrego la calificación ingresada a la lista de calificaciones
    
    print(f"En {materia} has obtenido {calificacion}")  # Despliego el mensaje con la materia y la calificación correspondiente

![image](https://github.com/user-attachments/assets/cad9da4e-9b25-4071-8916-8c3d44cc5677)
![Uploading image.png…]()
