# Conexión de Sistemas en Red
  
_Larissa Gerpe Rangel y Santiago Marticó Bello_

***
  
### ÍNDICE:
1. Creación de una red LAN utilizando máquinas virtuales:
1.1 Establecer una red de área local (LAN) en la que se conecten dos máquinas virtuales:   
1.2 Investiga y aporta un esquema que ejemplifique su funcionamiento:   
2. Establecimiento de permisos locales en Windows 11 Pro  
2.1 Mapa lógico de red 
2.2 Listado de dispositivos  
2.3 Presupuesto    
3. Bibliografia  
  
***

## 1. Creación de una red LAN utilizando máquinas virtuales:  

### 1.1 Establecer una red de área local (LAN) en la que se conecten dos máquinas virtuales:   

- En ambas máquinas buscamos su tipo de red desde el panel de configuración de red de virtual vox (en ambas es LAN) y lo cambiamos a red interna.
![Captura1](./Fotos_1_1/Captura1.png)
![Captura2](./Fotos_1_1/Captura2.png)

- Desde la terminal de linux de la primera máquina le configuramos una ip estática mediante un archivo “netplan”. Tendremos que crearlo, insertar la instrucción para crear la ip estática y ejecutarlo.
![Captura3](./Fotos_1_1/Captura3.png)
![Captura4](./Fotos_1_1/Captura4.png)
![Captura5](./Fotos_1_1/Captura5.png)

- Hacemos lo mismo en la segunda máquina virtual pero dándole otra ip distinta
![Captura6](./Fotos_1_1/Captura6.png)

- Para comprobar que están en la misma red LAN podemos hacer varias cosas como pedir información de una máquina desde la otra, en este caso pediremos el ping de la segunda máquina desde la primera.
![Captura7](./Fotos_1_1/Captura7.png)

### 1.2 Investiga y aporta un esquema que ejemplifique su funcionamiento:

● NAT
![Captura8]()

● Adaptador puente
![Captura9]()

● Red interna
![Captura10]()

● Red NAT
![Captura11]()


## 2. Diseño de una red LAN:  

### 2.1 Mapa lógico de red
![Captura12]()

### 2.2 Listado de dispositivos

- Switch (TP-Link TL-SG3452XP)
![Captura13]()

- Bobina de cable de par trenzado (Bobina 100m Cable Red Rígido UTP Cat. 6 10/100/1000)
![Captura14]()

- Clavijas RJ45 (Equip Conector RJ45 Cat6 100 Unidades)
![Captura15]()

- Crimpador (6COMGIGA)
![Captura16]()

### 2.3 Presupuesto

|              | Switch    | Bobina   | Clavija  | Crimpador |
|--------------|-----------|----------|----------|-----------|
| Precio S/IVA | 613,03€   | 22,03€   | 26,78€   | 16,58€    |
| Precio C/IVA | 775,99€   | 27,89€   | 33,99€   | 20,99€    |
| Total S/IVA  | 613,03€   | 22,03€   | 26,78€   | 16,58€    |
| Total C/IVA  | 775,99€   | 27,89€   | 33,99€   | 20,99€    |

## 3. Bibliografía:

- https://www.pccomponentes.com/tp-link-tl-sg3452xp-switch-administrado-48-puertos-gigabit-poe-10-100-1000-4-puertos-sfp

- https://www.pccomponentes.com/bobina-100m-cable-red-rigido-utp-cat-6-10-100-1000

- https://www.pccomponentes.com/equip-conector-rj45-cat6-100-unidades

- https://www.amazon.es/6COMGIGA-Herramienta-crimpado-crimpadora-6C-CT-02/dp/B0C7VP8WMV/ref=sr_1_3_sspa?dib=eyJ2IjoiMSJ9.fo5sUoZXxncbdWC6fySPWlsLu6KdqO8ToFKGbwrY6S5m59jEO4gZxBy4bloIMwlK3PHOqXnruJQu31sKWlREGGNjM5v8u8RifINNQAu5ElHwfEhX_QUgRrCK7kn6i9-mHtpj6T6FPnXUt2BpJZTw4Fwi1n4AvlNOnF0NP6Fpk5za3NrhOl4DfloNuTW_wHn-asvXr9fUrhAsHthFpBXQPl4a67j5VRYaXMw7xlhEPz9qevc_QttVX9muCePiJMDMLo78WuvRrXbOfwpUhebPBkW4AZ4Igf7Nb3pnplLaUBU.wwiXsIcSNxcpxLaqICz4ARIZ-ge9817gHEzkw7rHdtQ&dib_tag=se&keywords=crimpadora%2Brj45&qid=1716798608&sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1

