# Blackjack Game - Vite Project

Un juego de Blackjack interactivo desarrollado con JavaScript vanilla y Vite, donde puedes jugar contra la computadora.

![Blackjack Game](https://img.shields.io/badge/Game-Blackjack-success)
![Vite](https://img.shields.io/badge/Vite-v7.1.7-646CFF?logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript)

## Descripción

Este proyecto es un juego completo de Blackjack (21) implementado con JavaScript moderno. El jugador compite contra la computadora en partidas emocionantes donde el objetivo es acercarse lo más posible a 21 puntos sin pasarse.

El proyecto forma parte del curso **JavaScript Moderno: Guía para dominar el lenguaje** creado por **Fernando Herrera**, disponible en Udemy.

## Características

- Juego de Blackjack completamente funcional
- Interfaz intuitiva con Bootstrap 5
- Sistema de puntuación en tiempo real
- Baraja completa con 52 cartas
- Animaciones y diseño responsivo
- Lógica de juego que simula las reglas reales del Blackjack
- Turno automático de la computadora

## Tecnologías Utilizadas

- **Vite** - Build tool y dev server
- **JavaScript ES6+** - Lógica del juego
- **Bootstrap 5.3.8** - Estilos y UI
- **Underscore.js** - Utilidades (shuffle de cartas)
- **HTML5** - Estructura
- **CSS3** - Estilos personalizados

## Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/jesusvelezx/blackjack-vite-project.git
```

2. Navega al directorio del proyecto:
```bash
cd blackjack-vite-project
```

3. Instala las dependencias:
```bash
npm install
```

4. Inicia el servidor de desarrollo:
```bash
npm run dev
```

5. Abre tu navegador en `http://localhost:5173`

## Cómo Jugar

1. Haz clic en **"Nuevo Juego"** para comenzar una nueva partida
2. Usa **"Pedir carta"** para solicitar una carta adicional
3. Usa **"Detener"** cuando estés satisfecho con tu puntuación
4. La computadora jugará automáticamente después de tu turno
5. Gana acercándote a 21 sin pasarte

## Reglas del Juego

- Las cartas numéricas (2-10) valen su valor nominal
- Las figuras (J, Q, K) valen 10 puntos
- El As vale 11 puntos
- Si te pasas de 21, pierdes automáticamente
- La computadora debe intentar igualar o superar tu puntuación

## Scripts Disponibles

```bash
npm run dev      # Inicia el servidor de desarrollo
npm run build    # Construye el proyecto para producción
npm run preview  # Previsualiza la build de producción
```

## Estructura del Proyecto

```
blackjack-vite-project/
├── assets/
│   └── cartas/          # Imágenes de las 52 cartas
├── public/
│   └── vite.svg
├── src/
│   ├── main.js          # Lógica principal del juego
│   ├── style.css        # Estilos personalizados
│   └── javascript.svg
├── index.html           # Archivo HTML principal
├── package.json
└── README.md
```

## Acerca del Curso

Este proyecto fue desarrollado como parte del curso:

**JavaScript Moderno: Guía para dominar el lenguaje**
Instructor: **Fernando Herrera**
Plataforma: Udemy
[Enlace al curso](https://www.udemy.com/share/102Bgj3@WUAEnP6cEWj2Tlb2bHvuQWVJY1m4NXaHjRLZAD19IRi8x6wBQ2fA3kBqoHTE8He1yQ==/)

## Autor

**Jesus Velez**
Email: jesus.27velez@gmail.com
GitHub: [@jesusvelezx](https://github.com/jesusvelezx)

## Licencia

Este proyecto es de código abierto y está disponible para fines educativos.

---

Desarrollado con JavaScript Moderno
