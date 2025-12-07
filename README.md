# Busaa – Plataforma Integral para la Adopción Responsable de Mascotas

> ⚠️ **Nota Importante**  
> El código fuente de Busaa **no es público**. Este proyecto fue desarrollado con fines altruistas para mejorar los procesos de adopción de animales y no deseo que sea utilizado de forma inapropiada o con fines comerciales.  
> Si deseas conocer más detalles técnicos o tener acceso al repositorio privado por motivos profesionales, puedes ponerte en contacto conmigo.

## 📘 Descripción General

**Busaa** es una plataforma completa creada como **proyecto final del Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)**.  
Su misión es facilitar la adopción responsable de perros y gatos mediante un sistema de compatibilidad inteligente que conecta a cada persona con la mascota que mejor se ajusta a su estilo de vida.

La plataforma está compuesta por:

- **Base de datos en Microsoft SQL Server**
- **API REST en C#**  
- **Aplicación Android nativa**  
- **Aplicación web para protectoras (Java Spring Boot)**  


## 🎯 Objetivos del Proyecto

- 🐶 Reducir las adopciones fallidas.
- 🏡 Ayudar a cada animal a encontrar su hogar definitivo.
- 💚 Promover la adopción responsable y consciente.
- 🤝 Mejorar la gestión interna de las protectoras.

## 🧩 Arquitectura de la Plataforma

### 🗄️ Base de Datos  
**Tecnología:** Microsoft SQL Server  
**Funciones clave:**
- Gestión de usuarios adoptantes y protectoras  
- Fichas completas de animales  
- Modelo de características y niveles de energía  
- Registro de adopciones, compatibilidades y preferencias

<a href="https://youtu.be/EqJbdHHcwe8">
  <img src="https://img.youtube.com/vi/EqJbdHHcwe8/maxresdefault.jpg" 
       alt="Ver demo"
       width="600" />
</a>

### ⚙️ API REST (Backend principal)  
**Lenguaje:** C#  
**Tipo:** API RESTful  
**Responsabilidades:**
- Autenticación y autorización  
- Lógica del sistema de matching  
- CRUD de animales, usuarios y protectoras  
- Gestión de solicitudes de adopción  
- Intermediario entre Android y la web administrativa  

### 📱 Aplicación Android (Usuarios)  
**Tecnología:** Android SDK (Java o Kotlin)  
**Funciones:**
- Perfil del usuario  
- Sistema de compatibilidad (matching)  
- Listado y filtrado de animales  
- Detalle completo del animal  
- Favoritos  
- Contacto con protectoras  

### 🐾 Aplicación Web – Protectoras  
**Tecnología:** Java Spring Boot  
**Uso dirigido a:** protectoras y refugios  
**Incluye:**
- Gestión de animales  
- Subida de fotos e información relevante  
- Panel administrativo interno  
- Control del estado de adopciones  

## ⭐ Características Destacadas

### 🔍 Matching Inteligente  
Evaluación de:
- Nivel de energía del animal  
- Experiencia del adoptante  
- Disponibilidad horaria  
- Tipo de hogar  
- Preferencias personales  

### 📚 Base de Datos de Animales  
Incluye:
- Fotografías  
- Edad, raza y tamaño  
- Personalidad  
- Necesidades especiales  
- Estado de salud  

### 🪄 Interfaz Cuidada y Accesible  
Diseñada para ser:
- Intuitiva  
- Visualmente agradable  
- Fácil de usar tanto para usuarios como para protectoras  

## 🏗️ Tecnologías Utilizadas

| Componente | Tecnología |
|------------|------------|
| Base de Datos | Microsoft SQL Server |
| Backend API | C#, .NET, REST |
| Android | Java/Kotlin, Android SDK |
| Web Protectora | Java Spring Boot |
| Arquitectura | Cliente–Servidor |
| Control de Versiones | Git + Repos privado |

## 🚀 Motivación Personal

Busaa busca aportar una mejora real al proceso de adopción, ayudando a reducir el número de animales en refugios y promoviendo decisiones conscientes y responsables.

## 🖼️ Galería del Proyecto  

(Images)

## 📬 Contacto

Si deseas más información, revisar el proyecto o acceder al repositorio privado:

🔗 LinkedIn: https://www.linkedin.com/in/david-roga/
