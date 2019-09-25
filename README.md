Minimal setup:

- Execute the global build via `gradlew build`
- Deploy the EAR from `ear/build/libs` inside Glassfish, e.g., copy to `%GLASSFISH_HOME%\glassfish\domains\domain1\autodeploy`
- Open `http://localhost:8080/frontend` to see the initial UI of the frontend project


Functionalties:

 Beverage Management( http://localhost:8080/frontend/beveragemanagement )
    
    - Creation of new beverages
    - Modification of existing Beverages
    - Deletion of Beverages
    
 Incentive Management ( http://localhost:8080/frontend/incentives )

    - Creation of new Incentive names 
    - Modification of existing Incentives
    - Deletion of Incentives
    
 Order Creation ( http://localhost:8080/frontend/createorder )

    - Displays list of available Beverages
    - Orders can be created by selecting the necessary Beverage and its Quantity
 
  Report Management ( http://localhost:8080/frontend/reports )
 
    - Displays the summerized report based on Orders and Incentives 
    - Report can be filtered by dates and sorted by OrderId, Date and Price  