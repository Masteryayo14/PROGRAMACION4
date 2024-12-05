# PROGRAMACION4
PROGRAMACION 7MO SEMESTRE


# 📚 Biblioteca en Django  

## Descripción del Proyecto  
La **Biblioteca en Django** es una aplicación web diseñada para la gestión de libros de manera sencilla y eficiente. Incluye funcionalidades como:  
- **Crear, leer, actualizar y eliminar (CRUD)** libros.  
- Gestión de usuarios con autenticación (inicio y cierre de sesión).  
- Interfaz intuitiva para una experiencia de usuario fluida.  

Este proyecto está desarrollado utilizando el framework Django, con un enfoque en buenas prácticas de desarrollo y modularidad.  

---

## 🛠️ Requisitos del Sistema  
Para ejecutar este proyecto, necesitas contar con:  
- **Python** 3.8 o superior.  
- **Django** 4.2 o superior.  
- **pip** para la gestión de paquetes.  
- Navegador web moderno (Chrome, Firefox, Edge, etc.).  

---

## 🚀 Instrucciones de Instalación  

### 1. Clonar el Repositorio  
Clona el repositorio en tu máquina local:  
```bash
git clone https://github.com/usuario/biblioteca_django.git
cd biblioteca_django
```  

### 2. Configurar el Entorno Virtual  
Crea un entorno virtual para aislar las dependencias del proyecto:  
```bash
python -m venv venv
```  
### Activa el entorno virtual:  
- En **Windows**:  
  ```bash
  venv\Scripts\activate
  ```  
- En **macOS/Linux**:  
  ```bash
  source venv/bin/activate
  ```  

### 3. Instalar Dependencias  
Instala las dependencias necesarias con:  
```bash
pip install -r requirements.txt
```  

### 4. Configurar la Base de Datos  
Aplica las migraciones para preparar la base de datos:  
```bash
python manage.py makemigrations
python manage.py migrate
```  

---

## 🖥️ Ejecución del Proyecto  
Para iniciar la aplicación, ejecuta el siguiente comando:  
```bash
python manage.py runserver
```  
Abre tu navegador y accede a:  
```plaintext
http://127.0.0.1:8000/
```  

---

## Funcionalidades Clave  
### 1. Inicio de Sesión  
Permite que los usuarios accedan a la plataforma de forma segura.  
 

### 2. Gestión de Libros  
Una interfaz donde puedes visualizar, crear, editar y eliminar libros.  
 

### 3. Registro de Nuevos Usuarios  
Facilita la incorporación de nuevos usuarios al sistema.  


---

## 📋 Detalles Técnicos  

### Estructura del Proyecto  
El proyecto sigue la arquitectura típica de Django:  
- **App `libros`:** Gestión de las operaciones CRUD de los libros.  
- **Autenticación:** Uso las vistas predeterminadas de Django para el login y logout, personalizadas con estilos dentro de los mismos HTML.  

### Dependencias Clave  
- **Django:** Framework principal para la construcción del proyecto.  
- **SQLite:** Base de datos utilizada por defecto.  

---

## 📧 Información de Contacto  
Si tienes preguntas, sugerencias o deseas colaborar en el proyecto, no dudes en contactarme:  
- **Correo Electrónico:** scarvajalf@itc.edu.co  
- **GitHub:** https://github.com/Masteryayo14/PROGRAMACION4
---


¡Gracias por interesarte en este proyecto! Si encuentras útil esta aplicación, considera dejar una estrella ⭐ en el repositorio.  
