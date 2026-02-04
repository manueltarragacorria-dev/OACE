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

### PARTE 2: CREAR EL SCRIPT DE POWERSHELL

#### 1. Abre el Bloc de notas o VS Code
#### Escribe el siguiente Script: 

<img width="713" height="624" alt="imagen" src="https://github.com/user-attachments/assets/f7bdc094-50c2-49f9-bc42-4927f01f0296" />

### PARTE 3: EJECUTAR EL SCRIPT

#### Paso 1: Permitir ejecución de scripts (si es necesario)
```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

<img width="991" height="120" alt="imagen" src="https://github.com/user-attachments/assets/44dbab53-fb0e-457e-bf4e-8d91d54e9d5e" />

#### Paso 2: Ejecutar el script 

```
Set-Location C:\Scripts -> .\crear_usuarios.ps1
```

<img width="369" height="108" alt="imagen" src="https://github.com/user-attachments/assets/4cbfbea2-2418-45d0-8893-2f294e214080" />


<img width="990" height="176" alt="imagen" src="https://github.com/user-attachments/assets/f73a2932-826c-4b0b-b349-d1cac28e416a" />
















