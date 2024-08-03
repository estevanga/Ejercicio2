1. Ingresar a Postman
2. Crear una colección nueva Ejercicio2 
3. Crear un request POST con el endponint : https://petstore.swagger.io/v2/user, con esto se crea un nuevo usuario
4. En body tipo raw colocar el json
{
"id": 1,
"username": "user113",
"firstName": "firstName",
"lastName": "secondName",
"email": "email",
"password": "password1",
"phone": "0989442049",
"userStatus": 1
}
5. Ejecutar el endpoint al dar click boton Send
6. Crear un request para buscar el usuario creado GET https://petstore.swagger.io/v2/user/user113
7. Para actualizar el usuario crear un request PUT https://petstore.swagger.io/v2/user/user113
8. En body tipo raw colocar el json
{
"id": 1,
"username": "user113",
"firstName": "Actualizado",
"lastName": "secondName",
"email": "Actualizado@live.com",
"password": "password1",
"phone": "0989442049",
"userStatus": 1
}
9.Ejecutar el paso 6 para buscar el usuario actualizado
10. Crear un request DELETE : https://petstore.swagger.io/v2/user/user113, para eliminar el usuario creado.
