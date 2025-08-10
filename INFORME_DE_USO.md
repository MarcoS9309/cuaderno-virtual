# 📋 Informe de Uso - Cuaderno Virtual

## 🎯 Resumen del Proyecto

El **Cuaderno Virtual** es un repositorio que alberga dos proyectos experimentales que exploran la intersección entre tecnología, arte y bienestar emocional:

1. **Cuentos Emocionales** 📖
2. **Psicodrama Virtual** 🎭

---

## 📂 Estructura del Repositorio

```
cuaderno-virtual/
├── 📄 README.md                    # Documentación principal
├── 📄 LICENSE                      # Licencia MIT
├── 📄 INFORME_DE_USO.md            # Este documento
├── 📂 cuentos-emocionales/
│   ├── 📄 README.md                # Documentación específica
│   ├── 📄 index.html               # Página web del proyecto
│   └── 📄 cuento.md                # Contenido narrativo
└── 📂 psicodrama-virtual/
    ├── 📄 README.md                # Documentación específica
    ├── 📄 index.html               # Aplicación web teatral
    └── 📄 LICENSE                  # Licencia específica
```

---

## 🚀 Cómo Usar los Proyectos

### **Proyecto 1: Cuentos Emocionales** 📖

#### **Propósito:**
Explorar narrativas que conectan emociones y experiencias personales para fomentar la empatía y reflexión.

#### **Cómo usarlo:**
1. **Visualización web:**
   ```bash
   # Navegar a la carpeta
   cd cuentos-emocionales/
   
   # Abrir con servidor local
   python3 -m http.server 8080
   # Abrir http://localhost:8080 en el navegador
   ```

2. **Lectura del contenido:**
   - Abrir `cuento.md` para leer las narrativas
   - Visualizar `index.html` para la experiencia web completa

#### **Características técnicas:**
- Diseño vintage con paleta de colores cálida
- Tipografía serif para lectura cómoda
- Imágenes optimizadas con efectos sepia
- Estructura HTML semántica

---

### **Proyecto 2: Psicodrama Virtual** 🎭

#### **Propósito:**
Aplicar técnicas de psicodrama en entornos digitales, combinando teatro clásico con tecnología moderna.

#### **Cómo usarlo:**
1. **Acceso directo:**
   ```bash
   # Navegar a la carpeta
   cd psicodrama-virtual/
   
   # Iniciar servidor
   python3 -m http.server 8080
   # Abrir http://localhost:8080 en el navegador
   ```

2. **Características interactivas:**
   - **Cortinas teatrales:** Animación de apertura automática
   - **Timeline del proceso:** 4 fases del psicodrama
   - **Cards de técnicas:** Role Playing, Espejo Digital, etc.
   - **Diseño responsive:** Adaptable a móviles y tablets

#### **Técnicas implementadas:**
- **🎭 Role Playing:** Exploración de perspectivas
- **🪞 Espejo Digital:** Técnicas de autorrefleción
- **🔄 Inversión de Roles:** Cambio de perspectivas
- **🎪 Escenario Virtual:** Espacios seguros de expresión

---

## 🛠️ Requisitos Técnicos

### **Para desarrollo:**
- **Git** para control de versiones
- **Navegador web moderno** (Chrome, Firefox, Safari, Edge)
- **Servidor web local** (Python, Node.js, o extensión Live Server)
- **Editor de código** (VS Code recomendado)

### **Para uso básico:**
- Cualquier navegador web
- Conexión a internet (para fuentes de Google)

---

## 🌐 Deployment y Hosting

### **Opciones recomendadas:**

1. **GitHub Pages** (Gratuito):
   ```bash
   # En la configuración del repositorio en GitHub
   Settings > Pages > Source: Deploy from branch > main
   ```

2. **Netlify** (Gratuito):
   - Conectar repositorio de GitHub
   - Auto-deploy en cada push

3. **Vercel** (Gratuito):
   - Importar desde GitHub
   - Deploy automático

### **URLs de ejemplo:**
- Cuentos Emocionales: `https://usuario.github.io/cuaderno-virtual/cuentos-emocionales/`
- Psicodrama Virtual: `https://usuario.github.io/cuaderno-virtual/psicodrama-virtual/`

---

## 📚 Guía de Contribución

### **Para añadir contenido:**

1. **Nuevos cuentos:**
   ```bash
   # Crear nuevo archivo en cuentos-emocionales/
   touch cuentos-emocionales/nuevo-cuento.md
   ```

2. **Nuevas técnicas de psicodrama:**
   - Editar `psicodrama-virtual/index.html`
   - Añadir nueva card en la sección "techniques-grid"

3. **Mejoras de diseño:**
   - CSS está embebido en cada `index.html`
   - Usar variables CSS para consistencia
   - Mantener accesibilidad (ARIA labels)

### **Workflow de desarrollo:**
```bash
# 1. Clonar repositorio
git clone https://github.com/MarcoS9309/cuaderno-virtual.git

# 2. Crear rama para cambios
git checkout -b nueva-funcionalidad

# 3. Realizar cambios
# ... editar archivos ...

# 4. Commit y push
git add .
git commit -m "Descripción del cambio"
git push origin nueva-funcionalidad

# 5. Crear Pull Request en GitHub
```

---

## 🎨 Consideraciones de Diseño

### **Paletas de colores:**

**Cuentos Emocionales:**
- Primario: `#f8ecd4` (Beige papel)
- Secundario: `#3a2c1a` (Marrón tinta)
- Acento: `#bfa77a` (Dorado vintage)

**Psicodrama Virtual:**
- Primario: `#2C1810` (Marrón teatro)
- Secundario: `#8B4513` (Cortina terciopelo)
- Acento: `#FFD700` (Dorado teatral)

### **Tipografías:**
- **Cuentos:** Georgia, serif (legibilidad)
- **Psicodrama:** Playfair Display + Source Sans Pro (elegancia teatral)

---

## 📊 Métricas y Analíticas

### **Para implementar seguimiento:**

1. **Google Analytics:**
   ```html
   <!-- Añadir en <head> de cada index.html -->
   <script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
   ```

2. **Plausible Analytics** (Alternativa privacy-friendly):
   ```html
   <script defer data-domain="tudominio.com" src="https://plausible.io/js/script.js"></script>
   ```

---

## 🔧 Mantenimiento

### **Tareas regulares:**
- [ ] Verificar enlaces externos (Wikipedia, etc.)
- [ ] Actualizar dependencias de fuentes
- [ ] Optimizar imágenes de Unsplash
- [ ] Revisar accesibilidad con herramientas WAVE
- [ ] Validar HTML con W3C Validator

### **Backup y versionado:**
- Repositorio Git como backup principal
- Tags para versiones estables: `git tag v1.0.0`
- Branches para experimentos: `experimental/nueva-idea`

---

## 📞 Soporte y Contacto

### **Para reportar problemas:**
1. Crear issue en GitHub con:
   - Descripción del problema
   - Pasos para reproducir
   - Navegador y versión
   - Screenshots si aplica

### **Para sugerencias:**
- Usar GitHub Discussions
- Etiquetas: `enhancement`, `documentation`, `design`

---

## 📄 Licencia y Créditos

- **Licencia:** MIT License
- **Imágenes:** Unsplash (licencia libre)
- **Fuentes:** Google Fonts (SIL Open Font License)
- **Inspiración:** Psicodrama de Jacob Levy Moreno

---

## 🎉 Estado del Proyecto

✅ **Completado:**
- Estructura básica de ambos proyectos
- Diseño responsive y accesible
- Documentación completa
- Control de versiones configurado

🔄 **En desarrollo:**
- Expansión de contenido narrativo
- Nuevas técnicas de psicodrama
- Integración con herramientas de IA

💡 **Futuras mejoras:**
- PWA (Progressive Web App)
- Modo offline
- Múltiples idiomas
- Integración con redes sociales

---

*Última actualización: Agosto 10, 2025*
*Versión del documento: 1.0*
