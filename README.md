# Purpose
This repository will serve to hold a diagram of our web platform's ideal database schema's &amp; relationships

# Notes on Making Edits/Commits
The contents of this repo should contain a single text file called "aviation-diagram.txt" with our diagram's dbdiagram.io relevant code. The code should look like this:

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
           
This way, it will be easy to analyse what changes were made on a glance but you should also provide exact details in your commit descriptions (e.g. what schemas were made, what fields were added to what schemas, ext.)

If you wish to make an edit to the diagram (diagram code), simply copy the code from the text file inside this repo and paste into the text box within dbdiagram.io. Once you finish making changes, you copy all the code from your text box within dbdiagram.io and paste into the text file in your cloned repo (or directly here which I believe you can do too and might be more straightforward) and commit with an appropriate description. 
