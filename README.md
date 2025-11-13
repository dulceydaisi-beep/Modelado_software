🧾 MINISUPER – SISTEMA DE INVENTARIO 📋 Descripción

Aplicación de escritorio desarrollada en Java (Swing) con base de datos MySQL, que permite gestionar los productos, clientes, proveedores y ventas de un Mini Supermercado. Permite registrar, editar, eliminar productos, realizar ventas, generar reportes PDF y visualizar estadísticas con gráficos.

✨ Características

🖥️ Agregar, actualizar y eliminar productos.

📊 Control del inventario en tiempo real.

📈 Generación de reportes en formato PDF.

🔒 Autenticación de usuarios.

💾 Copia de seguridad y restauración de base de datos.

📦 Gestión de clientes y proveedores.

💰 Registro y listado de ventas con filtrado por fecha.

⚙️ Instalación Requisitos previos

☕ Java JDK 17 o superior

💻 IntelliJ IDEA (o NetBeans)

🛠️ XAMPP (para Apache + MySQL)

Configuración

Abrir XAMPP y ejecutar Apache y MySQL.

Crear una base de datos llamada ims.

Importar el archivo SQL con las tablas (productos, clientes, proveedores, ventas, usuarios).

En el código Java, verificar la conexión:

Connection conn = DriverManager.getConnection( "jdbc:mysql://localhost:3306/ims?useSSL=false&allowPublicKeyRetrieval=true&serverTimezone=UTC", "javauser", "12345");

🚀 Ejecución

Descargar el archivo .jar desde Google Drive.

Ejecutarlo con doble clic o desde terminal:

java -jar MiniSuper.jar

Iniciar sesión con:

Usuario: admin

Contraseña: 1234

📸 Capturas

Incluye capturas de:

Pantalla de inicio de sesión





<img width="482" height="430" alt="Captura de pantalla 2025-10-28 230606" src="https://github.com/user-attachments/assets/5d53bc10-6173-418f-aaed-7a7e16795791" />





Menu Principal





<img width="735" height="619" alt="Captura de pantalla 2025-10-28 231119" src="https://github.com/user-attachments/assets/bbab7ba9-6fc8-4c09-a0c8-04babeeeb005" />


Gestión de Productos

<img width="484" height="361" alt="Captura de pantalla 2025-10-28 235111" src="https://github.com/user-attachments/assets/d3881688-fc7f-4614-b007-7a584efbe4d6" />


Reporte PDF



<img width="871" height="485" alt="Captura de pantalla 2025-10-28 231743" src="https://github.com/user-attachments/assets/e8658843-c60a-40b7-a47b-93c48fbf5a8e" />






🧩 Tecnologías utilizadas

Java Swing – interfaz gráfica

MySQL – base de datos

Gson – manejo de JSON

iTextPDF – exportación de reportes

JFreeChart – gráficos estadísticos

IntelliJ IDEA – entorno de desarrollo

📦 Repositorio y descargas

📂 Repositorio en GitHub (podés reemplazarlo con el del MiniSuper) 📥 Descargar ejecutable (.jar) (pegá acá tu link de Drive)

👩‍💻 Desarrolladora

Flores Daisi Ivana y Humpiri Mariana Estudiante de Desarrollo de Software – Instituto Manuel Belgrano (Mendoza, Argentina) 📧 Email: dulceydaisi@gmail.com 🌐 GitHub: https://github.com/dulceydaisi-beep
