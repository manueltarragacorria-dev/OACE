# UNIDAD 3. ACTIVIDAD 1. EJERCICIOS CON DIRECTORIOS

## 1.- Crea un directorio llamado iso en tu unidad c:\. Sitúate en el directorio iso de tu unidad (que será la unidad C). Desde el directorio iso crea los directorios (1_eval, teoria, t1, practica, p1a, p1b) 

```
cd / -> mkdir iso -> cd iso -> mkdir 1_eval -> cd 1_eval -> mkdir teoria -> cd teoria -> mkdir t1 -> cd .. -> mkdir practica -> cd practica -> mkdir p1a -> cd p1a -> mkdir p1b
```

<img width="464" height="552" alt="imagen" src="https://github.com/user-attachments/assets/f6585aaf-32e2-4c35-8571-83b1d24fab8f" />


## 2.- Sitúate en el directorio p1b. Crea los directorios (3_eval, teoriaa, teoriab) utilizando trayectorias relativas.

```
md ..\..\..\..\3_eval\teoriaa ..\..\..\..\3_eval\teoriab
```

<img width="774" height="99" alt="imagen" src="https://github.com/user-attachments/assets/136bf72b-5b8b-4877-b67a-c2435274b5b2" />

## 3.- Sitúate en el directorio iso. Crea el directorio (2_eval).

```
cd C:\iso -> mkdir 2_eval
```

<img width="405" height="99" alt="imagen" src="https://github.com/user-attachments/assets/dc370e1d-f086-43da-ae6e-7e52a942bb0b" />

## 4.- Sitúate en el directorio 2_eval. Crea los directorios (prac1, prac2, prac3) con una única sentencia

```
cd 2_eval -> mkdir prac1 prac2 prac3
```

<img width="376" height="99" alt="imagen" src="https://github.com/user-attachments/assets/f9e6e586-8db2-47ba-9748-5d45322e0f20" />

## 5.- Sitúate en el directorio prac3. Crea los directorios (prac31, prac311) usando trayectorias relativas.

```
mkdir prac31 prac311
```

<img width="333" height="101" alt="imagen" src="https://github.com/user-attachments/assets/4ed1906b-1c36-4bf8-ada9-63e1f8045782" />

## 6.- Accede al directorio iso usando trayectoria absoluta con una única sentencia

```
cd C:\iso
```

<img width="238" height="101" alt="imagen" src="https://github.com/user-attachments/assets/233871cd-d149-4b23-8d58-20e97efb7b52" />

## 7.- Desde iso elimina los directorios (prac311, prac31,teoriab, teoriaa, t1, p1b, p1a) utilizando trayectorias absolutas.

```
rmdir C:\iso\2_eval\prac3\prac31 C:\iso\2_eval\prac3\prac311 -> rmdir C:\iso\3_eval\teoriaa C:\iso\3_eval\prac3\teriab -> rmdir C:\iso\1_eval\teoria\t1 C:\iso\1_eval\practica\p1a C:\iso\1_eval\practica\p1b
```

<img width="549" height="63" alt="imagen" src="https://github.com/user-attachments/assets/5fe1810d-8ccd-4621-8c9e-561c2b04878f" />

<img width="321" height="98" alt="imagen" src="https://github.com/user-attachments/assets/5d5efd47-9638-4b3c-9cd5-5bb4bf5f9bc8" />

<img width="549" height="129" alt="imagen" src="https://github.com/user-attachments/assets/0dbe1f71-7683-4ce1-aca7-9374e0d30896" />

## 8.- Accede al directorio 2_eval usando trayectoria relativa con una única sentencia.

```
cd 2_eval
```
<img width="136" height="98" alt="imagen" src="https://github.com/user-attachments/assets/6bb4bb96-173f-47b6-9cfc-e0963ae6dc6e" />

## 9.- Desde aquí cambia el nombre del directorio prac1 por el de prac4.

```
ren prac1 prac4
```

<img width="235" height="22" alt="imagen" src="https://github.com/user-attachments/assets/907881ad-e099-4d3d-95fe-ff85988de308" />


## 10.- Desde aquí sitúa el directorio prac4 dentro del directorio prac3.

```
move prac4 C\:iso\3_eval
```

<img width="327" height="79" alt="imagen" src="https://github.com/user-attachments/assets/288cb16f-ad79-4165-8442-e1a217c8e8e0" />

## 11.- Desde aquí elimina los directorios (1_eval, 3_eval

```
rmdir ..\1_eval ..\3_eval
```
<img width="343" height="93" alt="imagen" src="https://github.com/user-attachments/assets/98a250e5-d07f-49bb-9b3d-acb3c33b5078" />


