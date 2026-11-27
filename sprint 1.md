## Sprint 1 - Montaje

## 1. VM grafica(g07-grafica)

instalacion de Xubuntu con particion manual: / ,swap y /home. No usamos «borrar el disco»(añadir descripcion como el ejemplo)
| Partición | Tamaño | Por que |
|---|---|---|
| / | 15gb | porque aloja el sistema el escritorio y los programas  |
| swap | 2gb | porque respalda la RAM cuando se llena |
| /home | 9.84gb | porque guardo los archivos del usuario separados del sistema |

(añadir navegadores y editores intalados como por ejemplo Firefox y Chromium, nano y gedit.)
## Comandos usados
**Ajustar la hora y el nombre del equipo

sudo timedatectl set-timezone America/Bogota

sudo hostnamectl set-hostname g07-grafica

sudo sed -i 's/grupo-7-VirtualBox/g07-grafica/g' /etc/hosts

**Instalar editores y cliente SSH

sudo apt update

sudo apt install -y geany vim openssh-client

**Instalar navegadores

sudo apt install -y epiphany-browser falkon

sudo mkdir -p /usr/share/qt5

sudo dpkg --configure -a

**Verificar particiones

date; lsblk; df -h; cat /etc/fstab

**Verificar navegadores y editores

date; dpkg -l epiphany-browser falkon geany vim | grep ^ii

**Código del sprint

echo "YD07-PDUX" > ~/codigo_sprint1.txt

date; cat ~/codigo_sprint1.txt

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
| / | 10gb | porque es del sistema y los programas |
|/var | 6gb | porque registros y cache y datos que van creciendo |
| swap | 2gb | porque apoya a la RAM cuando se llena |
| /home | 7gb | porque los archivos del usuario |

<img width="4032" height="3024" alt="image" src="https://github.com/user-attachments/assets/86561979-4ade-4e97-b6ab-75afb5ec38ab" />

## Comandos usados
| Comandos |
|---|
| aqui van los comandos |
## Captura de pantalla 4

<img width="898" height="686" alt="image" src="https://github.com/user-attachments/assets/58a8a4ad-c96a-4f2d-a8c4-0f04f3ab5ce5" />

## Captura de pantalla 5
[Captura 5: las cinco herramientas mostrando su versión]

<img width="1293" height="205" alt="image" src="https://github.com/user-attachments/assets/84f21e16-5b2a-47f9-8b1d-735e54699e0f" />

## 3.Red 
Cada VM tiene dos adaptadores: el 1 en NAT (internet) y el 2 en red solo-anfitrión (para verse entre ellas).
Comandos: ip a en cada VM y ping en los dos sentidos.
## Captura de pantalla 6
[Captura 6: ip a en las dos VMs, mostrando una dirección en cada interfaz]

IP CONSOLA

<img width="847" height="442" alt="image" src="https://github.com/user-attachments/assets/218c980e-5b3d-4e8b-9862-ba5acb30918c" />

IP GRAFICA

<img width="1061" height="581" alt="image" src="https://github.com/user-attachments/assets/156b8bf0-515f-4a33-8da9-ae98d01f53fa" />

## Captura de pantalla 7
[Captura 7: ping de la gráfica a la consola y de la consola a la gráfica]

PING CONSOLA 

<img width="594" height="273" alt="image" src="https://github.com/user-attachments/assets/4f4799f5-823d-4cef-b64e-fc0d980ead99" />

PING GRAFICA 

<img width="650" height="376" alt="image" src="https://github.com/user-attachments/assets/7118d480-0efd-4b55-9cfa-31ffef1cfd03" />

## 4.SSH
Entramos por SSH desde la VM gráfica a la VM de consola.
Comando: ssh usuario@direccion-de-la-consola
## Captura de pantalla 8
[Captura 8: la sesión SSH abierta, con el prompt de la consola]

<img width="410" height="165" alt="image" src="https://github.com/user-attachments/assets/30c185e6-eab1-4ce6-a917-7d472999e581" />

## 5.Instantáneas
Una por VM, llamada instalacion-limpia, tomada con la VM apagada y la instalación terminada.
## Captura de pantalla 9
[Captura 9: pestaña de instantáneas de g07-grafica]

<img width="1600" height="855" alt="image" src="https://github.com/user-attachments/assets/208e9e57-efa4-42de-9e81-f449ed937c18" />

## Captarua de pantalla 10
[Captura 10: pestaña de instantáneas de g07-consola]

<img width="1600" height="857" alt="image" src="https://github.com/user-attachments/assets/1c922175-9bff-4216-b359-3ef3e32b1fb4" />

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

