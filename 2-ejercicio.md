# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 
# COMPLETAR CON UNA CAPTURA DE PANTALLA LUEGO DE EJECUTAR EL ARCHIVO


<img width="868" height="434" alt="sonar (2)" src="https://github.com/user-attachments/assets/a5eabd5d-570d-4a79-b460-877a0af33dd8" />

  

# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube
<img width="659" height="685" alt="sonarlog" src="https://github.com/user-attachments/assets/aeb78312-ee93-433f-a83f-84b36633b28f" />
<img width="649" height="690" alt="sonar list" src="https://github.com/user-attachments/assets/daafd6ce-e1ed-4d12-8607-2ecf249a6bba" />

