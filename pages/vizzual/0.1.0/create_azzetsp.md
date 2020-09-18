---
title: Create Azzets
permalink: /vizzual_0.1.0_create_azzetsp.html
version: 0.1.0
toc: false
---

***
Create Azzets (you can only from your Provider)

The Azzets is the one who sends the data to the kafka topics to create a new Assets, we go to the `Entities / Assets` tab:

{% include image.html file="azzets/CreateProviAzzets/entitiesAzzets.png" alt="Create Azzets" %}  

***
We click on the blue `Create A New Azzets` button and fill in the fields of the Form:  

{% include image.html file="azzets/CreateProviAzzets/formAzzp.png" alt="Form" %}
 
*Identifier*: This is the name of the Assets that we are creating.  

*Description*: A brief description of the Assets created.  

*Vendor*: It is an identifier.  

*Asset Use*: This is the list of all Azzets Use created, you must choose the one you are going to work with.  

The enable checkbox, we must mark it.  

***
At the end we must click on the blue `SAVE` button, and this will take us to the window where all the Assets created will be, the application gives us the option to delete or modify an Assets if we wish:  
{% include image.html file="azzets/CreateProviAzzets/provAzzEnd.png" alt="End" %}  

***

The application automatically sends the data to the kafka topic, as the events are created. It also gives us the option to forward the entire stream using the `Send Kafka` button