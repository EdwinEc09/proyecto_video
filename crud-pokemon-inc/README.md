# [CRUD Pok茅mon Inc](https://elliotgaramendi.000webhostapp.com/app/crud-pokemon-inc/frontend/) | [<img src="https://i.postimg.cc/dtPYcvbM/youtube.png" alt="YouTube" height="20px"/>](https://www.youtube.com/@elliotgaramendi) | [<img src="https://i.postimg.cc/5NBMxTJX/github.png" alt="GitHub" height="20px"/>](https://github.com/elliotgaramendi) | [<img src="https://i.postimg.cc/J7BLFtdc/linkedin.png" alt="Linkedin" height="20px"/>](https://www.linkedin.com/in/elliotgaramendi/) | [<img src="https://i.postimg.cc/sfJtqS4W/instagram.png" alt="Instagram" height="20px"/>](https://www.instagram.com/elliotgaramendi/)

[![CRUD Pok茅mon Inc](https://i.postimg.cc/pdVrDSsh/crud-pokemon-inc.png)](https://elliotgaramendi.000webhostapp.com/app/crud-pokemon-inc/frontend/)

## 馃摐 Resumen 馃摐
Aplicaci贸n Web donde puedes administrar usuarios mediante un CRUD. La aplicaci贸n emplea MySQL como motor de base de datos, PHP de lado del Backend y PHP de lado del Frontend.

## 馃搵 Requisitos 馃搵
- PHP 8.X
- MySQL 5.X
- Cliente Web (Opera, Firefox, Chrome, etc.)

## 馃捇 Instalaci贸n 馃捇
- Archivos
  - Ubicarse en la carpeta dentro del servidor que contendr谩 la aplicaci贸n 
  - Abrir terminal de comandos
  - git clone https://github.com/elliotgaramendi/crud-pokemon-inc.git || descargar y copiar zip
  - cd crud-pokemon-inc || Ir desde el explorador de archivos
  - Abrir la aplicaci贸n en el editor de su preferencia
  - Editar la variable $url de la l铆nea 4 de /frontend/index.php y l铆nea 6 de /frontend/views/editar.php a una ruta que coincida con el recurso /backend/models/usuarios.php en su servidor

- Base de datos
  - Ir a su cliente de Base de Datos
  - Crear la tabla develop
  - Usar la base de datos creada
  - Importar el script develop.sql
    - /database 

- Aplicaci贸n
  - Abrir un cliente web
  - Poner la url de su index principal (vista) del frontend
  - Disfrutar
  
## 鉂? Posibles errores 鉂?
- Si tiene credenciales diferentes en su motor de base de datos, deber谩 configurar el script ubicado en /backend/models/Conexion.php con su editor favorito.

## 馃懆鈥嶐煉? Tecnolog铆as usadas 馃懆鈥嶐煉?
| MYSQL | PHP | Bootstrap |
| --- | --- |--- |
| <img src="https://d1.awsstatic.com/asset-repository/products/amazon-rds/1024px-MySQL.ff87215b43fd7292af172e2a5d9b844217262571.png" width="1000"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/2/27/PHP-logo.svg" width="1000"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Bootstrap_logo.svg/1200px-Bootstrap_logo.svg.png" width="1000px"/> |

## 馃敆 Endpoints 馃敆

URL: https://elliotgaramendi.000webhostapp.com/app/crud-pokemon-inc/backend/models/usuarios.php
### **usuarios**

> #### $_REQUEST['httpMethods'] == POST /backend/models/usuarios.php
> ##### Agrega un nuevo registro
**Nota:** Si emplea JavaScript desde el Frontend la data debe ser enviada empleando la clase **FormData**.

**Body**
```
{
  "usuario": "string",
  "clave": "string",
  "idRol": 0
}
```

> #### $_REQUEST['httpMethods'] == GET /backend/models/usuarios.php
> ##### Lee los registros

> #### $_REQUEST['httpMethods'] == GET /backend/models/usuarios.php
> ##### Lee un registro

**Body**
```
{
  "id": 0
}
```

> #### $_REQUEST['httpMethods'] == PUT /backend/models/usuarios.php
> ##### Actualiza un registro

**Body**
```
{
  "id": 0,
  "usuario": "string",
  "clave": "string",
  "idRol": 0
}
```

> #### $_REQUEST['httpMethods'] == DELETE /backend/models/usuarios.php
> ##### Elimina un registro

**Body**
```
{
  "id": 0
}
```

## 馃 Redes sociales 馃
- 馃惌 YouTube: https://www.youtube.com/@elliotgaramendi 馃惌
- 馃惌 GitHub: https://github.com/elliotgaramendi 馃惌
- 馃惌 LinkedIn: https://www.linkedin.com/in/elliotgaramendi/ 馃惌
- 馃惌 Instagram: https://www.instagram.com/elliotgaramendi/ 馃惌
