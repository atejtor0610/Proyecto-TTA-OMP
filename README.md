# Proyecto-TTA-OMP




## Índice

###### 1. Figura del Entorno ######
###### 3. Espacio de Nombres ######
###### 4. Zonas Directas e Inversas ######
###### 6. Servidor DNS de sólo caché ######
###### 7. Resolución clientes DNS ######
###### 8. Registros especiales ######
###### 9. Transferencia de zona ######


### *1. Figura del Entorno*
     Esta es nuestra figura de enterno para el proyecto:
![image](https://user-images.githubusercontent.com/116157396/214513913-59001abf-cca0-4532-b785-9ec14b63eaea.png)

### *2. Tener instalado Debian6-Pruebas*
     Está instalado Debian6-Pruebas además de contener su configuración para el uso.
![image](https://user-images.githubusercontent.com/116157396/214515199-857f6d40-9b0f-4212-9da3-ab41eb7bb318.png)

     
### *3. Espacio de Nombres*
     Esta es nuestro espacio de nombres:
![image](https://user-images.githubusercontent.com/116157396/214514480-f3fa04ba-bde1-4c52-ac93-71083be514cc.png)
     
### *4 y 5. Zonas Directas e Inversas*
     Nuestras zonas directas se basan en la siguinte configuración en base a nuestra figura de entorno y espacio de nombres.
  
   ***Fichero /etc/binf/named.conf.local***
   
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/1.png)
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/1.1.png)
   
   ***Fichero /etc/binf/named.conf.options***
   
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/2.png)
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/2.2.png)
   
   ***Fichero /etc/binf/named.conf.default-zones***
   
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/3.png)
  
   
  
   ***Fichero /var/lib/bind/db.(1º Red)***
   
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/4.png)
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/4.4.png)
   
   

   ***Fichero /var/lib/bind/db.2smradmin.com***
   
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/6.png)
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/6.6.png)
   
   
     
### *6. Servidor DNS de sólo caché*  
     El D2 está en la Red 2, esta es su confguración para el servidor de sólo caché:
   ![image](
   ![image](
   
     Esta es la configuración de D1:
   ![image](
   ![image](
   
   ![image](
   ![image](
     

### *7. Resolución clientes DNS* 
     Configuración D1:
   ![image](
   ![image](
   
     Configuración D2:
  ![image](
  ![image](
  
     Configuración D3:
  ![image](
  ![image](
  
     Configuración D5:
   ![image](
   ![image](
   
     Configuración D6:
   ![image](
   ![image](

### *8. Registros Especiales* 

###  *9. Transferencia de zona*








