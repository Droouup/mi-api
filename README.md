# Mi API REST de Usuarios
## Instalación
```
# Inicializa el repositorio local
git init

# Conecta el remoto (tu repo en GitHub)
git remote add origin https://github.com/Droouup/mi-api.git

# Prepara todos los archivos para el commit
git add .

# Crea el primer commit
git commit -m "Primer commit"

# Renombra la rama principal a main
git branch -M main

# Sube al remoto
git push -u origin main

```
## Ejecución
```
node index.js
```
## Autenticación
Todas las peticiones requieren el header:
```
<img width="1918" height="1007" alt="image" src="https://github.com/user-attachments/assets/adbfa02f-05e0-4c1a-93f6-d1ab0bd75353" />
<img width="1916" height="1021" alt="image" src="https://github.com/user-attachments/assets/bbe952bd-7b83-4f00-b01a-e166fea1ecc9" />
<img width="1917" height="1023" alt="image" src="https://github.com/user-attachments/assets/016f9a65-59f9-458d-bf9d-62f42decbd00" />
<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/29fdd07d-d504-4bb9-a0e1-c31760104738" />
<img width="1917" height="1018" alt="image" src="https://github.com/user-attachments/assets/01aae8b6-1229-4d4d-b3a3-c28d457db412" />
<img width="1915" height="1020" alt="image" src="https://github.com/user-attachments/assets/e4f851ac-0b90-4e56-99ea-5dc45f8d8f48" />
<img width="1915" height="1018" alt="image" src="https://github.com/user-attachments/assets/b11caf69-b5a0-4cb8-9893-cef312ea7482" />
<img width="1918" height="1021" alt="image" src="https://github.com/user-attachments/assets/63cd1c40-514e-44f6-a391-2f907274e280" />


```
## Endpoints
| Método | Ruta | Descripción |
|---------|-------------------|---------------------------|
| GET | /usuarios | Listar todos |
| GET | /usuarios/:id | Obtener uno por ID |
| POST | /usuarios | Crear usuario |
| PUT | /usuarios/:id | Actualizar usuario |
| DELETE | /usuarios/:id | Eliminar usuario |
| GET | /usuarios?rol=X | Filtrar por rol |
