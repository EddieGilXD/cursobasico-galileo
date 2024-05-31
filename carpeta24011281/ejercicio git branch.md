### Ejercicio 1: Crear y cambiar entre ramas
1. Clona el repositorio de ejemplo:
   ```bash
   git clone https://github.com/desarrolladoresTH/BootCamp-FullStack.git
   cd BootCamp-FullStack
   
   Si quieres que se muestren todos los archivos del repo
   ls -a 
   ```
2. Crea una nueva rama llamada `feature/nueva-caracteristica`:
   ```bash
   git branch feature/nueva-caracteristica
   ```
3. Cambia a la nueva rama creada:
   ```bash
   git checkout feature/nueva-caracteristica
   ```
4. Realiza algunos cambios en cualquier archivo y luego haz commit de esos cambios en la nueva rama.
### Ejercicio 2: Fusionar una rama con la principal
1. Asegúrate de estar en la rama principal:
   ```bash
   git checkout main
   ```
2. Actualiza la rama principal con los cambios de la rama `feature/nueva-caracteristica`:
   ```bash
   git merge feature/nueva-caracteristica
   ```
3. Resuelve cualquier conflicto que pueda surgir durante la fusión, si es necesario.