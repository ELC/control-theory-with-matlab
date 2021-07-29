# [Teoría de Control con Matlab](https://elc.github.io/control)
Este es un libro de código abierto basado en Jupyter sobre cómo iniciarse en la teoría de control con Matlab
## Contenido

* [Capítulo 1: Transformada de Laplace](https://elc.github.io/control-theory-with-matlab/chapters/ELC01_Transformada_de_Laplace.html)
* [Capítulo 2: Función de Transferencia](https://elc.github.io/control-theory-with-matlab/chapters/ELC02_Funcion_de_transferencia.html)
* [Capítulo 3: Sistemas de Primer Orden](https://elc.github.io/control-theory-with-matlab/chapters/ELC03_Sistemas_Primer_Orden.html)
* [Capítulo 4: Sistemas de Segundo Orden](https://elc.github.io/control-theory-with-matlab/chapters/ELC04_Sistemas_Segundo_Orden.html)
* [Capítulo 5: Root Locus](https://elc.github.io/control-theory-with-matlab/chapters/ELC05_Root_Locus.html)
* [Capítulo 6: Controladores](https://elc.github.io/control-theory-with-matlab/chapters/ELC06_Controladores.html)
* [Capítulo 7: Sintonización](https://elc.github.io/control-theory-with-matlab/chapters/ELC07_Sintonizaci%C3%B3n.html)
* [Capítulo 8: Bode](https://elc.github.io/control-theory-with-matlab/chapters/ELC08_Bode.html)
* [Capítulo 9: Nyquist](https://elc.github.io/control-theory-with-matlab/chapters/ELC09_Nyquist.html)

Los siguientes son temas que no están cubiertos en ninguno de los capítulos:

- Reducción de bloques (Real y Simbólica)
- Arreglo de Routh
- Compensadores (Lag, Lead, Notch)

---
## Como leer el libro

El libro se puede leer de varias maneras diferentes, empezando por la más recomendada a la menos recomendada: 

1. La mejor manera es leer el libro online en el navegador, teniendo Matlab abierto y copiando y pegando el código de lo que sea relevante. Todo lo referido a Simulink se ilustra paso a paso con capturas de pantalla. Los contenidos se actualizan de forma sincronizada a medida que se suben cambios en este repositorio.

2. Otra posibilidad es clonar el repositorio para descargar los archivos .ipynb en tu máquina local. Si tienes Jupyter instalado, puedes ver los capítulos en tu navegador *además* de editar y ejecutar el código proporcionado (y probar algunas preguntas de práctica). Esta es la opción que más control da al usuario, pero requiere seguir pasos adicionales: 
    - Jupyter es un requisito para ver los archivos ipynb. Se puede descargar [aquí](http://jupyter.org/).
    - Además, necesitarás tener Matlab instalado ya que el código está escrito en ese lenguaje. Alternativamente podría usarse Octave como alternativa gratuita pero no se realizaron pruebas de compatibilidad
    - Es necesario tener instalado el kernel de matbal como se detalla en la [documentación de matlab_kernel](https://github.com/Calysto/matlab_kernel).
 
3. Los PDF son el último método recomendado para leer el libro, ya que los PDF son estáticos y no interactivos. Si se desean PDFs, se pueden crear dinámicamente utilizando la utilidad [nbconvert](https://github.com/jupyter/nbconvert).

---
## Cómo contribuir

### ¿Con qué se puede contribuir?

- La lista actual de capítulos no está finalizada. Si ves algo que falta, no dudes en empezar por ahí. 
- Limpiar el código de Matlab según buenas prácticas
- Dar mejores explicaciones
- Errores de ortografía/gramática
- Sugerencias
- Contribuir a los estilos de Jupyter notebook
- Traducciones

### Commits

- Todos los commits son bienvenidos, incluso si son menores ;)
- Si no estás familiarizado con Github, puedes enviarme tus contribuciones al correo electrónico que aparece a continuación.


---
## Frequently Asked Questions (FAQ)

### 1. Why use an external tool like Jupyter instead of the native Matlab Live Editor?

Jupyter provides useful advantages over the Live Editor:
1. It can be easily integrated in source control, because it json.
1. It is not version dependent, meaning if it can be then migrated to any Matlab Version.
1. In Live Editor the execution is "per section" whereas in Jupyter is "per cell", providing faster output in Jupyter.
1. Performance of Live Editor notebooks with a good amount of LaTeX is poor while in Jupyter it is managable.

On the other hand, using Jupyter has drawbacks too:
1. There is no built-in help, one has to use the Matlab site or the Matlab software.
1. Interactivity options for plots (panning, zoom, etc.) are limited.
1. There is currently limited support for Matlab Apps such as Control System Designer.
1. Symbolic Expressions are not natively print using LaTeX typical fonts.
1. There are services such as NBviewer that allow the rendering of the notebook online.
1. Transparent integration with HTML in cells to improve User Experience

All things considered, the advantages of using Jupyter overcome its drawbacks by far and therefore it was chosen as the go-to tool.

### 2. Can I use this material in my class/course?

The material is free to use for public and/or non-commercial uses, however, I would like to get notify if you do so. Knowing other people is using the material motivates to improve it. You can let me know by using the contact information in the bottom section.

For commercial use, please contact first.

### 3. Can I request some changes in the material?

Suggestions and recommendations are welcome, please visit the Contributing section above.

### 4. I found a typo/error, how do I report it?

Same answer as 3.

### 5. I would like to have a translation to X language of this material, how can I get it?

Please send an email to get notify of translations. 

At the moment there is English to Spanish Translation

### 6. How can I use this in Matlab?

Matlab does not provide a built-in Jupyter inport function, however all code cells are copy/paste friendly. You can paste them in any .m file and it should work out of the box.

### 6. I cannot execute the Notebook because of X error?

For execution problems, please refer to the [Matlab Kernel Developers](https://github.com/Calysto/matlab_kernel)

---
## Contact
Contact the main author, Ezequiel Leonardo Castaño at castanoezequielleonardo *at* gmail.com

---
## Reconocimientos

This format was heavily inspired by the [Bayesian Methods for Hackers by Cam Davidson-Pilon](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
