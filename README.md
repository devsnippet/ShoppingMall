<!-- 폴더 내의 DB파일 넣기. -->
mongoimport -d project -c things --type csv --file db.csv -headerline

mongoimport -d cartDB -c carts --type csv --file cart.csv -headerline

mongoimport -d boughtitemDB -c boughtitems --type csv --file boughtitem.csv -headerline

<!-- 실행법 -->
콘솔창에서 프로젝트 폴더로 이동 후
nodemon bin/www

<!-- 접속 URL-->
localhost:3000


