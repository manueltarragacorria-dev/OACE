# UNIDAD 3. ACTIVIDAD 6. EJERCICIOS CON FICHEROS. POWERSHELL.

## 1.- Situado en smm crea los directorios A, B, C y D. Utiliza trayectoria absoluta

```
New-Item -ItemType Directory SMM -> Set-Location SMM -> New-Item -ItemType Directory C:\SMM\A, C:\SMM\B, C:\SMM\C, C:\SMM\D
```

<img width="834" height="584" alt="image" src="https://github.com/user-attachments/assets/4b1962a9-52ed-483e-8bc2-ab27105c40a3" />

## 2.- Sitúate en D y desde allí crea A1, A2, A21, A22, A221 con una única sentencia utilizando trayectoria relativa

```
Set-Location D -> New-Item -ItemType Directory A1, A2, A21, A22, A221
```

<img width="600" height="311" alt="image" src="https://github.com/user-attachments/assets/1a9b73d9-b03c-4784-b0b3-6d3c14b3bcc3" />
