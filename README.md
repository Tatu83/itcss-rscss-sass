# ITCSS + RSCSS + SMACSS + SASS

- [ITCSS](https://www.creativebloq.com/web-design/manage-large-css-projects-itcss-101517528)
- [RSCSS](https://rscss.io/)
- [SMACSS](http://smacss.com/)
- [SASS](https://sass-lang.com/)

Se utiliza la arquitectura **ITCSS** para la organización del código CSS del proyecto. A esta arquitectura le aplicamos la metodología **RSCSS** para la escritura del código CSS, que nos proporciona una manera sencilla, clara y mantenible de redactar nuestros selectores. 

Para conseguir una unión perfecta entre Arqitectura y Metodología se llevan a cabo algunas modificaciones en los conceptos de ambas. De este modo conseguimos que empasten y puedan ir de la mano perfectamente.

Para la escritura del código CSS utilizaremos **SASS** para facilitar la modularidad, mantenibilidad y escalabilidad del código. En la carpeta **/scss/** está todo el código fuente que deberá ser compilado para ponerlo en producción en los archivos site.css o **site.min.css**.

Síentete libre de utilizar, mejorar y ampliar este proyecto, y por supuesto ... compártelo :)

# Prefijos (SMACSS)

Los prefijos en los selectores nos ayudarán a identificar mejor qué es cada cosa cuando estemos trabajando y tengamos múltiples archivos abiertos.

- **o-**: Objetos (elementos en RSCSS)
- **c-**: Componentes
- **l-**: Layouts
- **u-**: Utilities

Estos serían los prefijos básicos que tenemos que utilizar y aplicar como buena práctica a la hora de definir el nombre de nuestros selectores. Adicionalmente se pueden incluir otros prefijos que puedan ser de utilidad, como podrían ser los siguientes:

- **is-**, **has-**: Para definir selectores que aplican unas ciertas reglas de estilo como consecuencia de un determinado estado o condición.
- **js-**: Para definir que ese elemento es usado en Javascript para realizar alguna operación o interacción. Siempre que sea posible los selectores js- deberían ser usados únicamente en Javascript y por lo tanto no deberían tener reglas CSS en nuestros archivos .scss.

