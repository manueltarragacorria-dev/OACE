# UNIDAD 3. ACTIVIDAD 5. EJERCICIOS CON DIRECTORIOS. POWERSHEL

### 1.- Crea un directorio llamado iso en tu unidad c:. Sitúate en el directorio iso de tu unidad (que será la unidad C). Desde el directorio iso crea los directorios (1_eval, teoria, t1, practica, p1a, p1b) utilizando trayectorias absolutas.

```
New-Item -ItemType Directory iso -> New-Item -ItemType Directory C:\iso\1_eval\teoria\t1, C:\iso\1_eval\practica\p1a\p1b
```

<img width="472" height="168" alt="imagen" src="https://github.com/user-attachments/assets/58cc2093-1d88-4b7c-867c-b329c3354a4b" />
<img width="675" height="284" alt="imagen" src="https://github.com/user-attachments/assets/7873a171-bab8-4906-80cf-a3c226fc293e" />

### 2.- Sitúate en el directorio p1b. Crea los directorios (3_eval, teoriaa, teoriab) utilizando trayectorias relativas.

```
Set-Location 1_eval\practica\p1a\p1b -> New-Item -ItemType Directory ..\..\..\..\3_eval\teoriaa, ..\..\..\..\3_eval\teoriab
```
<img width="833" height="195" alt="imagen" src="https://github.com/user-attachments/assets/787726b6-78a8-4ae0-99e4-14555eee7185" />

### 3.- Sitúate en el directorio iso. Crea el directorio (2_eval)

```
Set-Location ..\..\..\..\ -> New-Item -ItemType Directory C:\iso\2_eval
```

<img width="437" height="175" alt="imagen" src="https://github.com/user-attachments/assets/c2f452cf-449b-48e1-8f49-34916934c6a9" />

### 4.- Sitúate en el directorio 2_eval. Crea los directorios (prac1, prac2, prac3) con una única sentencia.

```
Set-Location 2_eval -> New-Item -ItemType Directory prac1, prac2, prac3
```

<img width="470" height="204" alt="imagen" src="https://github.com/user-attachments/assets/92df5a32-2ed3-4307-bf27-289c25c0c698" />

### 5.- Sitúate en el directorio prac3. Crea los directorios (prac31, prac311) usando trayectorias relativas.

```
Set-Location prac3 -> New-Item -ItemType Directory prac31\prac311
```

<img width="476" height="179" alt="imagen" src="https://github.com/user-attachments/assets/ec45dba6-8c95-418d-9524-b7e0add8a95b" />

### 6.- Accede al directorio iso usando trayectoria absoluta con una única sentencia.

```
Set-Location ..\..\
```

<img width="319" height="58" alt="imagen" src="https://github.com/user-attachments/assets/26b5acfb-db79-4ecc-a05e-be87f964ce63" />

### 7.- Desde iso elimina los directorios (prac311, prac31,teoriab, teoriaa, t1, p1b, p1a) utilizando trayectorias absolutas.

```
Remove-Item C:\iso\2_eval\prac3\prac31\prac311, C:\iso\2_eval\prac3\prac31, C:\iso\3_eval\teoriab, C:\iso\3_eval\teoriaa, C:\iso\1_eval\teoria\t1, C:\iso\1_eval\practica\p1a\p1b, C:\iso\1_eval\practica\p1a
```


<img width="1005" height="53" alt="imagen" src="https://github.com/user-attachments/assets/40ee17a6-a05a-42b6-acc2-923409f61d8a" />

### 8.- Accede al directorio 2_eval usando trayectoria relativa con una única sentencia.

```
Set-Location 2_eval
```

<img width="223" height="59" alt="imagen" src="https://github.com/user-attachments/assets/bc8bd487-a952-4553-9341-fef6dc9ff443" />

### 9.- Desde aquí cambia el nombre del directorio prac1 por el de prac4.

```
rename-Item prac1 prac4
```

<img width="299" height="59" alt="imagen" src="https://github.com/user-attachments/assets/ce959a5f-cf80-479e-a875-b409421767f0" />

### 10.- Desde aquí sitúa el directorio prac4 dentro del directorio prac3.

```
Move-Item prac4 prac3
```

<img width="380" height="136" alt="imagen" src="https://github.com/user-attachments/assets/1ee25ee5-97bc-4537-8a42-075dbc8e59c7" />

### 11.- Desde aquí elimina los directorios (1_eval, 3_eval)

```
Remove-Item ..\1_eval, ..\3_eval -Recurse
```

<img width="419" height="36" alt="imagen" src="https://github.com/user-attachments/assets/65be7edb-ff15-4886-aae7-4f2020c3499d" />

### 12.- Ejecuta la orden para visualizar el árbol de directorios y subdirectorios dependientes del directorio iso

```
Tree
```

<img width="378" height="153" alt="imagen" src="https://github.com/user-attachments/assets/1ef894a6-4373-42c0-976d-999f6df7878a" />

### 13.- Accede directamente a la raíz (a la unidad en la que te encuentras)

```
Set-Location /
```

<img width="232" height="60" alt="imagen" src="https://github.com/user-attachments/assets/9cdd1a62-624d-4cdb-837e-4c776368b020" />

## Actividad 2. Crea el siguiente árbol de directorios siguiendo las instrucciones paso a paso. En cada uno de los pasos deberás transcribir todas y cada una de las sentencias utilizadas.

### 1.- Sitúate en el directorio iso de la unidad C:. Crea con una única sentencia (p1, in, e1, e2)

```
New-Item -ItemType Directory iso -> Set-Location iso -> New-Item -ItemType Directory C:\iso\p1\in\e1\e2
```

<img width="417" height="329" alt="imagen" src="https://github.com/user-attachments/assets/7a7947e9-2dfe-4c02-9e39-3a21b4b65bd0" />

### 2.- Accede al directorio e2 utilizando trayectoria absoluta. Desde aquí crea los directorios (out, s1, s2, s31, s32) utilizando trayectorias relativas y en una única sentencia.

```
New-Item -ItemType Directory C:\iso\p1\out\s1\s2\s31, C:\iso\p1\out\s1\s2\s32
```

<img width="690" height="193" alt="imagen" src="https://github.com/user-attachments/assets/f4ede265-8f7a-4e9e-a4bf-491edb32ef5c" />




