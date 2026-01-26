# UNIDAD 3. ACTIVIDAD 5. EJERCICIOS CON DIRECTORIOS. POWERSHEL

## 1.- Crea un directorio llamado iso en tu unidad c:. Sitúate en el directorio iso de tu unidad (que será la unidad C). Desde el directorio iso crea los directorios (1_eval, teoria, t1, practica, p1a, p1b) utilizando trayectorias absolutas.

```
New-Item -ItemType Directory iso -> New-Item -ItemType Directory C:\iso\1_eval\teoria\t1, C:\iso\1_eval\practica\p1a\p1b
```

<img width="472" height="168" alt="imagen" src="https://github.com/user-attachments/assets/58cc2093-1d88-4b7c-867c-b329c3354a4b" />
<img width="675" height="284" alt="imagen" src="https://github.com/user-attachments/assets/7873a171-bab8-4906-80cf-a3c226fc293e" />

## 2.- Sitúate en el directorio p1b. Crea los directorios (3_eval, teoriaa, teoriab) utilizando trayectorias relativas.

```
Set-Location 1_eval\practica\p1a\p1b -> New-Item -ItemType Directory ..\..\..\..\3_eval\teoriaa, ..\..\..\..\3_eval\teoriab
```
<img width="833" height="195" alt="imagen" src="https://github.com/user-attachments/assets/787726b6-78a8-4ae0-99e4-14555eee7185" />

## 3.- Sitúate en el directorio iso. Crea el directorio (2_eval)

```
Set-Location ..\..\..\..\ -> New-Item -ItemType Directory C:\iso\2_eval
```

<img width="437" height="175" alt="imagen" src="https://github.com/user-attachments/assets/c2f452cf-449b-48e1-8f49-34916934c6a9" />

## 4.- Sitúate en el directorio 2_eval. Crea los directorios (prac1, prac2, prac3) con una única sentencia.

```
Set-Location 2_eval -> New-Item -ItemType Directory prac1, prac2, prac3
```

<img width="470" height="204" alt="imagen" src="https://github.com/user-attachments/assets/92df5a32-2ed3-4307-bf27-289c25c0c698" />

## 5.- Sitúate en el directorio prac3. Crea los directorios (prac31, prac311) usando trayectorias relativas.

```
Set-Location prac3 -> New-Item -ItemType Directory prac31\prac311
```

<img width="476" height="179" alt="imagen" src="https://github.com/user-attachments/assets/ec45dba6-8c95-418d-9524-b7e0add8a95b" />

















