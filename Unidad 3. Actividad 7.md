# UNIDAD 3. ACTIVIDAD 7. CREACIÓN USUARIOS POWERSHELL

## ACTIVIDAD 1 

### Paso 1: Comprobar usuarios existentes

```
Get-LocalUser
```
<img width="997" height="242" alt="imagen" src="https://github.com/user-attachments/assets/bbee5920-7740-4c5c-a960-452e2a1337d2" />


### Paso 2: Crear una contraseña segura 

```
$Password = Read-Host "Introduce la contraseña" -AsSecureString
```

<img width="494" height="54" alt="imagen" src="https://github.com/user-attachments/assets/2a8c7d10-b39c-4de5-8745-d18f1df1ce40" />


### Paso 3: Crear el usuario local

```
New-LocalUser
```

<img width="480" height="169" alt="imagen" src="https://github.com/user-attachments/assets/70c1664b-c2ae-43e8-83b2-90fb1ac6a6f8" />

### Paso 4: Añadir el usuario a un grupo

```
Add-LocalGroupMember -Group "Usuarios" -Member "usuario_ps"
```

<img width="480" height="39" alt="imagen" src="https://github.com/user-attachments/assets/c26b8cf1-aa4c-4540-b22c-b9a725dc5bae" />

### Paso 5: Verificar la creación del usuario

```
Get-LocalUser -Name "usuario_ps"
```

<img width="285" height="98" alt="imagen" src="https://github.com/user-attachments/assets/472a821a-92a2-4994-962c-5b76794abd64" />

## ACTIVIDAD 2

### PARTE 1: CREAR EL ARCHIVO CSV CON LOS USUARIOS
#### 1. Abre el Bloc de notas
#### 2. Escribe el siguiente contenido:

<img width="482" height="115" alt="imagen" src="https://github.com/user-attachments/assets/03805abd-a049-42ec-a285-04075959d080" />





















