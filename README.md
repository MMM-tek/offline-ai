# IA Offline - Chat Local

Aplicación de chat con IA que funciona completamente offline en tu navegador. ¡Sin conexión a internet necesaria!

## ✨ Características

- ✅ Funciona offline - Sin dependencias externas
- ✅ Cero errores CORS - Abre simplemente el archivo HTML
- ✅ Soporte multilingüe
- ✅ Interfaz moderna similar a WhatsApp
- ✅ Modelos locales en .zip

## 🚀 Uso

### Opción 1: Abrir directamente (Recomendado)
1. **Haz clic derecho** en `index.html`
2. Selecciona **"Abrir con"** → Tu navegador favorito
3. ¡Listo! La aplicación está lista para usar

El archivo HTML está completamente autodidáctico - todas las librerías están incrustadas dentro, sin necesidad de referencias externas.

### Opción 2: Servidor local (Alternative)
Si prefieres usar un servidor local:
```bash
python3 -m http.server 8000
```
Luego abre http://localhost:8000 en tu navegador

## 📦 Primeros pasos

1. **Selecciona un modelo**: Carga un archivo `modelo.zip` con los pesos de la IA
2. **Escribe tu mensaje**: Usa la caja de texto para interactuar
3. **Obtén respuestas**: La IA procesa localmente en tu navegador

## 🔧 Archivos incluidos

- `index.html` - Aplicación Web completa (incrustrada, sin CORS)
- `Models.zip` - Modelos de ejemplo
- `jszip.min.js` - Librería para descompresión ZIP
- `transformers.min.js` - Librería de IA

## 📝 Notas técnicas

- El archivo HTML (1.3MB) contiene todas las dependencias incrustradas para evitar problemas de CORS con `file://`
- Compatible con Chrome, Firefox, Edge y Safari
- Requiere modelo en formato compatible (ONNX recomendado)

---
**¡Disfruta tu IA personal offline! 🤖**