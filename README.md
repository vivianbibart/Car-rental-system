# GIS Car rental system

# Enunt
  Sa se creeze un sistem de inchiriere al masinilor spre clienti, indicand evidenta inchirierilor spre clienti avand in vedere masina, numele clientului, date despre client, precum si perioada de timp in care masina respectiva este data spre inchiriere. 

  Entitati:
  - Cars: car_id ; make ; model ; year ; color ; plate_number 
  - Customers:  customer_id ; name ; address ; driver_license_number
  - Rentals: rental_id ; start_date ; end_date ; car_id ; customer_id
  
  ![Diagrama_abstracta_Car rental](https://user-images.githubusercontent.com/118603219/216809866-87a2fea1-84a3-45c0-ae6b-c05459b339eb.JPG)

  
  ![Diagrama_car_rental](https://user-images.githubusercontent.com/118603219/216809614-8a040dca-81af-4c6a-a61a-26de1e27290e.png)

  
  Steps:

git clone (descarcare repository)
git status
pentru a importa baza de date in pgadmin:
open pgadmin
enter your admin password
open your databases tab
create a database
right click on your database
click import and select the file "car_rental_system.sql"
pentru a modifica repository (git add)
git commit -m "your message goes here"
git push -f
