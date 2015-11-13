mongoimport --db be-mean --collection restaurantes --drop --file restaurantes/restaurantes.json

use be-mean

> db.restaurantes.count();
25359

