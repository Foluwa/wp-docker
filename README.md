# Wordpress Setup With Docker
 Setup Wordpress, MySQL & PHPMyadmin with a single command using the  Docker compose file. 

## Setup
1. Confirm that you have [docker](https://www.docker.com/) installed in your environment and
2. Navigate into the project root directory 
3. Run the  `docker-compose up`
4. Navigate your browser to `http://localhost:8000/` (You will conclude wordpress installation here)
5. For Phpmyadmin navigate to `http://localhost:8080`  
6. An exported version of the database is in the root directory named `wp-docker-db.sql` 
 

    ### Wordpress
    Username: `admin`

    password: `admin`

    email: `admin@admin.com`


    ### Phpmyadmin 
    username: `wordpress`

    password: `wordpress`