Instalar:
npm install express mysql2 bcrypt cors multer

Inicializar Server: 
node index.js


Na conexão do MySQL:
const db = mysql.createConnection({
    host: 'localhost',
    user: '',                               -> Adicionar USER
    password: '',                           -> Sua password
    database: 'edequity'
}).promise(); // Usar .promise() para async/await com db.query
