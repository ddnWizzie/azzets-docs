---
title: Create User
permalink: /azzets_0.1.X_creating_user.html
toc: false
---


* * *
First impression upon access.
When we identify ourselves, our main screen will appear, where the first thing we will do is manage our account. We click on `Administration/User Management`

{% include image.html file="azzets/useRoot/cnu_manager1.png" alt="Create User" %}

* * *
Here we see our user and we click on edit, we get a new window where we will fill in the form.

{% include image.html file="azzets/useRoot/formRoot.png" alt="Form" %}

*Username "email"*: It is the login user

*First Name*: This is the name of the user who will use this account eg. Robert

*Last Name*: This is the Surname of the user who will use this account. ex. Smith

*Wizzie Token API:* This is an API Token that Wizzie must give to the user. Without this API the user cannot work in the system, it is necessary to be able to load the Wizzie organizations and to be able to create Provider

*Language:* This is the user's preferred language. The application supports three languages, Spanish, English and Catalan


* * * 
   {% include image.html file="azzets/useRoot/enduser.png" alt="End" %}             
_ _ _
There are two types of users, root and a Provider administrator:

1- Root:

The root and activated check boxes are marked by default, to create a root user we must select both check boxes. If you are root, you will have access to all the Providers and all the information.
At the end we click on the blue `SAVE` button.

{% include image.html file="azzets/createUserRoot/checkboxroot.png" alt="Create User" %}

2- Provider:  
In the event that the user we are creating is not root, we must uncheck the root checkbox and specify the Provider to which it belongs. This user will only see the data of their Provider.

{% include image.html file="azzets/createUserRootProvider/user-noroot.png" alt="Create User" %}

