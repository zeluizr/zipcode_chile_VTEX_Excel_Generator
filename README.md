# 📮 Códigos Postales Chile VTEX - Generador Excel

[![Licencia MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

Una herramienta web gratuita y de código abierto para generar archivos Excel con todos los códigos postales de Chile, especialmente formateada para uso en la plataforma de e-commerce VTEX.

## 🎯 Características

- **📊 Completo**: Incluye las 16 regiones de Chile con todos sus códigos postales
- **🏢 VTEX Ready**: Formateado específicamente para la plataforma VTEX
- **📁 Organizado**: Genera un archivo Excel con 16 pestañas (una por región)
- **⚡ Rápido**: Generación instantánea sin necesidad de servidor
- **📱 Responsive**: Interfaz adaptable a diferentes dispositivos
- **🆓 Gratis**: Completamente gratuito y de código abierto

## 🚀 Demo en Vivo

Visita: [https://tu-dominio.com](https://tu-dominio.com) para usar la herramienta directamente.

## 📋 Contenido del Archivo Excel

El archivo generado contiene:

- **16 pestañas**: Una por cada región de Chile
- **2 columnas por pestaña**:
  - `Nombre`: Nombre de la comuna
  - `Código Postal`: Código postal correspondiente
- **Formato optimizado**: Para importación directa en VTEX

### Regiones incluidas

- I Región (Tarapacá)
- II Región (Antofagasta)
- III Región (Atacama)
- IV Región (Coquimbo)
- V Región (Valparaíso)
- VI Región (O'Higgins)
- VII Región (Maule)
- VIII Región (Bío Bío)
- IX Región (Araucanía)
- X Región (Los Lagos)
- XI Región (Aysén)
- XII Región (Magallanes)
- XIII Región Metropolitana
- XIV Región (Los Ríos)
- XV Región (Arica y Parinacota)
- XVI Región (Ñuble)

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura de la aplicación
- **JavaScript ES6+**: Lógica de procesamiento y generación
- **Tailwind CSS**: Diseño y estilos responsivos
- **SheetJS (xlsx)**: Librería para generación de archivos Excel
- **CDN**: Sin dependencias locales, funciona completamente offline

## 🏗️ Instalación y Uso Local

### Prerrequisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (solo para cargar las librerías CDN)

### Instalación

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/zeluizr/zipcode_chile_VTEX_Excel_Generator.git
   cd zipcode_chile_VTEX_Excel_Generator
   ```

2. **Abre el archivo**:

   ```bash
   open index.html
   # o simplemente abre index.html en tu navegador preferido
   ```

3. **¡Listo!** La aplicación estará funcionando inmediatamente.

## 📖 Cómo Usar

1. **Abre la aplicación** en tu navegador
2. **Revisa la vista previa** de los datos en la parte inferior
3. **Haz clic en "Generar Archivo Excel"**
4. **Descarga automática** del archivo `Codigos_Postales_Chile_VTEX_YYYY-MM-DD.xlsx`
5. **Importa en VTEX** según la documentación de la plataforma

## 🎯 Uso en VTEX

Este generador está especialmente diseñado para facilitar la configuración de códigos postales en tiendas VTEX:

### Pasos para usar en VTEX

1. Genera el archivo Excel usando esta herramienta
2. Accede al admin de tu tienda VTEX
3. Ve a **Configuración de la tienda** > **Envío** > **Código postal**
4. Importa el archivo Excel generado
5. Configura las reglas de envío según tus necesidades

## 🤝 Contribución

¡Las contribuciones son bienvenidas! Si quieres mejorar este proyecto:

1. **Fork** el proyecto
2. **Crea una rama** para tu feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. **Push** a la rama (`git push origin feature/AmazingFeature`)
5. **Abre un Pull Request**

### Ideas para contribuir

- [ ] Añadir validación de datos
- [ ] Mejorar el diseño UI/UX
- [ ] Añadir más formatos de exportación (CSV, JSON)
- [ ] Optimizar para dispositivos móviles
- [ ] Añadir tests automatizados
- [ ] Documentación en inglés
- [ ] Integración con APIs de correos

## 📊 Estadísticas del Proyecto

- **16 regiones** cubiertas
- **346+ comunas** incluidas
- **0 dependencias** de servidor
- **100% cliente** (funciona offline)
- **Licencia MIT** (uso comercial permitido)

## 🐛 Reportar Problemas

Si encuentras algún error o tienes una sugerencia:

1. Revisa los [issues existentes](https://github.com/zeluizr/zipcode_chile_VTEX_Excel_Generator/issues)
2. Si no existe, [crea un nuevo issue](https://github.com/zeluizr/zipcode_chile_VTEX_Excel_Generator/issues/new)
3. Incluye información detallada sobre el problema

## 📝 Changelog

### v1.0.0 (2024-01-XX)

- ✨ Lanzamiento inicial
- 📊 Datos completos de las 16 regiones de Chile
- 📁 Generación de Excel con múltiples pestañas
- 🎨 Interfaz responsiva con Tailwind CSS

## 📞 Contacto

- **Autor**: Jose Luiz Rodrigues
- **GitHub**: [@zeluizr](https://github.com/zeluizr)
- **Email**: [tu-email@ejemplo.com](mailto:tu-email@ejemplo.com)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

---

⭐ **Si este proyecto te fue útil, ¡no olvides darle una estrella!**

Hecho con ❤️ para la comunidad chilena de e-commerce
