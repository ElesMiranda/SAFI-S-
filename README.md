#  Repositorio de Proyectos SAFIs - UAEMex

¡Bienvenidos al equipo de **SAFIs**! Este espacio está diseñado para centralizar las tareas unicamnete para ver quien chambea y quien no ;).

# Tarea resumen PDF

**Propulsión** [Teoria Sobre Motores Cohete de Propelente Solido](https://www.nakka-rocketry.net/articles/teoria_de_los_motores_cohete.pdf) 
**Aeroestructuras** [Fins for Rocket Stability](https://www.nakka-rocketry.net/fins.html)
---

##  Instrucciones de Entrega

Para mantener el orden del repositorio, todos los nuevos integrantes deben seguir estas reglas de contribución:

### 1. Estructura de Carpetas
No subas archivos sueltos a la raíz. Debes crear una carpeta con tu **Nombre Completo** siguiendo este formato:
`Carpeta del equipo/Nombre Completo _ area dentro del capitulo`

### 2. Contenido Requerido
Dentro de tu carpeta, debes incluir los archivos de **KiCad** de tu fuente de voltaje:
*   `*.kicad_sch` (Esquemático)
*   `*.kicad_pcb` (Diseño de placa)
*   `*.kicad_pro` (Archivo de proyecto)
*   **/Gerbers** (Carpeta con los archivos de fabricación)
*   **/PDF** (para la tarea de propulsión y Aeroestructuras)

### 3. Proceso de Subida (Git)
1- CLonar el repositorio con el siguinte comando:
```bash
git clone https://github.com/ElesMiranda/SAFI-S-.git
```
2- crea tu Carpeta

3- sube los cambios

```bash
git add .  

git commit -m "Entrega Fuente de Voltaje - [Tu Nombre]"

git push origin main
