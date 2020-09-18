---
title: Creating an Azzets
permalink: /azzets_0.1.X_creating_azzets.html
toc: false
---

* * *

 
The Azzets is the one who sends the data to the kafka topics. To create a new Assets we go to the `Entities / Assets` tab:  


{% include image.html file="azzets/createRootazzets/entitiesAzzets.png" alt="Create User" %}

* * *

We click on the blue `Create A New Azzets` button and fill in the fields of the Form:  

{% include image.html file="azzets/createRootazzets/formAzzets.png" alt="Create User" %}  
_ _ _
*Identifier*: This is the name of the Assets that we are creating.  

*Description*: A brief description of the Assets created.  

*Vendor*: It is an identifier.  

*Provider*: This is the list of all the Providers created, you must choose the one to work with.  

The enable checkbox, we must mark it.  

* * * 
At the end we must click on the blue SAVE button, and this will take us to the window where all the Assets created will be, the application gives us the option to delete or modify an Assets if we wish:  

{% include image.html file="azzets/createRootazzets/createAzzetsEnd.png" alt="Create User" %}  

          


The application automatically sends the data to the kafka topic, as the events are created. It also gives us the option to forward the entire stream using the Send Kafka button.