# UNIDAD 4. ACTIVIDAD 2. LINUX

## 1.- Situado en smm crea los directorios A, B, C, D, A1, A2, A3, B1, B11, B111, B112, A21, A22, A221 con trayectorias relativas.

```
mkdir SMM -> cd SMM -> mkdir A B C D A1 A2 A3 B1 B11 B111 B112 A21 A22 A221
```

<img width="723" height="131" alt="imagen" src="https://github.com/user-attachments/assets/e30b14d7-2970-4676-8443-081895926880" />

## 2.- Situado en A1 crea en A21 un fichero llamado o1 que contenga “Fernando” en la primera línea, “Zoraida” en la segunda línea y “Antonia” en la tercera línea. UTILIZA LAS REDIRECCIONES. Almacena el fichero o1 ordenado dentro del directorio C con el nombre Orden.

```
cd A1 -> echo "Fernando\nZoraida\nAntonia" | sort > ../A21/o1
```

<img width="784" height="38" alt="imagen" src="https://github.com/user-attachments/assets/1635032d-75b8-4d0d-8f3b-534df97688e4" />

## 3.- Crea una copia de A dentro de D con el nombre nuevoA. A continuación elimina A.

```
cp -r ../A ../D -> rm -r ../A
```

<img width="414" height="36" alt="imagen" src="https://github.com/user-attachments/assets/61b33a2b-9b44-4290-9352-b0ef0cbc9070" />

