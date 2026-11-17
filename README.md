# Mi Periódico Digital

* **Temática:** Actualidad, tecnología y cultura.
* **Autor/a:** [Tu Nombre y Apellidos]

## Preguntas teóricas sobre HTML y CSS

### 1. ¿Cuál es la diferencia entre un elemento de bloque y uno en línea?
* **Elementos de bloque (`block`):** Ocupan todo el ancho disponible de su contenedor y siempre empiezan en una nueva línea (ejemplos: `<div>`, `<p>`, `<h1>`).
* **Elementos en línea (`inline`):** Solo ocupan el espacio necesario para su contenido y no fuerzan un salto de línea, colocándose junto a otros elementos (ejemplos: `<span>`, `<a>`, `<strong>`).

### 2. ¿Qué diferencia existe entre class e id?
* **`id`:** Es un identificador único que solo se puede utilizar una vez por página para un elemento específico (en CSS se selecciona con `#`).
* **`class`:** Es una clase reutilizable que se puede aplicar a múltiples elementos para darles el mismo estilo (en CSS se selecciona con un punto `.` antes de su nombre).

### 3. ¿Qué diferencia hay entre margin y padding?
* **`padding` (relleno):** Es el espacio interior que hay entre el contenido de un elemento y su propio borde.
* **`margin` (margen):** Es el espacio exterior que separa el borde de ese elemento respecto a los demás elementos que lo rodean.

### 4. ¿Para qué sirve box-sizing: border-box?
Por defecto, al ancho (`width`) de una caja se le suman los bordes y el relleno, haciendo que ocupe más espacio del previsto. Al aplicar `box-sizing: border-box`, el navegador incluye el relleno y el borde **dentro** del ancho total establecido, lo que facilita mucho el diseño y el cálculo de las cajas.