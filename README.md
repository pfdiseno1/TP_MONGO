<h1>BASE DE DATOS MODELO<h1>
<h2>Admintradore y Gestion de Productos, Usuarios y sus Categorías</h2>

<p>“Este proyecto permite administrar productos, usuarios y categorías. Puedes agregar, ver, actualizar y eliminar elementos, similar a un supermercado o cualquier otro comercio.”</p>

<h3>Que podes hacer con esto?<h3>
  
<p>Vas a poder administrar y gestionar usuarios y productos con sus distintas categorías, tanto en productos como administrar alcances y permisos de usuarios (administrador, vendedor, etc.)
 
<p>

<h2>Tecnologías Utilizadas:<h2>
  <br>
<p>	JavaScript (Node.js y Express)
    <br>

	TypeScript(Node.js y Express)
  <br>
	MongoDB 
  <br>
	Mongoose 
  <br>
	JsonWebToken 
  <br>
	bcrypt
  <br>
	dotenv</p>

<h2>Configuración de Proyecto:<h2>  
<p>
1)	Clonar repositorio en tu equipo local.
  <br>
2)	Instalar las dependencias del proyecto ejecutando npm install.
  <br>
3)	Configura las variables de entorno.
<br>
4)	Inicia el servidor ejecutando npm run dev.<p></p>
  <br>
<h3>Como Utilizarla:<h3>
<h4>o	Usuarios:<h4>
<p>	Método: POST (envio de la información)
	Ruta: api/usuarios/crearUsuario
  
o	Obtener Usuarios (con usuario logueado y administrador)
<br>
<h4>	Método GET:<h4>
<p>	Ruta: api/usuarios/obtenerUsuario
  
o	Actualizar Usuario (con usuario logueado)<p>
    <br>
<h4>	Método PUT:<h4>
<p>	Ruta: api/usuarios/modificarUsuario/:id<p>  
o	Eliminar Usuario por ID:<p>
    <br>
<h4>	Método: DELETE<h4>
<p>	Ruta: api/usuarios/borrarUsuario/:id<p>
  <br>

<h4>o	Iniciar Sesión:
  <br>
	Método: POST<h4>
  <br>
<p>	Ruta: api/usuarios/validarUsuario
  
  	Proporcionar email y password<p>
      <br>

  
o	Productos:
<br>

o	Crear Producto
<br>
	Método: POST (envio de la información)
<br>
	Ruta: api/productos/crearProducto
<br>

o	Obtener Todos los Productos
<br>
	Método GET: 
<br>

	Ruta: api/productos/obtenerProductos
<br>
o	Obtener Producto por Nombre
<br>

	Método GET: 
<br>
	Ruta: api/productos/buscarProductos/:nombre
<br>

o	Eliminar Producto por ID:
<br>
	Método: DELETE
<br>
	Ruta: api/productos/borrarProducto/:id
<br>

o	Actualizar Producto por ID:
<br>
	Metodo: PUT
<br>
	Ruta: api/productos/modificarProducto/:id
<br><br>

o	Categorías:
<br>
o	Obtener Todas las Categorías
<br>

	Método: GET
<br>
	Ruta: api/ categorias /obtenerCategorias
<br>

o	Crear Categoria
<br>
	Método GET: 
<br>
	Ruta: api/ categorias /obtenerCategoria
<br>

o	Modificar Categoria
<br>

	Método PUT 
<br>
	Ruta: api/categorias/modificarCategoria/:id
<br>

o	Eliminar Categoria
<br>

	Método: POST
<br>
	Ruta: api/ categorias /borrarCategoria /:id
<br>


 

