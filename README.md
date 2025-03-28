# todolist
A simple server on go, with СRUD connection to skl light and data storage there, as well as UI using react.

Dependencies: 
                                                                                   
For routing:                                                                           
github.com/go-chi/chi/v5 v5.2.1 
  
To work with the client part, you need to set up a CORS                                  
github.com/go-chi/cors v1.2.1                                                     
 
To make working with environment variables easier                                           
github.com/joho/godotenv v1.5.1                                                   
 
Connecting to Postgres                                             
github.com/lib/pq v1.10.9                                                 
 
Connecting to Sqlite                                                     
github.com/mattn/go-sqlite3 v1.14.24                                           
