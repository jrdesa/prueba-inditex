# prueba-inditex
Servicio de precios
git clone prices-sarvice de main
git fetch dentro de la carpeta prices-sarvice
git pull
mvn update 
mvn clean package. 
Con o sin el IDE, el jar que se crea en el target despliega la app, contruye el esquema de datos y su contenido.
Sólo está el método get en el controller. 
```
	"url": "http://localhost:8080/api/price?requestDate=2020-06-15 16:00:00&productId=35455&brandId=1"
```
No todos los tests están completos, pero si se revisa el comportamiento en los casos definidos.
![image](https://github.com/user-attachments/assets/daf17c72-a8c8-4a75-828f-79c5963ded24)

De cara a la gestión de los errores, he prreferido aprovechar la potencia de controller advice, para retornar la explicación de lo que ha provocado el error, aunque soy muy consciente de que en un entorno de producción es una brecha de seguridad, y el mensaje genérico para un usuario sería: "Contacte con el servicio tecnico" o algo parecido. E internamente, hacerle llegar a la aplicación de auditoría interna, el mensaje o la traza del error.
![image](https://github.com/user-attachments/assets/dcf017dd-e02e-4644-8e55-ed7c73850723)
![image](https://github.com/user-attachments/assets/c6dcb5e8-3777-48d8-a465-d25cb6b3c9c9)

Swagger url
```
"url": "http://localhost:8080/swagger-ui/index.html#/"
```
