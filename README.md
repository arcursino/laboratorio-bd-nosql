Atividades da matéria Laboratório de Banco de Dados

Install mongoDB 4.0
https://www.mongodb.org/downloads
criar diretório \data\db com as permissões necessárias para testar bin\mongod (servidor)
bin\mongo (mongo shell)

pip install pymongo
pip install bottle 
Mongo shell (JavaScript)
help
show dbs
show collections
db.help()
db.test.help()
post = {"title": "My Blog Post",
        "content": "Here's my blog post.",
        "date": new Date()}
db.blog.insert(post)
db.blog.find()
db.blog.find().pretty()
db.blog.findOne()
post.comments = []
db.blog.update({title: "My Blog Post"}, post)
db.blog.findOne()
db.blog.remove({title: "My Blog Post"})
db.blog.findOne()

CRUD python
Create = Insert, Read = Find, Update = Update, Delete = Remove


tarefas:
inserir na collection names {"name": "seunome"}
ler a collection names e mostrar o primeiro registro (fisl 06)

mongo shell > db.names.remove({name: "seunome"})
mongo shell > db.names.save({name: "Mongo is great"})
dar refresh no browser