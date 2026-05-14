# Chu Han Zhen Xiong - Ajedrez Chino

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Versión">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="Licencia">
  <img src="https://img.shields.io/badge/HTML5-Game-orange.svg" alt="HTML5">
</p>

**楚汉争雄** es un juego de ajedrez chino implementado en HTML5 puro. Sin dependencias externas, se juega directamente en el navegador. Soporta modo persona vs persona y persona vs IA.

[English](README.md) | [简体中文](README_zh-CN.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md)

---

## Características

### Reglas del Ajedrez Chino
- ✅ Implementación completa de las reglas del ajedrez chino
- ✅ 7 tipos de piezas: General/General, Asesor/Asesor, Elefante/Elefante, Carro/Carro, Caballo, Cañón/Cañón, Soldado/Soldado
- ✅ Reglas de bloqueo de caballo y的眼塞规则
- ✅ Regla de enfrentando entre Generales
- ✅ Detección de jaque, jaque mate y ahogado

### Modos de Juego
- 🔹 **Persona vs Persona** - Dos jugadores en el mismo dispositivo
- 🔹 **Persona vs IA** - Juega contra la IA con tres niveles de dificultad

### Dificultad de IA
| Dificultad | Descripción |
|------------|-------------|
| Principiante | Para principiantes, la IA comete errores |
| Intermedio | Conciencia básica de ataque y defensa |
| Experto | Experto en estrategia y tácticas |

### Funciones Adicionales
- 🎵 Sonidos de movimiento, captura y aviso de jaque
- 📜 Registro de movimientos
- ↩️ Función de deshacer
- 🔄 Reiniciar

---

## Cómo Jugar

### Método 1: Abrir directamente
Haz doble clic en el archivo `index.html` y ábrelo en cualquier navegador moderno.

### Método 2: Servidor local
```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .

# PHP
php -S localhost:8080
```
Visita `http://localhost:8080`

---

## Stack Tecnológico

| Tecnología | Descripción |
|------------|-------------|
| HTML5 | Estructura semántica |
| CSS3 | Estilos del tablero, animaciones |
| JavaScript | Lógica del juego, IA, interacción |

- **Sin dependencias** - Implementación nativa pura
- **Responsive** - Compatible con escritorio y móvil
- **Accesibilidad** - Soporte de etiquetas ARIA

---

## Compatibilidad de Navegadores

| Navegador | Versión Soportada |
|-----------|-------------------|
| Chrome | 80+ |
| Firefox | 75+ |
| Safari | 13+ |
| Edge | 80+ |

---

## Estructura del Proyecto

```
chinese-chess/
├── index.html        # Página principal (contiene todo el código)
├── SPEC.md          # Especificaciones del proyecto
├── README.md         # Inglés
├── README_zh-CN.md   # Chino simplificado
├── README_ja.md      # Japonés
├── README_ko.md      # Coreano
├── README_es.md      # Español
├── LICENSE           # Licencia MIT
└── .gitignore        # Archivos ignorados por Git
```

---

## Desarrollo

### Ejecutar Pruebas
En la consola del navegador：
```javascript
runSelfTests()
```

---

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE).