# [Login Pok茅mon Inc](https://elliotgaramendi.000webhostapp.com/app/login-pokemon-inc/) | [<img src="https://i.postimg.cc/dtPYcvbM/youtube.png" alt="YouTube" height="20px"/>](https://www.youtube.com/@elliotgaramendi) | [<img src="https://i.postimg.cc/5NBMxTJX/github.png" alt="GitHub" height="20px"/>](https://github.com/elliotgaramendi) | [<img src="https://i.postimg.cc/J7BLFtdc/linkedin.png" alt="Linkedin" height="20px"/>](https://www.linkedin.com/in/elliotgaramendi/) | [<img src="https://i.postimg.cc/sfJtqS4W/instagram.png" alt="Instagram" height="20px"/>](https://www.instagram.com/elliotgaramendi/)

[![login-pokemon-inc](https://i.postimg.cc/QtbMwpvS/login-pokemon-inc.png)](https://elliotgaramendi.000webhostapp.com/app/login-pokemon-inc/)

## 馃摐 Resumen 馃摐
Aplicaci贸n Web donde puedes iniciar sesi贸n con usuarios registrados. La aplicaci贸n emplea MySQL como motor de base de datos, PHP de lado del Backend y HTML, CSS, JS Y PHP de lado del Frontend.

## 馃搵 Requisitos 馃搵
- PHP 8.X
- MySQL 5.X
- Cliente Web Actualizado (Opera, Firefox, Chrome, etc.)

## 馃捇 Instalaci贸n 馃捇
- Archivos
  - Ubicarse en la carpeta dentro del servidor que contendr谩 la aplicaci贸n 
  - Abrir terminal de comandos
  - git clone https://github.com/elliotgaramendi/login-pokemon-inc || descargar zip
  - cd login-pokemon-inc || Ir desde el explorador de archivos
  - Abrir la aplicaci贸n en el editor de su preferencia y disfrutar

- Base de datos
  - Ir a su cliente de Base de Datos
  - Crear la tabla develop
  - Usar la base de datos creada
  - Importar el script develop.sql
    - /database

- Aplicaci贸n
  - Abrir un cliente web
  - Poner la url de su index principal (vista)
  - Usuarios por defecto de la base de datos
    - administrador
      - usuario: Elliot
      - clave: elliot
    - entrenador
      - usuario: Doky
      - clave: doky
    - entrenador
      - usuario: Chocolate
      - clave: chocolate
  
## 鉂? Posibles errores 鉂?
- Si tiene credenciales diferentes en su motor de base de datos, deber谩 configurar el script ubicado en /backend/models/conexion.php con su editor favorito.

## 馃懆鈥嶐煉? Tecnolog铆as usadas 馃懆鈥嶐煉?
| MYSQL | PHP | HTML | CSS | JavaScript | Bootstrap | SweetAler2 | Axios |
| --- | --- | --- | --- | --- | --- | --- | --- |
| <img src="https://d1.awsstatic.com/asset-repository/products/amazon-rds/1024px-MySQL.ff87215b43fd7292af172e2a5d9b844217262571.png" width="1000"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/2/27/PHP-logo.svg" width="1000"/> | <img src="https://i.postimg.cc/rF6WrLjr/html.png" width="1000"/> | <img src="https://i.postimg.cc/mgSDG9F2/css.png" width="1000"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png" width="1000"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Bootstrap_logo.svg/1200px-Bootstrap_logo.svg.png" width="1000px"/> | <img src="https://sweetalert2.github.io/images/SweetAlert2.png" width="1000px"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Axios_%28computer_library%29_logo.svg/1280px-Axios_%28computer_library%29_logo.svg.png" width="1000px"/> |

## 馃敆 Endpoints 馃敆

URL: https://elliotgaramendi.000webhostapp.com/app/login-pokemon-inc/backend/models/Login.php
URL: https://elliotgaramendi.000webhostapp.com/app/login-pokemon-inc/backend/models/Logout.php
### **Login**

> #### POST /backend/models/Login.php
> ##### Iniciar sesi贸n
**Nota:** La data debe ser enviada empleando la clase **FormData** de Javascript.
**Body**
```
{
  "usuario": "string",
  "clave": "string"
}
```

> #### GET /backend/models/Logout.php
> ##### Cerrar sesi贸n

## 馃 Redes sociales 馃
- 馃惌 YouTube: https://www.youtube.com/@elliotgaramendi 馃惌
- 馃惌 GitHub: https://github.com/elliotgaramendi 馃惌
- 馃惌 LinkedIn: https://www.linkedin.com/in/elliotgaramendi/ 馃惌
- 馃惌 Instagram: https://www.instagram.com/elliotgaramendi/ 馃惌