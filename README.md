# docker-demo


`git clone https://github.com/jigarpancholi/docker-demo.git`

`cd docker-demo`

`docker-compose build`
`docker-compose up`

You can see now by running`localhost:3001`

Now run `localhost:3002` and login with username and password provided in `docker-compose.yml` file.
And import `users.yml` file in database.

Now run `localhost:3001/mysql-connect.php` you will see it connects to MySql database and displays records from `users` table. 
