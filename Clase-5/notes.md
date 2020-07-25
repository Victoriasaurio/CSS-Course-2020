## BORDES
Se puede usar hasta 3 valores para cambiar la apariencia del borde: <br>

**1. Anchura** <br>
**2. Color** <br>

**3. Tipo de borde** <br>
***none*** <br>
sin borde (por defecto) <br><br>
***solid*** <br>
una línea <br><br>
***dotted*** <br>
línea de puntos <br><br>
***dashed*** <br>
línea discontinua <br><br>
***double*** <br>
doble línea <br><br>
***groove*** <br>
una línea estriada <br><br>
***ridge*** <br>
línea con crestas <br><br>
***inset*** <br>
inset global efecto 3D <br><br>
***outset*** <br>
outset global efecto 3D <br><br>

### TIPOS DE BORDES
![](images/tipos-bordes.png)

### PROPIEDADES DE LOS BORDES
    border-left: ;      borde-izq
    border-right: ;     borde-der
    border-bottom: ;    borde-inferior
    border-top: ;       borde-superior

    border-top-width: ; cambia-grosor
    border-top-color: ; cambia-color

    border-radius: ;    redondea-esquinas

    border-radius: 25px 55px 25px 55px;
    1. Superior izquierda
    2. Superior derecha
    3. Inferior derecha
    4. Inferior izquierda

### BORDES
![](images/bordes.png)

## SOMBREADO
2 tipos de sombra **sombras de caja** y **sombras de texto** <br>

### SOMBRAS DE CAJA
**box-shadow** se aplica a todo el bloque y tiene valores: <br>

    box-shadow: 6px 6px 0px black;

    box-shadow: 6px 6px 6px black;      tono-bajo

    box-shadow: 6px 6px 6px black inset; dentro del bloque

1. offset horizontal de la sombra <br>
2. offset vertical de la sombra <br>
3. bajada de tono <br>
4. color de la sombra <br>

### SOMBRA DEL TEXTO
**text-shadow** añade sombras a las letras del texto. Los valores trabajan igual que en `box-shadow`.

    text-shadow: 2px 2px 4px black;     sombra del texto

### SOMBRA CAJA Y SOMBRA TEXTO
![](images/sombra.png)