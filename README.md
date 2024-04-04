# diagrama_er_tienda
Diseña un diagrama ER para una tienda en línea con las siguientes entidades/tablas


Diseño de un diagrama ER
Diseña un diagrama ER para una tienda en línea con las siguientes entidades/tablas

Cliente:
ID de cliente (clave primaria)
Nombre
Dirección
Correo electrónico
Producto:
ID de producto (clave primaria)
Nombre
Precio
Descripción
Categoría_ID (clave foránea)
Proveedor_ID (clave foránea)
Orden:
ID de orden (clave primaria)
Fecha de orden
Cliente_ID (clave foránea)
Categoría:
ID de categoría (clave primaria)
Nombre
Proveedor:
ID de proveedor (clave primaria)
Nombre
Dirección
Correo electrónico
Reseña:
ID de reseña (clave primaria)
Cliente_ID (clave foránea)
Producto_ID (clave foránea)
Puntuación
Comentario
Nota que estas tienen las siguientes relaciones:

Una orden está asociada a un cliente: relación "uno a muchos" (clave foránea: Cliente_ID).
Un producto pertenece a una categoría: relación "uno a muchos" (clave foránea: Categoría_ID).
Un producto puede tener un proveedor: relación "uno a muchos" (clave foránea: Proveedor_ID).
Un cliente puede dejar múltiples reseñas: relación "uno a muchos" (claves foráneas: Cliente_ID y Producto_ID).
