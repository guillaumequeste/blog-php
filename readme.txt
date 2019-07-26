base de données : blog

table billets :
    id : int AI PK
    titre : varchar 255
    contenu : text
    date_creation : datetime - valeur par défaut : CURRENT_TIMESTAMP

table commentaires :
    id : int AI PK
    id_billet : int
    auteur : varchar 255
    commentaire : text
    date_commentaire : datetime - valeur par défaut : CURRENT_TIMESTAMP