# documentacion tecnica

## descripcion

este proyecto consiste en una tarjeta de presentacion digital creada usando html5 y etiquetas semanticas

## decisiones semanticas

header se utilizo para el encabezado principal con el nombre  
nav contiene el menu de navegacion  
main agrupa el contenido principal de la pagina  
section divide la informacion en partes como sobre mi habilidades y contacto  
article se uso para separar informacion dentro de habilidades  
footer contiene informacion final de la pagina  
address muestra la informacion de contacto

## arbol dom

html  
 ├── head  
 └── body  
      ├── header  
      ├── nav  
      ├── main  
      │    ├── section  
      │    ├── section  
      │    │     ├── article  
      │    │     └── article  
      │    └── section  
      └── footer