# Mi Tienda D - Proyecto Django

¡Bienvenido a Mi Tienda D! Este proyecto es una tienda en línea creada con Django. Aquí encontrarás toda la información necesaria para configurar y ejecutar este proyecto en tu máquina local.

## Requisitos Previos

Asegúrate de tener instalados los siguientes requisitos antes de comenzar:

- Python 3.6 o superior
- Django
- Pillow

## Instalación

Sigue estos pasos para configurar el proyecto:

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
   
Crea y activa un entorno virtual:
python -m venv env
source env/bin/activate  # En Windows usa `env\Scripts\activate`

2. **Instala las dependencias necesarias**
   ```bash
    pip install django
    pip install pillow

3. **Configuración**
Configura las variables de entorno:

Crea un archivo .env en el directorio raíz del proyecto y añade tus variables de entorno según sea necesario.

Realiza las migraciones:

    python manage.py makemigrations
    python manage.py migrate

Crea un superusuario(opcional):
    python manage.py createsuperuser

Ejecutar el Servidor
Para iniciar el servidor de desarrollo, utiliza el siguiente comando: python manage.py runserver


Funcionalidades
Usuarios Administradores
Ver y crear productos
Ver y crear usuarios
Usuarios Regulares
Agregar productos al carrito
Ver el carrito de compras
Restricciones
Solo los administradores pueden ver y acceder a las secciones de gestión de productos y usuarios.
Los usuarios regulares solo pueden ver y utilizar el carrito de compras.


Contacto
Si tienes alguna pregunta o sugerencia, no dudes en contactarme a través de ca.monge@duocuc.cl



Claro, aquí tienes el README.md actualizado con la sección de colaboradores:



## Colaboradores

- [Camilo](https://github.com/CvmiloM)
- [Fabián](https://github.com/Fabiancitto)

**Imagenes**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/5db33b07-9ae7-47d6-8e41-7b8380c72c15)
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/814fab89-9274-47d8-be53-b2cf178eee2e)

**Funcionalidades del admin**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/d13fd2fb-badd-4c12-afa5-5abc6af65c5d)
1. **Productos Lista**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/bd7bf0c6-eca1-429e-a6ab-36e9a73074a6)
2. **Crear Productos**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/d6d0a704-68d0-446f-9e91-a4f6fc7d9751)
3.**Lista de Usuarios**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/f106ae20-14b3-46aa-b3a3-0cf08ae413a1)
4.**Crear Usuarios**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/5ebc0b0d-36b7-4955-bb89-728bcc8aa0f3)
5.**al agregar un producto al carrito aparece un mensaje**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/b4d21ca5-4166-4191-99c6-902ac8e3db8b)
6.**Solo el admin podra ver estas cosas**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/9645d100-521a-407a-9341-8c943429f7f2)
7.**Ver el detalle de la compra**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/59b7d935-afee-4388-b92a-8d777a1983e1)
8.**Ver la lista de compra**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/e1b2adc0-db23-4adb-828d-1a3a1a9dc864)

## Usuario Normal solo tendra estas funciones

![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/7601261f-bfb4-4340-add9-ea836116c9af)

1.**cuando compramos solo veremos este boton y el mensaje al igual que nos llegare un correo electronico**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/65151ea9-adbc-4159-bc63-0ea7a1c30498)

2**Mensaje del correo electronico**
![image](https://github.com/CvmiloM/Pagina_web_3/assets/135039204/243d1b83-4957-46ee-89b7-fb080554e8b7)





