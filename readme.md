# Workshop 2

## Levantar la VM

1. Vamos a la ruta de /vms
2. Ejecutamos el comando `vagrant up`

## Agregar rutas DNS

1. En la ruta `c/windpows/system32/drivers/etc/hosts` editamos el archivo `hosts`
2. Agregamos las siguientes entradas

   - 192.168.33.10 webserver
   - 192.168.33.10 mibanco.com
   - 192.168.33.10 lfts.isw811.xyz

3. Despues hacemos Ping a los dominios

   - ping webserver
   - ping mibanco.com
   - ping lfts.isw811.xyz

4. Los pings deben ser exitosos a todos los dominios

## Index

- [Workshop #1](../WorkShop1/readme.md)
