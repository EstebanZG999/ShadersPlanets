# ShadersPlanets

## Descripción
Este proyecto es una simulación de un sistema solar escrito en Rust, utilizando técnicas de gráficos por computadora y shaders personalizados para representar diferentes tipos de planetas y estrellas.

## Características
- **Gráficos 3D en tiempo real**: Renderizado de esferas que representan planetas y estrellas.
- **Shaders personalizados**: Implementación de múltiples shaders para simular superficies planetarias y efectos visuales únicos.
- **Interacción en tiempo real**: Permite rotar, escalar y mover los cuerpos celestes durante la ejecución.
- **Cambio dinámico de shaders**: Posibilidad de alternar entre diferentes shaders para visualizar distintos planetas y estrellas.

## Controles
### Movimiento:
- `W / S`: Mover hacia adelante y atrás.
- `A / D`: Mover hacia la izquierda y derecha.
- `Q / E`: Mover hacia arriba y abajo.

### Rotación:
- Flechas Izquierda/Derecha: Rotar alrededor del eje Y.
- Flechas Arriba/Abajo: Rotar alrededor del eje X.

### Escalado:
- `Z`: Aumentar escala.
- `X`: Disminuir escala.

### Cambio de Shaders:
- `1`: Estrella.
- `2`: Planeta volcánico.
- `3`: Cristal.
- `4`: Planeta con vórtices.
- `5`: Planeta con anillos.
- `6`: Planeta rocoso.
- `7`: Planeta terrestre.

### Salir:
- `Esc`: Cerrar la aplicación.

## Instalación
### Prerrequisitos
- **Rust y Cargo**: Asegúrese de tener instalados el compilador de Rust y la herramienta Cargo.
  - [Descarga e instalación](https://www.rust-lang.org/tools/install)

### Pasos de Instalación
1. Clonar el repositorio:
   ```sh
   git clone https://github.com/EstebanZG999/ShadersPlanets.git
   ```
2. Entrar al directorio del proyecto:
   ```sh
   cd ShadersPlanets
   ```
3. Compilar el proyecto:
      ```sh
   cargo run --relase
   ```

## Estructura: 
src/: Código fuente del proyecto.
main.rs: Punto de entrada de la aplicación.
framebuffer.rs: Manejo del framebuffer para renderizado.
vertex.rs: Definición de estructuras y operaciones para vértices.
fragment.rs: Implementación de shaders de fragmento.
shaders.rs: Shaders personalizados para efectos visuales.
obj.rs: Carga y procesamiento de modelos OBJ.
triangle.rs: Funciones para renderizar triángulos.
line.rs: Utilidades para dibujar líneas.
color.rs: Definiciones y operaciones con colores.
assets/: Recursos utilizados, como modelos y texturas.


## Planetas: 
![image](https://github.com/user-attachments/assets/2d45603a-5fce-48de-81b5-903a46a4e931)
![image](https://github.com/user-attachments/assets/4326f24a-f002-4744-974e-4190b36f3c6a)
![image](https://github.com/user-attachments/assets/f68a2a5d-3707-4fb2-aa38-68ad6edd955c)
![image](https://github.com/user-attachments/assets/b9c4ee42-cbcd-487d-a858-898217914631)
![image](https://github.com/user-attachments/assets/c22fc060-02f1-400a-b1b2-4c22fc70d00d)
![image](https://github.com/user-attachments/assets/d5f02897-288e-481c-9c1d-34ee93e98b51)
![image](https://github.com/user-attachments/assets/b76a189e-af36-4fe6-8df2-c3d0816f8b0c)
