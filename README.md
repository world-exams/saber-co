# 🇨🇴 Saber Para Todos - Colombia

> **Plataforma de práctica gratuita para el examen Saber 11° (ICFES)**

[![Status](https://img.shields.io/badge/status-active-brightgreen)](https://saberparatodos.space)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Organization](https://img.shields.io/badge/org-world--exams-purple)](https://github.com/world-exams)

## 🎯 Descripción

Plataforma web para practicar el examen Saber 11° de Colombia (ICFES). Incluye preguntas de todas las áreas del conocimiento con explicaciones detalladas.

## 🌐 Sitio en Vivo

**🔗 https://saberparatodos.space**

## 📚 Áreas de Conocimiento

- 📐 **Matemáticas** - Álgebra, geometría, cálculo
- 📖 **Lectura Crítica** - Comprensión de lectura y análisis
- 🧪 **Ciencias Naturales** - Biología, química, física
- 🌍 **Sociales y Ciudadanas** - Historia, geografía, civismo
- 🌐 **Inglés** - Comprensión de lectura en inglés

## ✨ Características

- ✅ **Preguntas ilimitadas** - Miles de preguntas de práctica
- ✅ **Explicaciones detalladas** - Aprende de tus errores
- ✅ **Modo examen** - Simula la experiencia real del Saber 11°
- ✅ **Modo entrenamiento** - Practica por áreas específicas
- ✅ **Historial de progreso** - Sigue tu evolución
- ✅ **100% Gratis** - Sin costos ni suscripciones

## 🏗️ Arquitectura

Esta es la **interfaz pública** de Saber Para Todos. El backend y las preguntas están en un repositorio privado para proteger el contenido.

```
saber-co (PÚBLICO)
├── UI/UX Frontend
└── Consume API de saberparatodos.space

saberparatodos (PRIVADO)
├── Backend API
├── Banco de preguntas
└── Edge Functions
```

## 🛠️ Stack Tecnológico

- **Frontend:** Astro 5 + Svelte 5
- **Estilos:** TailwindCSS
- **API:** saberparatodos.space/api
- **Hosting:** Cloudflare Pages
- **Analytics:** Integrado

## 🚀 Desarrollo Local

```bash
# Clonar el repositorio
git clone https://github.com/world-exams/saber-co.git
cd saber-co

# Instalar dependencias
npm install

# Configurar variables de entorno
cp .env.example .env
# Editar .env con tu configuración

# Ejecutar en desarrollo
npm run dev

# Construir para producción
npm run build
```

## 🌍 Otros Exámenes

Saber Para Todos es parte de **World Exams**, una organización que crea plataformas de práctica para exámenes estandarizados alrededor del mundo:

- 🇨🇴 **Colombia** - Saber 11° (este repo)
- 🇲🇽 **México** - EXANI-II *(próximamente)*
- 🇧🇷 **Brasil** - ENEM *(próximamente)*
- 🇦🇷 **Argentina** - Ingreso Universitario *(próximamente)*

Ver todos los exámenes en: https://world-exams.github.io

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Puedes ayudar con:

- 🐛 Reportar bugs
- 💡 Sugerir nuevas características
- 🎨 Mejorar el diseño UI/UX
- 📝 Mejorar la documentación
- 🌐 Traducciones

Ver [CONTRIBUTING.md](CONTRIBUTING.md) para más detalles.

## 📄 Licencia

MIT License - Ver [LICENSE](LICENSE) para más detalles.

El contenido de las preguntas tiene licencias separadas (ver backend privado).

## 📞 Contacto

- **Organización:** [github.com/world-exams](https://github.com/world-exams)
- **Website:** [world-exams.github.io](https://world-exams.github.io)
- **Email:** [contacto via GitHub Issues]

---

**Hecho con ❤️ para estudiantes colombianos**
