# API Restful NodeJS + postgresql

Para ejecutar la api en localhost se requiere:

- Tener instalado Nodejs, postgres, utilizar programa como (insomnia o postman) para ejecutar las url de la api.
- Descarga la carpeta api_rest_nodejs.zip que se encuentra en el repositorio

![image](https://user-images.githubusercontent.com/87329633/151477626-ca9a55e9-9fd5-4bb3-9f14-be57a1f4519d.png)

- Copiar la carpeta api_rest_nodejs e Importar la base de datos que se encuentra dentro de la carpeta api_rest_nodejs con nombre api.

![image](https://user-images.githubusercontent.com/87329633/151477471-18bc1532-bef2-4905-909c-b590ae17eac8.png)


![image](https://user-images.githubusercontent.com/87329633/151293912-87f2e5ec-ae0c-49a6-880f-f43c08f2f093.png)



- Abrir una terminal y ejecutar el comando npm run dev ( arranca la api)
- Ejecutar las URLS : 


a. Consultar utilizando el metodo GET: http://localhost:4000/personas

![image](https://user-images.githubusercontent.com/87329633/151466405-0939568c-475a-48bc-8ee3-fe1ac146b5c8.png)



![image](https://user-images.githubusercontent.com/87329633/151466305-8438b3cc-75ef-41a9-88af-fcbc235253cc.png)




b. Crear utilizando el metodo POST: http://localhost:4000/personas/

Nota: se envia datos por medio de un json.

![image](https://user-images.githubusercontent.com/87329633/151466139-af960264-214e-492e-95ac-26851c076c61.png)





C. Actualizar utilizando el metodo PUT : http://localhost:4000/personas/3

Nota: Se consulta las personas para visualizar datos


![image](https://user-images.githubusercontent.com/87329633/151292600-c6eeacc9-1154-4e15-a665-addbbfe66057.png)

Nota: se actualiza la información 

![image](https://user-images.githubusercontent.com/87329633/151292615-0f72e368-7b15-4c88-86b6-6ad02d3cf8e5.png)



D. Eliminar utilizando el metodo DELETE : http://localhost:4000/personas/3


![image](https://user-images.githubusercontent.com/87329633/151292741-45e091fe-bdc2-4efc-bc80-e80853c22aed.png)

