Deploy containers : `docker-compose build --force-rm --no-cache && docker-compose -f docker-compose.yml up`

Access via "http://localhost:8080" (or "http://$(docker-machine ip):8080" if using docker-machine)

During initial Drupal setup,  
Database type: PostgreSQL  
Database name: postgres  
Database username: postgres  
Database password: smile  
ADVANCED OPTIONS; Database host: postgres  