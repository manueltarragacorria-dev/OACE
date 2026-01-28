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

<img width="365" height="60" alt="imagen" src="https://github.com/user-attachments/assets/b79c98bb-b396-4263-a678-34e7aa36385d" />


