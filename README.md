# ⏰ 🌐 Proyecto Vite con Tailwind CSS v3, PostCSS y Autoprefixer

Este proyecto es una plantilla básica que integra Vite con Tailwind CSS versión 3, utilizando PostCSS y Autoprefixer para el procesamiento de estilos.

## 🛠️ Tecnologías Utilizadas
- Vite: Herramienta de compilación rápida para proyectos web modernos.
- Tailwind CSS v3: Framework de CSS utilitario para diseñar interfaces de usuario eficientes.
- PostCSS: Herramienta para transformar CSS con plugins.
- Autoprefixer: Plugin de PostCSS que añade prefijos específicos de navegador a las reglas CSS.

**Requisitos:📑**
Asegúrate de tener instalados los siguientes componentes:

- Node.js (versión 12 o superior)
- npm (gestor de paquetes de Node.js)

## ⚙️ Instalación

Para poner en marcha este proyecto en tu máquina local, sigue estos pasos:

1. Clona el repositorio

2. Instalar dependencias
```bash
npm install
```
3. Inicializar la configuracion de TailWind CSS 
```bash
npx tailwindcss init -p
```
Este comando genera los archivos tailwind.config.js y postcss.config.js en la raíz del proyecto.
4. Configurar los archivos de TailWind CSS🧮 
```bash
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
5. Ejecutar el servidor de desarrollo
```bash
npm run dev
```

📄 Licencia

Este proyecto está bajo la licencia MIT.

🎨 Capturas de Pantalla
Aquí tienes una vista previa de cómo luce el proyecto:

![Pantalla Principal](https://github.com/AlbertoContento/PROYECTOS-PYTHON/blob/main/PROYECTO08%20-%20Reloj%20Despertador/assets/Captura_de_pantalla.png)
