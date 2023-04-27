# Blogging System

## Applications
* Blogs => manage articles (post, delete, edit, display)
* Category => manage articles category (add/delete edit display)
* LoginSystem => register/login in to system
* WriterPanel => page that writer can edit their own article

## Types of User
* Admin👮🏻‍♂️ => manage systems (Articles, Users, Category, User permission)
* Writer✍🏼 => post, remove, edit articles
* Reader/ Visitor🤓 => read articles, able to register account. 

## Database categories
Column name|data type|meaning
:-------------------------:|:-------------------------:|:-------------------------:
ID(primary key)|IntegerField|ID of Article
Name|CharField|Article name
Description|TextField|Article description
Content|TextField|Article content
Writer|CharField|writer name
Views|IntegerField|number for views
image|ImageField|image
Created|DateTimeField|Article wrote date
Category_ID(Foreign key)|IntegerField|ID of category


## Screenshots

Welcome page
:-------------------------:
![image](https://user-images.githubusercontent.com/128176822/234559311-6427635b-4083-4b26-af23-d6f55b8c4046.png)

Article page
:-------------------------:
![image](https://user-images.githubusercontent.com/128176822/234559734-44f211a3-e832-4af0-9a3e-dd86f64768b3.png)

Article content page
:-------------------------:
![image](https://user-images.githubusercontent.com/128176822/234559881-5e24e5cd-7e10-4b06-a814-0fabba2fca30.png)

Login/Register page
:-------------------------:
![image](https://user-images.githubusercontent.com/128176822/234561043-f8fd8666-945f-4beb-b1e3-87ef836b4670.png)

Writer panel page (manage article)
:-------------------------:
![image](https://user-images.githubusercontent.com/128176822/234561297-f82c785e-e32e-455b-b384-dae86746fb9c.png)

Writer panel page (write article)
:-------------------------:
![image](https://user-images.githubusercontent.com/128176822/234561446-946b5b54-3695-4862-8367-f2d23ba21beb.png)

