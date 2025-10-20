Videojuego: Invasión Calavera

Asignatura: Graficación

Evaluación: Examen del Segundo Seguimiento

Fecha: 20 de Octubre de 2025

Integrantes del Equipo

Enrique Gomez Orta - 23200842

José David Martinez Badillo - 23200995

1. Contexto del Proyecto

Este proyecto se desarrolla como parte de la evaluación correspondiente al segundo seguimiento de la asignatura de Graficación. El propósito es aplicar los conocimientos teóricos y prácticos adquiridos en clase para la creación de una aplicación gráfica interactiva en dos dimensiones (2D).

El resultado es "Invasión Calavera", un videojuego web con temática de "Día de Muertos" que demuestra el uso de la API Canvas de HTML5 como motor de renderizado y la manipulación de objetos gráficos en tiempo real.

2. Objetivo

El objetivo principal de este examen es diseñar, desarrollar e implementar un videojuego 2D funcional, aplicando los conceptos fundamentales de la graficación por computadora, tales como:

Renderizado en 2D: Utilizar la API Canvas para dibujar (draw) y actualizar (update) objetos gráficos en un bucle de animación.

Transformaciones Geométricas: Implementar el movimiento (traslación) de múltiples objetos (calaveras) en pantalla, aplicando trayectorias aleatorias y variadas (lineales, diagonales, sinusoidales).

Interacción Usuario-Objeto: Gestionar eventos del mouse (click) para detectar colisiones entre el puntero y los objetos gráficos, permitiendo su eliminación.

Gestión de Escena: Administrar un conjunto de objetos, controlando su aparición, desaparición y comportamiento cíclico en el canvas.

Ambientación Gráfica: Integrar recursos visuales como sprites (imágenes de calaveras), fondos de escenario, y un cursor personalizado para crear una experiencia de usuario cohesiva y temática.

3. Justificación

La creación de un videojuego es una de las aplicaciones más completas para demostrar el dominio de la graficación. Este proyecto justifica la aplicación práctica de los siguientes conceptos:

Bucle de Animación (requestAnimationFrame): Es el corazón del proyecto. Se implementó un bucle de renderizado eficiente que limpia y redibuja el canvas en cada fotograma, creando la ilusión de movimiento fluido.

Manejo de Coordenadas y Estado: Cada calavera es un objeto con propiedades (posición x, y, velocidad speedX, speedY, imagen) que se actualizan en cada ciclo, demostrando la gestión del estado de múltiples elementos gráficos.

Interfaz Gráfica de Usuario (GUI): Se integraron elementos de HUD (Heads-Up Display) como el contador de puntuación y los botones de control (pausa, reinicio), que son componentes esenciales en cualquier aplicación gráfica.

Tecnologías Web como Plataforma Gráfica: Se eligió el entorno web (HTML, CSS, JavaScript) para demostrar la capacidad y versatilidad de estas herramientas para el desarrollo de aplicaciones gráficas, sin depender de software o librerías especializadas.

4. Operación del Videojuego

El juego está diseñado para ser simple e intuitivo:

Inicio Automático: Al abrir el archivo index.html, el juego y la música de fondo comienzan de inmediato.

Objetivo del Jugador: El objetivo es hacer clic en la mayor cantidad posible de calaveras que aparecen y se mueven por la pantalla.

Puntuación: Cada calavera eliminada correctamente suma un punto al marcador visible en la esquina superior izquierda.

Controles de Juego:

Botón de Pausa/Reanudar (⏸ / ▶): Detiene por completo la animación y el sonido del juego. Al presionarlo de nuevo, la partida continúa desde donde se quedó.

Botón de Reinicio (🔄): Restablece la puntuación a cero y comienza una nueva partida inmediatamente.

5. Conclusiones

El desarrollo de "Invasión Calavera" permitió consolidar de manera exitosa los conocimientos adquiridos en la asignatura de Graficación. Se logró implementar un motor de renderizado 2D básico desde cero, gestionando el ciclo de vida de los objetos, sus transformaciones y la interacción con el usuario.

El principal aprendizaje se centró en la lógica detrás del bucle de animación y la importancia de gestionar el estado de la aplicación (por ejemplo, la variable isPaused) para controlar el flujo del renderizado. El proyecto no solo cumple con los requisitos técnicos solicitados, sino que también sirve como una base sólida para explorar conceptos más avanzados de graficación en el futuro, como la física de partículas, shaders
