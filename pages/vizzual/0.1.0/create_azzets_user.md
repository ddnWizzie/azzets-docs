---
title: Create Users Provider
permalink: /vizzual_0.1.0_create_azzets_user.html
version: 0.1.0
toc: false
---

<!-- {% include image.html file="vizzual/logo.svg" alt="Vizzual" %} -->

***
First impression upon access.
Upon identifying ourselves, our main window will appear. A Provider user could only create other provider type users and the new users belong to the same Provider. To do this we click on `Administration / User Management`. 

{% include image.html file="azzets/createProviUser/creatNUserinit.png" alt="Create User" %}  

***

We click on the blue `Create A New User` button and fill in the fields of the Form:  
{% include image.html file="azzets/createProviUser/formProvUser.png" alt="Create User" %}  

*Username "email"*: It is the access user  

*First Name*: This is the name of the user who will use this account  

*Last Name*: This is the last name of the user who will use this account.  

*Wizzie Token API*: This is a Token API that Wizzie must give to the user. Without this API the user cannot work in the system, it is necessary to be able to load the Wizzie organizations and to be able to create Provider.  

*Language*: This is the user's preferred language. The application supports three languages, Spanish, English and Catalan  

***
At the end we click on the blue `SAVE` button and this will take us to the window where all the users created that belong to the same Provider will be, the application gives us the option to delete or modify a user if we wish:  

{% include image.html file="azzets/createProviUser/provUserEnd.png" alt="Create User" %}


