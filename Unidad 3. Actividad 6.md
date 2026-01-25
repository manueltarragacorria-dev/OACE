# UNIDAD 3. ACTIVIDAD 6. EJERCICIOS CON FICHEROS. POWERSHELL.

## 1.- Situado en smm crea los directorios A, B, C y D. Utiliza trayectoria absoluta

```
New-Item -ItemType Directory SMM -> Set-Location SMM -> New-Item -ItemType Directory C:\SMM\A, C:\SMM\B, C:\SMM\C, C:\SMM\D
```

<img width="834" height="584" alt="image" src="https://github.com/user-attachments/assets/4b1962a9-52ed-483e-8bc2-ab27105c40a3" />

## 2.- Sitúate en D y desde allí crea A1, A2, A21, A22, A221 con una única sentencia utilizando trayectoria relativa

```
Set-Location D -> New-Item -ItemType Directory ..\A\A1, ..\A\A2, ..\A\A21, ..\A\A22, ..\A\A221
```

<img width="809" height="315" alt="image" src="https://github.com/user-attachments/assets/9236b7c9-6347-453a-bb4e-c733c04d2148" />


## 3.- Sitúate en A221 y desde allí crea B1, B11, B111, B112 con una única sentencia y utilizando trayectoria relativa.

```
Set-Location A221 -> New-Item -ItemType Directory ..\..\B\B1, ..\..\B\B1\B11, ..\..\B\B1\B11\B111, ..\..\B\B1\B11\B112
```

<img width="1049" height="586" alt="image" src="https://github.com/user-attachments/assets/25d7fef1-84b2-4cd1-aeae-502664d5d075" />



## 4.- Estando situado en A221, crea un fichero llamado líneas.txt en el directorio C que contenga el árbol de directorios dependiente del directorio A (incluyendo los subdirectorios).

```
Tree C:\SMM\A | Out-File C:\SMM\C\lineas.txt
```

<img width="603" height="51" alt="image" src="https://github.com/user-attachments/assets/46a3ed26-3a5f-42f3-87c7-b64bd2dab229" />


