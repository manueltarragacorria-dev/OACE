# UNIDAD 3. ACTIVIDAD 2. EJERCICIOS CON FICHEROS

## 0.- Cambia el prompt a tu primera inicial del nombre y tu apellido.

```
prompt mtarraga $p^>
```
<img width="747" height="244" alt="imagen" src="https://github.com/user-attachments/assets/a85d6e02-5d4a-4253-a334-aa8a450aa47a" />

## 1.- Situado en smm crea los directorios A, B, C y D. Utiliza trayectoria absoluta.

```
mkdir C:\SMM\A C:\SMM\B C:\SMM\C C:\SMM\D
```
<img width="748" height="302" alt="imagen" src="https://github.com/user-attachments/assets/4f326207-b8b2-42e7-a9c5-7baa52b9cc2f" />

## 2.- Sitúate en D y desde allí crea A1, A2, A21, A22, A221 con una única sentencia utilizando trayectoria relativa.

```
cd D -> mkdir A1 A2 A21 A22 A221
```
<img width="744" height="121" alt="imagen" src="https://github.com/user-attachments/assets/2765159f-d432-4275-85a6-b57a0629dcad" />

## 3.- Sitúate en A221 y desde allí crea B1, B11, B111, B112 con una única sentencia y utilizando trayectoria relativa.

```
cd A221 mkdir B1 B11 B111 B112
```

<img width="742" height="119" alt="imagen" srcc="https://github.com/user-attachments/assets/f43ee3fd-e4e6-4f0a-ab1a-fbe<98f521064"/>

## 4.- Estando situado en A221, crea un fichero llamado líneas.txt en el directorio C que contenga el árbol de directorios dependiente del directorio A (incluyendo los subdirectorios).
<img width="770" height="106" alt="imagen" src="https://github.com/user-attachments/assets/c3187337-cd46-4a70-9214-95296eac6894" />

## 5.- Crea en D un fichero llamado Nombre.txt que contenga tu nombre y otro fichero llamado Apellido.txt que contenga tu primer apellido.

<img width="766" height="203" alt="imagen" src="https://github.com/user-attachments/assets/a7f6305a-093b-4b46-a69e-fd9dd2037f89" />

## 6.- Genera un fichero llamado union.txt en D que contenga el contenido de Nombre.txt y Apellido.txt

```
type Nombre.txt > union.txt -> type Apellido.txt >> union.txt
```

<img width="323" height="92" alt="imagen" src="https://github.com/user-attachments/assets/fa2aa141-273c-47d1-9d33-65d8795aee5c" />

## 7.- Mueve el fichero union.txt a A21.

```
move C:\SMM\D\union.txt C:\SMM\D\A21
```
<img width="372" height="70" alt="imagen" src="https://github.com/user-attachments/assets/11fd51e0-6275-4396-8e10-c688e2d9f364" />

### 8.- Mueve el directorio A2 dentro de C.

```
move C:\SMM\D\A2 C:\SMM\C
```

<img width="322" height="53" alt="imagen" src="https://github.com/user-attachments/assets/18eeea3c-6c2f-4e72-a4bf-957ed99acb74" />

### 9.- Cambia el nombre del fichero union.txt por el de nuevaunion.txt

```
ren union.txt nuevaunion.txt
```

<img width="336" height="23" alt="imagen" src="https://github.com/user-attachments/assets/6d64bbaf-4d55-46d3-9819-aa359c11be8a" />

### 10.- Copia el fichero Nombre.txt al directorio A

```
copy C:\SMM\D\Nombre.txt C:\SMM\A
```

<img width="385" height="74" alt="imagen" src="https://github.com/user-attachments/assets/b1440041-b4f9-41ab-87a6-8283b728f59d" />

### 11.- Elimina el directorio A (sin usar el parámetro /s).

```
del Nombre.txt -> cd .. ->   rd A
```

<img width="198" height="86" alt="imagen" src="https://github.com/user-attachments/assets/c635b3b7-022d-40c4-9181-b209de11fa2b" />

### 12.- Cambia el nombre del fichero Apellido.txt por el de miApellido.doc

```
ren C:\SMM\D\Apellido.txt miApellido.doc
```
<img width="386" height="34" alt="imagen" src="https://github.com/user-attachments/assets/cb4f9e0b-7c1b-4b3e-811b-156cd3039810" />

### 13.- Cambia el nombre del directorio C por el de nuevoC

```
ren C:\SMM\C nuevoC
```

<img width="220" height="34" alt="imagen" src="https://github.com/user-attachments/assets/04bdef6f-1137-4f5f-8c90-05eb3715eab0" />

### 14.- Copia el fichero lineas.txt a D con el nombre nlineasend.txt

```
copy C:\SMM\nuevoC\lineas.txt C:\SMM\D
```

<img width="368" height="48" alt="imagen" src="https://github.com/user-attachments/assets/dc6639ee-acd0-4f7d-aaf4-042d0307ce49" />

### 15.- Muestra el árbol de directorios (incluyendo ficheros) que depende del directorio smm.

```
tree /f
```

<img width="424" height="333" alt="imagen" src="https://github.com/user-attachments/assets/314d52ee-84e9-4351-9898-b9da3e26c638" />




