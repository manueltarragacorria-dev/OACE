# UNIDAD 3. ACTIVIDAD 7. CREACIÓN USUARIOS POWERSHELL

## Paso 1: Comprobar usuarios existentes

```
Get-LocalUser
```
<img width="997" height="242" alt="imagen" src="https://github.com/user-attachments/assets/bbee5920-7740-4c5c-a960-452e2a1337d2" />


## Paso 2: Crear una contraseña segura 

```
$Password = Read-Host "Introduce la contraseña" -AsSecureString
```

<img width="494" height="54" alt="imagen" src="https://github.com/user-attachments/assets/2a8c7d10-b39c-4de5-8745-d18f1df1ce40" />


## Paso 3: Crear el usuario local

```
New-LocalUser
```

<img width="480" height="169" alt="imagen" src="https://github.com/user-attachments/assets/70c1664b-c2ae-43e8-83b2-90fb1ac6a6f8" />



