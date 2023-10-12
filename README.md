# CrudMongoDb
CRUD Básico para el curso de backend nodejs de digital webdise

mkdir formulario-crud
cd formulario-crud
npm init -y
npm install express mongoose body-parser ejs


// Abre una conexión con la base de datos (asegúrate de que la aplicación esté en ejecución)
use formulario-crud

db.createCollection('contactos')
db.contactos.insertMany([
  {
    nombre: 'Juan Pérez',
    email: 'juan@example.com',
    mensaje: 'Hola, soy Juan.',
  },
  {
    nombre: 'María García',
    email: 'maria@example.com',
    mensaje: 'Saludos desde María.',
  },
])

