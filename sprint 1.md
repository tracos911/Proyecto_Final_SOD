## Sprint 1 - Montaje

## 1. VM grafica(g07-grafica)

instalacion de Xubuntu con particion manual: / ,swap y /home. No usamos «borrar el disco»(añadir descripcion como el ejemplo)
| Partición | Tamaño | Por que |
|---|---|---|
| / | 15gb | porque |
| swap | 2gb | porque |
| /home | 9.84gb | porque |

(añadir navegadores y editores intalados como por ejemplo Firefox y Chromium, nano y gedit.)
## Comandos usados
| Comandos |
| aqui van los comandos |
## Captura de pantalla 1
<img width="1759" height="942" alt="image" src="https://github.com/user-attachments/assets/83da3897-a995-4277-8059-cdebfa03ec7d" />


## Captura de pantalla 2
<img width="1283" height="801" alt="image" src="https://github.com/user-attachments/assets/953a351b-96f5-4656-92a1-180833930739" />

## Captura de pantalla 3
<img width="1278" height="646" alt="image" src="https://github.com/user-attachments/assets/c0e5b6d3-a3b1-4afa-9d69-48c6a21e4ce0" />


## 2.VM de consola(g07-consola)
instalacion de Rocky linux con particion manual: / ,swap, /home y /var. disco de 25 GB y 2 CPU.(añadir descripcion como en el ejemplo) 
| Partición | Tamaño | Por que |
|---|---|---|
| / | 2gb | porque |
|/var | 2gb | porque |
| swap | 2gb | porque |
| /home | 2gb | porque |

(añadir herramientas instaladas como por ejemplo make, rsync, curl, git y wget)
## Comandos usados
| Comandos |
|---|
| aqui van los comandos |
## Captura de pantalla 4
[Captura 4: lsblk, df -h y cat /etc/fstab de g07-consola, con prompt y fecha]
## Captura de pantalla 5
[Captura 5: las cinco herramientas mostrando su versión]

## 3.Red 
Cada VM tiene dos adaptadores: el 1 en NAT (internet) y el 2 en red solo-anfitrión (para verse entre ellas).
Comandos: ip a en cada VM y ping en los dos sentidos.
## Captura de pantalla 6
[Captura 6: ip a en las dos VMs, mostrando una dirección en cada interfaz]
## Captura de pantalla 7
[Captura 7: ping de la gráfica a la consola y de la consola a la gráfica]

## 4.SSH
Entramos por SSH desde la VM gráfica a la VM de consola.
Comando: ssh usuario@direccion-de-la-consola
## Captura de pantalla 8
[Captura 8: la sesión SSH abierta, con el prompt de la consola]

## 5.Instantáneas
Una por VM, llamada instalacion-limpia, tomada con la VM apagada y la instalación terminada.
## Captura de pantalla 9
[Captura 9: pestaña de instantáneas de g07-grafica]
## Captarua de pantalla 10
[Captura 10: pestaña de instantáneas de g07-consola]

## Codigo del sprint
se publica 48 horas antes del cierre en el campus

## Video del sprint 1(3 minutos)
Pantalla continua y sin cortes. Cada integrante muestra su parte, dice su nombre y qué hizo en los primeros 10 segundos, y aparece su cara.
Aquí va el enlace del video de YouTube (público o no listado).<<--- como se tiene que hacer el video
## Lo que realizo cada integrante en este sprint
| Integrante | Que hizo | Commits |
|---|---|---|
| Jeffrey florez prado | Creo las paginas del sitio y reviso que no falte nada | 4 |
| Jean Paul López Bolaños | falta | porque |
| Carlos Valencia | falta | porque |

