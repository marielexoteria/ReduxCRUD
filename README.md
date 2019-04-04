# ReduxCRUD
Proyecto de React que usa como ejecutar acciones de CRUD (create - read - update - delete) usando Redux. Curso de React y Redux por Juan Pablo de la Torre en udemy.com 

# Dependencias a instalar
axios
react-redux
redux
redux-thunk
react-router-dom

# Instalar servidor de JSON para imitar el comportamiento de una API
sudo npm install -g json-server (https://jsonplaceholder.typicode.com/ tenía esa opción en la página cuando el curso se hizo, pero ya no la tienen publicada).

# Para iniciar el servidor que va a leer el archivo de JSON que simulará la base de datos
json-server --watch productos.json --port 5000
