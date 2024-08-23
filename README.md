<h1 align="center">ApiRest usando spring boot 3 para el registro de medicos y consultas</h1>

<h2 align="center"><img src="https://github.com/user-attachments/assets/8b624678-f8ee-4b88-96cb-06d382b06193" width="400"></h2>

<h3 align="center">En este proyecto, desarrollé una ApiRest que se enfoca en el registro y consultas del personal medico y citas en una clinica, la api esta documentada usando spring boot 3 y tambien cuenta con autenticacion usando JWT 
</h3>
<br>
  <div align="center"><img src="https://github.com/user-attachments/assets/d51f3e7c-4f36-4dc3-b35b-35db6461cea8" width="550"></div><br><br>
  

## :hammer: Funcionalidades del proyecto<br>
- <h3>Funcionalidad 1</h3>
  Autenticacion con JSON Web Tokens(JWT)<br><br>
  Peticion HTTP post:<br>
  <div align="center"><img src="https://github.com/user-attachments/assets/825e98f9-a45b-4661-aa23-d7d67b1bfea6" width="600"></div><br><br>
  Response<br>
  <div align="center"><img src="https://github.com/user-attachments/assets/78fed4d2-ee13-4d20-8f24-04623200eb48" width="600"></div><br><br>
  Para usar los otros metodos debes agregar el JWT del Response en el boton AUTHORIZE<br>
  <div align="center">
    <img src="https://github.com/user-attachments/assets/d00a6ce1-22b3-41cc-9a1d-8814f0d44c02" width="600"></div><br><br>



- <h3>Funcionalidad 2</h3>
    conexion con base de datos Mysql y persistencia de datos como Medicos Pacientes y Citas<br><br>
     Peticion Registro Medico HTTP post:<br>
      <div align="center"><img src="https://github.com/user-attachments/assets/0cd8df1a-7c70-438b-8a9c-6d8e70d31b02" width="600"></div><br><br>
     Response:<br>
     <div align="center"><img src="https://github.com/user-attachments/assets/24316f6e-798e-4825-ab53-328c4dc33545" width="600"></div><br><br>
     Peticion Listar Medicos HTTP get:<br>
      <div align="center"><img src="https://github.com/user-attachments/assets/4647dae0-a6db-4741-804f-a69d4900aae0" width="600"></div><br><br>
      Response:<br>
      <div align="center"><img src="https://github.com/user-attachments/assets/a6471002-7e97-4b57-9150-1696c9892e51" width="600"></div><br><br>
       Peticion Editar Medico HTTP put:<br>
      <div align="center"><img src="https://github.com/user-attachments/assets/4c2b2aa8-c162-4199-82cf-3a02b979fbe7" width="600"></div><br><br>
      Response:<br>
      <div align="center"><img src="https://github.com/user-attachments/assets/85936980-4e50-4736-b8d6-875cbe0d8179" width="600"></div><br><br>
      Peticion Delete Medico HTTP delete:<br>
      <div align="center"><img src="https://github.com/user-attachments/assets/59bdc9e9-cea2-40a1-9c38-0d416afc430c" width="600"></div><br><br>
      Response:<br>
      <div align="center"><img src="https://github.com/user-attachments/assets/990fca4c-e5e7-4528-8c1d-309cd1c4fae1" width="600"></div><br><br>

- <h3>Funcionalidad 3</h3>
      Migrations con flyway 


## 📁 Acceso al proyecto 🛠️
Clonar el repositorio y ejecutar el "APiApplication".
nota: Recuerda editar el archivo "aplications.properties" con tus credenciales de la base de datos Mysql


## :hammer: Tecnologías utilizadas
- Java 17
- Spring boot 3
- Lombook
- Flyway
- Swagger UI
- Insomnia
- Postman
- Mysql
## Autores
<div align="center">
  <img src="https://avatars.githubusercontent.com/u/133101799?s=400&u=e9b08cc380e815cf4f929a3f30cb47979d4164f1&v=4" width="115"><br><sub>Ariel Armel Yance Orozco</sub>
</div>
