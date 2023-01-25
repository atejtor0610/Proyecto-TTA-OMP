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
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/7.png)
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/7.7.png)
   
     Esta es la configuración de D1:
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/8.png)
  
   
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/8-8.png)
   
     

### *7. Resolución clientes DNS* 
     Configuración D1:
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/a.png)
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/a.a.png)
   
     Configuración D2:
  ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/b.png)
  ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/b.b.png)
  
     Configuración D3:
  ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/c.png)
  ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/c.c.png)
  
     Configuración D5:
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/d.png)
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/d.d.png)
   
     Configuración D6:
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/e.png)
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/e.e.png)
   

### *8. Registros Especiales* 
     Tener servidores DNS (D5 y D6):
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/z.png)
    
     D3 servidor de correo
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/x.png)
     
     Router llamado enrutador
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/s.png)
      
     D5 y D6 se llaman servidordns1 y servidordns2
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/d5d6.png)
      
     MX D3
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/m.png)
      
     Registro SOA
   ![image](https://github.com/atejtor0610/Proyecto-TTA-OMP/blob/main/capturas/n.png)







###  *9. Transferencia de zona*








