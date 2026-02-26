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



































