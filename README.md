# unida1
1.1 Evolucion de la graficacion por computadoras

La graficación por computadora es una rama de la informática que se encarga de crear y manipular imágenes usando computadoras, y su historia está directamente relacionada con el desarrollo tecnológico. Sus orígenes se remontan a las décadas de 1950 y 1960, cuando las computadoras solo podían mostrar puntos y líneas simples, principalmente con fines científicos y militares. Un avance fundamental ocurrió en 1963, cuando Ivan Sutherland desarrolló Sketchpad, el primer sistema interactivo de dibujo por computadora, considerado el punto de partida de la graficación moderna y del diseño asistido por computadora. Durante los años setenta se introdujeron los monitores raster basados en píxeles y se crearon algoritmos matemáticos para dibujar líneas, curvas y figuras, lo que permitió que los gráficos comenzaran a usarse en videojuegos y aplicaciones industriales.

En la década de 1980, con la llegada de las computadoras personales, la graficación por computadora se consolidó gracias a la aparición de las interfaces gráficas y al desarrollo de modelos para representar objetos en dos y tres dimensiones, así como técnicas de iluminación y sombreado que mejoraron el realismo de las imágenes. Empresas dedicadas a la animación digital, como Pixar, demostraron que era posible crear películas completas utilizando gráficos generados por computadora. En los años noventa surgieron las tarjetas gráficas o GPU, que hicieron posible el procesamiento acelerado de imágenes y el renderizado en tiempo real, lo que impulsó enormemente a los videojuegos y al cine digital. Además, se estandarizaron herramientas de programación gráfica como OpenGL y las librerías gráficas de Microsoft, facilitando el desarrollo de aplicaciones visuales complejas.

En el siglo XXI, la graficación por computadora ha alcanzado altos niveles de realismo gracias al uso de sombreadores avanzados, simulación física y técnicas como el ray tracing. Actualmente, se combina con inteligencia artificial, realidad virtual y realidad aumentada, lo que permite crear entornos interactivos, simulaciones médicas, animaciones cinematográficas y mundos virtuales cada vez más detallados. En resumen, la evolución de la graficación por computadora ha pasado de simples líneas y puntos a imágenes tridimensionales realistas y entornos virtuales, convirtiéndose en una herramienta esencial para la ciencia, la industria, el entretenimiento y la educación.

1.2 Areas de aplicacion 

Las áreas de aplicación de la graficación por computadora abarcan muchos campos del conocimiento y de la vida cotidiana, ya que permite representar información visual de forma clara, realista e interactiva. Una de las principales áreas es el entretenimiento, donde se utiliza en videojuegos, animación digital y cine para crear personajes, escenarios y efectos especiales. También es fundamental en la ingeniería y arquitectura, ya que permite el diseño y modelado de estructuras, máquinas y edificios mediante programas CAD, facilitando la visualización y detección de errores antes de construirlos.

En el ámbito de la medicina, la graficación se usa para visualizar órganos y tejidos a partir de estudios como tomografías y resonancias, así como para simular cirugías y entrenar personal médico. En la educación, se emplea para crear simulaciones, modelos 3D y material interactivo que ayuda a comprender mejor conceptos abstractos de física, química o biología. Otra área importante es la ciencia y la investigación, donde se representan datos complejos en gráficos, mapas y modelos visuales que permiten analizar fenómenos naturales, climáticos o astronómicos.

1.3 Aspectos matematicos de la graficacion

Los aspectos matemáticos de la graficación por computadora son fundamentales, ya que las imágenes que vemos en pantalla se construyen a partir de modelos matemáticos que describen formas, posiciones, colores y movimientos. Uno de los pilares es la geometría, especialmente la geometría analítica y la geometría espacial, que se usan para representar puntos, líneas, polígonos y objetos tridimensionales mediante coordenadas en sistemas 2D y 3D. Gracias a esta, se pueden definir figuras usando ecuaciones y transformarlas mediante operaciones como traslación, rotación y escalamiento.

Otro aspecto clave es el álgebra lineal, en particular el uso de vectores y matrices, que permiten realizar transformaciones geométricas de forma eficiente. Mediante matrices se implementan cambios de perspectiva, proyecciones ortogonales y proyecciones en perspectiva, lo que hace posible simular cómo se vería un objeto desde distintos puntos de vista. También interviene el cálculo diferencial e integral, sobre todo para describir curvas y superficies suaves, como las curvas de Bézier y las superficies B-spline, además de para modelar movimientos, aceleraciones y trayectorias en animaciones.

La trigonometría es esencial para calcular ángulos, direcciones y longitudes, especialmente en rotaciones y en la simulación de cámaras y luces. Por otro lado, la teoría del color y modelos matemáticos de iluminación utilizan ecuaciones para representar cómo la luz interactúa con las superficies, considerando reflexión, refracción y sombras. A esto se suma la estadística y probabilidad, que se emplean en técnicas como el muestreo aleatorio del ray tracing y en la generación de texturas y efectos naturales como humo, nubes o fuego.

1.4 Modelos del color: RBG, CMY, HSV y HSL.

Los modelos de color son sistemas matemáticos que permiten representar los colores de manera numérica para su uso en pantallas, impresión y procesamiento digital de imágenes. Cada modelo organiza los colores de forma distinta según su finalidad.
El modelo RGB (Red, Green, Blue) se basa en la mezcla aditiva de luz. Utiliza tres componentes: rojo, verde y azul, cuyos valores suelen ir de 0 a 255. Al combinar estas intensidades se obtienen todos los colores visibles en pantallas como monitores, televisores y celulares. Por ejemplo, (255, 0, 0) representa rojo puro y (255, 255, 255) representa blanco. Este modelo es el más usado en sistemas digitales y gráficos por computadora porque está directamente relacionado con el funcionamiento físico de los dispositivos de visualización.
El modelo CMY (Cyan, Magenta, Yellow) se basa en la mezcla sustractiva de color y es el complemento del modelo RGB. Se utiliza principalmente en impresión. En este modelo, los colores se forman al absorber ciertas longitudes de onda de la luz blanca: el cian absorbe el rojo, el magenta absorbe el verde y el amarillo absorbe el azul. Al combinar los tres se obtiene un color cercano al negro. En la práctica, se amplía a CMYK (agregando negro) para mejorar la calidad y el contraste en impresoras.

El modelo HSV (Hue, Saturation, Value) organiza los colores de forma más cercana a la percepción humana. El matiz (Hue) representa el tipo de color (rojo, verde, azul, etc.) y se mide en grados de 0 a 360. La saturación indica qué tan puro o intenso es el color, y el valor representa el brillo. Este modelo es muy útil en edición de imágenes y gráficos, ya que facilita seleccionar colores según su tono y luminosidad de manera intuitiva.
El modelo HSL (Hue, Saturation, Lightness) es similar al HSV, pero en lugar de valor utiliza luminosidad (Lightness), que indica qué tan claro u oscuro es un color en relación con el blanco y el negro. En HSL, un color con luminosidad baja se acerca al negro y con luminosidad alta se acerca al blanco. Este modelo se emplea mucho en diseño gráfico y diseño web porque permite modificar fácilmente la claridad y la intensidad del color sin cambiar su matiz.

1.5 Representación y trazo de líneas y polígonos

Como realizar la practica de un poligono en bleander

Abre Blender y elimina el cubo inicial seleccionándolo y presionando la tecla X, luego elige Delete.
Presiona Shift + A, ve a Mesh y selecciona Plane para crear un polígono básico.
Presiona Tab para entrar en modo edición.
Usa las teclas 1, 2 y 3 para cambiar entre selección de vértices, aristas y caras.
Puedes mover los vértices con la tecla G, escalar con S y rotar con R para modificar la forma del polígon
<img width="1508" height="848" alt="Captura de pantalla 2026-02-26 165417" src="https://github.com/user-attachments/assets/ef19dd06-4088-4bb0-ac19-2b52307f6fbf" />

Como realizar una flor de vida 

Abre Blender y elimina el cubo inicial con la tecla X y selecciona Delete. Luego presiona Shift + A, ve a Mesh y selecciona Circle. En la parte inferior izquierda elige una cantidad alta de vértices, por ejemplo 64, para que el círculo sea suave. Presiona Tab para entrar en modo edición y asegúrate de estar viendo desde arriba con la tecla 7 del teclado numérico.
Ahora duplica el círculo con Shift + D y muévelo con la tecla G sobre el eje X hasta que su borde toque el centro del primer círculo. Ese será tu segundo círculo. Repite este proceso duplicando y moviendo el círculo alrededor del primero, formando un anillo de seis círculos iguales. Debes colocarlos como si fueran pétalos alrededor del círculo central.
Después crea un segundo anillo de círculos. Duplica los círculos del primer anillo y muévelos un poco más hacia afuera, siguiendo el mismo patrón circular. Debes mantener siempre la misma distancia entre centros para que el diseño sea simétrico. Con esto se forma el patrón clásico de la Flor de la Vida.

1.6 Procesamientos de mapas de bits

El procesamiento de mapas de bits (bitmap processing) es el conjunto de técnicas utilizadas para manipular imágenes digitales formadas por píxeles, donde cada píxel almacena un valor de color. A diferencia de los gráficos vectoriales, que se describen mediante ecuaciones matemáticas, los mapas de bits representan la imagen como una matriz de puntos, por lo que su calidad depende directamente de la resolución.

Una parte fundamental del procesamiento es la lectura y representación de la imagen en memoria, donde se organiza como una matriz bidimensional de píxeles con valores asociados a un modelo de color (por ejemplo, RGB o escala de grises). Sobre esta estructura se aplican operaciones básicas como el ajuste de brillo y contraste, que se logra modificando los valores de intensidad de cada píxel, y la conversión de color, por ejemplo de una imagen RGB a escala de grises.

Otro aspecto importante es la aplicación de filtros, que consisten en recorrer la imagen píxel por píxel y calcular nuevos valores a partir de los vecinos cercanos. Entre los filtros más comunes están el suavizado (para reducir ruido), el realce de bordes (para resaltar contornos) y el desenfoque. Estas operaciones suelen implementarse mediante convoluciones con matrices pequeñas llamadas máscaras o kernels.

El procesamiento de mapas de bits también incluye técnicas de transformación geométrica, como escalamiento, rotación y traslación de imágenes. Estas transformaciones requieren interpolación, ya que los nuevos píxeles no siempre coinciden exactamente con los originales. Además, se utilizan métodos de compresión para reducir el tamaño de los archivos de imagen, ya sea sin pérdida (como en formatos PNG) o con pérdida (como JPEG).


Blibliografias

Foley, J. D., van Dam, A., Feiner, S. K., & Hughes, J. F. (1996). Computer graphics: Principles and practice (2nd ed.). Addison-Wesley.

Hearn, D., & Baker, M. P. (2011). Computer graphics with OpenGL (4th ed.). Pearson.

Shirley, P., Ashikhmin, M., Marschner, S., & Ramamoorthi, R. (2009). Fundamentals of computer graphics (3rd ed.). A K Peters.

Gonzalez, R. C., & Woods, R. E. (2018). Digital image processing (4th ed.). Pearson.

Angel, E., & Shreiner, D. (2015). Interactive computer graphics: A top-down approach with WebGL (7th ed.). Pearson.

Burger, W., & Burge, M. J. (2016). Digital image processing: An algorithmic introduction using Java (2nd ed.). Springer.

Poynton, C. (2012). Digital video and HD: Algorithms and interfaces (2nd ed.). Morgan Kaufmann.

Joblove, G. H., & Greenberg, D. (1978). Color spaces for computer graphics. ACM SIGGRAPH Computer Graphics, 12(3), 20–25.
