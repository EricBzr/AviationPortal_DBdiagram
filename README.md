# AviationPortal_DBdiagram
A repository that holds a diagram of our web platform's ideal database schema's &amp; relationships

# Note
The contents of this repo should contain a single text file with our diagram's dbdiagram.io relevant code. Example:

           Table users as U {
              id int [pk, increment] 
              full_name varchar
              created_at timestamp
              country_code int
           }

           Table countries {
              code int [pk]
              name varchar
              continent_name varchar
           }
