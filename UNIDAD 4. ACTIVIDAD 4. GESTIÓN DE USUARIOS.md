# UNIDAD 4. ACTIVIDAD 4. GESTIÓN DE USUARIOS

## 1.- Crea en tu SO a un usuario con tu nombre (en mi caso “alex”). Contraseña 2fpb1234

```
sudo useradd manuel -> sudo passwd manuel
```

<img width="676" height="201" alt="imagen" src="https://github.com/user-attachments/assets/c96c4c99-2051-4cc5-a6ce-1d6b2b14e238" />


## 2- Crea el grupo “grupotest”

```
sudo groupadd grupotest
```

<img width="676" height="112" alt="imagen" src="https://github.com/user-attachments/assets/4f6c722f-681a-4c36-8d85-d7241b407f67" />

## 3- Metemos a tu usuario en el grupo “grupotest”

```
sudo usermod -aG grupotest manuel
```

<img width="676" height="133" alt="imagen" src="https://github.com/user-attachments/assets/37df0a4c-a47a-4a1c-9a0e-e76f7a4ce25a" />

## 4- Cambia el nombre de tu usuario, por usuario2, en mi caso “alex2”

```
sudo usermod -l manuel2 manuel
```

<img width="676" height="133" alt="imagen" src="https://github.com/user-attachments/assets/36a33408-801a-4c0f-840a-d06e9c449436" />

## 5- Cambia la carpeta de referencia de usuario, en mi caso de /home/alex a home/alex2

```
sudo usermod -d /home/manuel2 -m manuel2
```

<img width="676" height="18" alt="imagen" src="https://github.com/user-attachments/assets/fcb8831f-b8f0-4d1e-8d37-611fb0b0fbe7" />

## 6- Intenta crear la carpeta “prueba” en /home/usuario2, en mi caso /home/alex2

```
mkdir /home/manuel2/prueba
```

<img width="1024" height="167" alt="imagen" src="https://github.com/user-attachments/assets/8b091380-b155-4d3c-a102-a969e2521cfd" />

## 7- Loguéate con tu usuario y contraseña (comando su)

```
su manuel2
```

<img width="1024" height="118" alt="imagen" src="https://github.com/user-attachments/assets/b7fea626-018a-4eae-a7c9-8448bffc6e2e" />

## 8- Intenta crear ahora carpeta en tu usuario

```
mkdir /home/manuel2/prueba
```
<img width="710" height="384" alt="imagen" src="https://github.com/user-attachments/assets/5d7a4362-4ca9-4022-a8e6-b0b6536c2ba8" />

## 9- Volvemos a loguearnos como “administrador” 

```
su administrador
```

<img width="368" height="142" alt="imagen" src="https://github.com/user-attachments/assets/b2cc8eeb-1181-45bb-9c2a-479eebc08dd7" />

## 10- Elimina tu usuario creado 

```
sudo userdel -r manuel2
```

<img width="673" height="151" alt="imagen" src="https://github.com/user-attachments/assets/fce9ce2e-22e0-4c44-a67c-35b08d891e85" />























