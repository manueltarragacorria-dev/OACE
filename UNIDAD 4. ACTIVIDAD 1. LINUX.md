# UNIDAD 4. ACTIVIDAD 1. LINUX

## 1.- Crea el directorio SMM en tu directorio de usuario. Desde el directorio SMM crea los directorios (1_eval, teoria, t1, practica, p1a, p1b) utilizando trayectorias absolutas y una única sentencia.

```
mkdir SMM -> cd SMM -> mkdir -p /home/administrador/SMM/1_eval/teoria/t1, /home/administrador/1_eval/practica/p1a/p1b
```

<img width="1137" height="131" alt="imagen" src="https://github.com/user-attachments/assets/1fbde6f0-54ac-4c9e-9c84-d480e91900b1" />

## 2.- Desde el directorio p1b crea los directorios (3_eval, teoriaa, teoriab) utilizando trayectorias relativas.

```
mkdir -p ../../../../3_eval/teoriaa/teoriab
```

<img width="853" height="113" alt="imagen" src="https://github.com/user-attachments/assets/10d7b7db-ce55-4822-8630-3b58a030c4b1" />

## 3.- Desde el directorio SMM crea el directorio (2_eval).

```
cd /home/administrador/SMM -> mkdir 2_eval
```

<img width="695" height="113" alt="imagen" src="https://github.com/user-attachments/assets/18adc8e7-b7bf-4fef-bdd4-59d1a577d930" />

## 4.- Accede al directorio 2_eval. Desde aquí crea los directorios (prac1, prac2, prac3) con una única sentencia.

```
mkdir prac1 prac2 prac3
```

<img width="538" height="113" alt="imagen" src="https://github.com/user-attachments/assets/daf9cd37-fef9-4515-8c8f-660ffb954913" />

## 5.- Accede al directorio prac3. Desde aquí crea los directorios (prac31, prac311) usando trayectorias relativas.

```
cd prac3 -> mkdir -p prac31/prac311
```

<img width="575" height="113" alt="imagen" src="https://github.com/user-attachments/assets/20c72f73-942d-4822-9085-14d47317fc46" />


## 6.- Accede al directorio SMM usando trayectoria absoluta con una única sentencia

```
cd /home/administrador/SMM
```

<img width="597" height="96" alt="imagen" src="https://github.com/user-attachments/assets/5c8ecaea-a208-4f0c-bff5-3e5f50c1a0b4" />

## 7.- Desde aquí elimina los directorios (prac311, prac31, teoriab, teoriaa, t1, p1b, p1a) utilizando trayectorias absolutas

```
rm -r 2_eval/prac3/prac31 3_eval/teoriaa 1_eval/teoria/t1 1_eval/practica/p1a
```

<img width="937" height="96" alt="imagen" src="https://github.com/user-attachments/assets/ac53874b-0eab-4f4d-80dc-3173ccdeac33" />

## 8.- Accede al directorio 2_eval usando trayectoria relativa con una única sentencia.

```
cd 2_eval
```

<img width="339" height="124" alt="imagen" src="https://github.com/user-attachments/assets/4edfa3ed-c28a-4b50-bdf5-984f146344c4" />

## 9.- Desde aquí cambia el nombre del directorio prac1 por el de prac4. (El comando sería el mv →investiga en la ayuda de Linux. Recuerda que el comando de ayuda es man).

```
mv prac1 prac4
```

<img width="439" height="188" alt="imagen" src="https://github.com/user-attachments/assets/22fa41bd-fb11-479c-8380-a29b112ead01" />

## 10.- Desde aquí sitúa el directorio prac4 dentro del directorio prac3.

```
mv prac4 prac3/prac4
```

<img width="492" height="188" alt="imagen" src="https://github.com/user-attachments/assets/18b0cc36-0529-45b6-bc13-fb865e58d41b" />

## 11.- Desde aquí elimina los directorios (1_eval, 3_eval)

```
rmdir -r ../1_eval ../3_eval
```

<img width="664" height="226" alt="imagen" src="https://github.com/user-attachments/assets/bc809152-0f02-4bab-8678-4b9ca73c4bda" />

## 12.- Consulta la ayuda del comando cal (Recuerda que el comando de ayuda es man). Utiliza dicho comando para visualizar el calendario del mes de enero de 2021.

```
man cal -> cal 01 2021
```

<img width="1008" height="942" alt="imagen" src="https://github.com/user-attachments/assets/847f4d35-52af-45a8-a4df-5a7130aacc2d" />
<img width="345" height="278" alt="imagen" src="https://github.com/user-attachments/assets/b326f236-bbae-459d-8d3e-915022cfbed7" />














