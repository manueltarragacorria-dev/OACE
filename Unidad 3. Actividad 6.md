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

## 5.- Crea en D un fichero llamado Nombre.txt que contenga tu nombre y otro fichero llamado Apellido.txt que contenga tu primer apellido.

```
"Manuel" | Out-File C:\SMM\D\Nombre.txt -> "Tarraga" | Out-File C:\SMM\D\Apellido.txt
```

<img width="547" height="70" alt="image" src="https://github.com/user-attachments/assets/c0b8e9ff-4681-4fee-b509-429c735b2c00" />


# 6.- Genera un fichero llamado union.txt en D que contenga nombre y tu primer apellido. 7.- Mueve el fichero union.txt a A21.

```
Get-Content C:\SMM\D\Nombre.txt, C:\SMM\D\Apellido.txt | Out-File C:\SMM\D\union.txt
```

<img width="927" height="53" alt="image" src="https://github.com/user-attachments/assets/1c008f2f-1658-4ed8-98e4-331d395152e6" />

## 7.- Mueve el fichero union.txt a A21.

```
Move-Item C:\SMM\D\union.txt C:\SMM\A\A21
```

<img width="538" height="48" alt="image" src="https://github.com/user-attachments/assets/fa58dbcd-b8a9-4e8c-b0d8-30637f4cbaba" />

## 8.- Mueve el directorio A2 dentro de C.

```
Move-Item C:\SMM\A\A2 C:\SMM\C
```

<img width="437" height="48" alt="image" src="https://github.com/user-attachments/assets/06c67e5b-56b1-48de-bbbc-02642c76a3f5" />

## 9.- Cambia el nombre del fichero union.txt por el de nuevaunion.txt

```
Rename-Item C:\SMM\A\A21\union.txt C:\SMM\A\A21\nuevaunion.txt
```

<img width="725" height="49" alt="image" src="https://github.com/user-attachments/assets/46e6aee9-32d5-44f1-b222-db7943e4fae9" />

## 10.- Copia el fichero Nombre.txt al directorio A

```
Copy-Item C:\SMM\D\Nombre.txt C:\SMM\A
```

<img width="511" height="48" alt="image" src="https://github.com/user-attachments/assets/8801af88-0ef6-4234-bb89-c46e6f25f13c" />

## 11.- Elimina el directorio A (sin usar el parámetro /s).

```
Set-Location C:\SMM -> Remove-Item A\A1 -> Remove-Item A\A21\nuevaunion.txt -> Remove-Item A\A21 -> Remove-Item A\A22 -> Remove-Item A\A221 -> Remove-Item A
```


<img width="1873" height="603" alt="image" src="https://github.com/user-attachments/assets/f5c0eeb7-4541-48d7-92e0-0f87d0ddefd9" />







