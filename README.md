## Mentoria_pred_dem_2023
### Título Mentoría
Potenciando la estrategia de negocios con Machine Learning: Práctica profesional en predicción de demanda con datos reales
### Mentor
Sebastián Gabriel Ormaechea.
 PhD en Ciencias Agropecuarias. 
 Especialización en Ciencia de datos e Investigación científica. 
 Actualmente trabaja en el área de Machine Learning de la empresa Ithreex Global. https://www.linkedin.com/in/ormaecheasg/
 Mail de contacto: sormaechea@ithreexglobal.com

### Integrantes
- Esequiel Armeria
- Rubén Alfredo Mendoza
- Guillermo Nicolás Laión 

### Descripción
En la era de inteligencia artificial, las organizaciones de diversos sectores se han visto obligadas a incorporar nuevas tecnologías en todas las áreas de su funcionamiento con el fin de mejorar sus procesos, elevar la calidad, aumentar su competitividad, proporcionar valor, satisfacer a sus clientes y ofrecer nuevas experiencias de compra. Un aspecto crucial para lograr una experiencia positiva del consumidor es la rapidez en la entrega de los productos adquiridos. En la actualidad, existen empresas innovadoras que utilizan la ciencia de datos para anticiparse a la distribución de un producto incluso antes de su compra, mediante la predicción de la demanda con cierto grado de certeza. Esto implica un cambio de paradigma hacia un modelo de producción "inteligente" que permita anticipar las ventas futuras y cubrir las necesidades de inventario, reduciendo así el tiempo de entrega y la optimización de los procesos de producción.
El conjunto de datos que emplearemos en este caso consiste en las ventas de productos de una empresa de pinturas en distintos países de la región durante los últimos años. El objetivo final de esta mentoría es poder predecir las ventas del próximo mes en diferentes países y zonas donde opera la compañía. Sin embargo, las prácticas realizadas en esta mentoría son aplicables a empresas de cualquier sector que deseen predecir la demanda.
Utilizaremos los conocimientos adquiridos en la diplomatura para recorrer todas las etapas de un proyecto de aprendizaje automático. En este sentido, estableceremos el marco de un problema de predicción de demanda, comprenderemos los datos y sus patrones temporales, aplicaremos modelos de aprendizaje automático y, finalmente, presentaremos los resultados obtenidos.
Trataremos de responder algunas de las siguientes preguntas:

¿Qué provincias demandan mayor cantidad de productos?
¿Qué localidades son las que demandan más variedad de productos?
¿Qué productos tienen una demanda estable a la largo del año y cuales tienen una demanda estacional?
¿Qué productos serían más vendidos el próximo mes en cada zona y país?
¿Cuánto de cada producto se vendería el próximo mes en cada zona y país?
¿Qué variables explican mejor la variación en la cantidad de productos demandados por una sucursal?


### Datos
El set de datos corresponde al registro de ventas que comercializa productos de pinturería en sudamérica. Contiene poco más 107.789 mil registros y 19 variables.
Variables


- Periodo: Identificador temporal
- Fecha: Fecha de venta
- NroDocPedido: Identificador del pedido
- PosPedido: Posición del pedido
- CodMaterial: Identificador del material
- Cantidad: Cantidad solicitada del producto. Los valores negativos representan devoluciones.
- CodGrupoArt: Identificador de grupo de artículos.
- GrupoArticulos: Nombre de cada grupo de artículos.
- codGrupoMaterial2: Identificador del grupo de materiales N°2
- codGrupoMaterial4: Identificador del grupo de materiales N°4
- codGrupoMaterial5: Identificador del grupo de materiales N°5
- Tipo_Precio: Tipificación de producto
- Departamento: Departamento de ubicación de la sucursal
- Localidad: Localidad de ubicación de la sucursal
- Provincia: Provincia de ubicación de la sucursal
- Pais: País de ubicación de la sucursal
- CodCliente_of: Identificador del cliente
- CodSucCliente_of: Identificador de la sucursal
- FechaPedido: Fecha de venta
