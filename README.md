# API Restful NodeJS + postgresql

Para ejecutar la api en localhost se requiere:

- Tener instalado Nodejs, postgres, utilizar programa como (insomnia o postman) para ejecutar las url de la api.
- Guardar la carpeta de api.
- Importar la base de datos.

![image](https://user-images.githubusercontent.com/87329633/151293912-87f2e5ec-ae0c-49a6-880f-f43c08f2f093.png)



- Abrir una terminal y ejecutar el comando npm run dev ( arranca la api)
- Ejecutar las URLS : 


a. Consultar utilizando el metodo GET: http://localhost:4000/personas

![image](https://user-images.githubusercontent.com/87329633/151292350-c8c25e7e-503f-470a-a04e-c38ffa8f2194.png)

![image](https://user-images.githubusercontent.com/87329633/151292404-d50ad5a4-6542-479b-9890-d69884bbc08a.png)



b. Crear utilizando el metodo POST: http://localhost:4000/crearPersona

Nota: se envia datos por medio de un json.

![image](https://user-images.githubusercontent.com/87329633/151292493-ff3359b4-62a1-4f1b-85fd-24378871ce51.png)




C. Actualizar utilizando el metodo PUT : http://localhost:4000/personas/3

Nota: Se consulta las personas para visualizar datos


![image](https://user-images.githubusercontent.com/87329633/151292600-c6eeacc9-1154-4e15-a665-addbbfe66057.png)

Nota: se actualiza la información 

![image](https://user-images.githubusercontent.com/87329633/151292615-0f72e368-7b15-4c88-86b6-6ad02d3cf8e5.png)



D. Eliminar utilizando el metodo DELETE : http://localhost:4000/personas/3


![image](https://user-images.githubusercontent.com/87329633/151292741-45e091fe-bdc2-4efc-bc80-e80853c22aed.png)

