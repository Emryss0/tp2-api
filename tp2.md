# tp2-api
1.Pour effectuer une requête GET sur les commentaires dans Postman, On entre l'URL https://jsonplaceholder.typicode.com/comments, on precise la méthode GET et on clique sur "Send".

2.Pour effectuer une requête POST sur les todos dans Postman, on entre l'URL `https://jsonplaceholder.typicode.com/todos`, on sélectionne la méthode POST, puis dans l'onglet Body, on choisit le format `x-www-form-urlencoded` et on ajoute les paramètres nécessaires (par exemple, `title`, `completed`, `userId`). Ensuite, on clique sur "Send" pour envoyer la requête.

3.Pour effectuer une requête PATCH sur les posts dans Postman, on entre l'URL `https://jsonplaceholder.typicode.com/posts/{id}`, on sélectionne la méthode PATCH, puis dans l'onglet Body, on choisit le format `raw` et on sélectionne le type `JSON`. On modifie ensuite les paramètres comme `title` et `body` dans le corps de la requête. Enfin, on clique sur "Send" pour envoyer la requête.

4.Pour effectuer une requête GET permettant d'afficher les commentaires associés au post ayant l'identifiant 1 dans Postman, on entre l'URL `https://jsonplaceholder.typicode.com/comments?postId=1`, on sélectionne la méthode GET et on clique sur "Send" pour envoyer la requête.

5.Pour effectuer une requête GET permettant d'afficher les photos affiliées à l'album numéro 2 dans Postman, on entre l'URL `https://jsonplaceholder.typicode.com/photos?albumId=2`, on sélectionne la méthode GET et on clique sur "Send" pour envoyer la requête.