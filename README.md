## 📖 Descripción del Proyecto

Esta aplicación web ha sido desarrollada utilizando **Blazor WebAssembly** tras culminar el [Curso de Blazor WebAssembly de Platzi](https://platzi.com/cursos/blazor-webassembly/). 

El proyecto demuestra la integración y consumo de servicios RESTful interactuando directamente con la [Platzi Fake Store API](https://fakeapi.platzi.com/), permitiendo listar productos, explorar categorías y gestionar la interfaz de usuario de manera dinámica, rápida y enteramente del lado del cliente.

## ✨ Características Principales

- **Arquitectura SPA:** Aplicación de página única (Single Page Application) ejecutada en el navegador mediante WebAssembly.
- **Consumo de API REST:** Integración asíncrona con Platzi Fake Store API utilizando `HttpClient`.
- **Componentes Reutilizables:** Diseño UI modular basado en componentes de Blazor (archivos `.razor`).
- **Enrutamiento del Cliente:** Navegación fluida sin recargas utilizando el sistema de enrutamiento integrado de Blazor.
- **Inyección de Dependencias:** Gestión eficiente de servicios de estado y clientes HTTP para una arquitectura limpia.

## 🛠️ Tecnologías Utilizadas

- **C# / .NET**
- **Blazor WebAssembly**
- **HTML5 & CSS3**
- **Platzi Fake Store API**

## 🚀 Instalación y Ejecución Local

Para ejecutar este proyecto en su propio entorno, tenga la bondad de seguir estos pasos:

### Requisitos Previos
- [.NET SDK](https://dotnet.microsoft.com/download) instalado en su sistema.
- Su editor de código de preferencia (Visual Studio, VS Code, JetBrains Rider).

### Pasos
1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/SuUsuario/NombreDelRepositorio.git
   cd NombreDelRepositorio
   ```
2. **Restaurar las dependencias del proyecto:**
   ```bash
   dotnet restore
   ```
3. **Ejecutar la aplicación (con recarga en caliente):**
   ```bash
   dotnet watch run
   ```
   *(La aplicación se abrirá automáticamente en su navegador por defecto).*

## 📂 Estructura Principal del Código

- `Pages/`: Contiene las vistas y rutas principales (ej. Catálogo, Detalles del Producto).
- `Components/`: Componentes UI reutilizables (tarjetas, menús de navegación, modales).
- `Services/`: Clases e interfaces dedicadas exclusivamente a la comunicación con la API.
- `Models/`: Clases de C# que tipan de forma segura las respuestas JSON de la API.

## 👨‍💻 Autor

**Vladimir Angarita**  
*Senior Software Developer | Systems Engineer*

---
*Proyecto desarrollado con fines educativos y de portafolio para demostrar competencias en el desarrollo Frontend con C# y WebAssembly.*
