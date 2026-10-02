---
on:
  workflow_dispatch:

permissions:
  contents: read

tools:
  github:
    toolsets:
      - repos

safe-outputs:
  create-issue:
    max: 1
---

# GHOST DARK CIRCLE — Revisión del repositorio

Analiza el repositorio Spikeblack009/spikeblack009.github.io.

Tu función en esta primera versión es SOLO analizar.

No modifiques archivos.
No hagas commits.
No hagas push.
No elimines archivos.
No cambies configuraciones.

## Revisa

- HTML
- CSS
- JavaScript
- enlaces
- rutas de archivos
- imágenes y recursos
- GitHub Pages
- Firebase
- Giscus
- carpeta Nuyoo
- blog
- compatibilidad móvil
- posibles problemas de seguridad
- posibles secretos expuestos

## Informe

Organiza el resultado en:

### ✅ CORRECTO
Lo que funciona correctamente.

### ⚠️ ATENCIÓN
Problemas o elementos que conviene revisar.

### ❌ ERRORES
Errores encontrados.

### 🔐 SEGURIDAD
Posibles problemas de seguridad.

### 📱 MÓVIL
Problemas específicos para teléfonos.

### 🔧 SOLUCIONES
Explica cómo solucionar cada problema.

No inventes información.
Si no puedes comprobar algo, indícalo claramente.