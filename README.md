# Website sqlite3 connection with django
 css javascript bootstraping and sqlite3 connection with django 

### What this project has done for me
- It was a very good project to improve myself with Django and with sqlite3.
- It helped me improve myself a lot in Bootstrap, which uses CSS and Javascript in website design. I learned about desing website with extensions. I prefer this to blog style websites
- I learned to code concepts such as opening a membership to the site, logging in and logging out of the account.
- I learned to connect the website interface and database.
- With the help of database website connection, we can make changes on the website through the interface without making any changes to the main code.
- By using Jinja, I learned to use the same navbar, footer and links in all extensions of our website.
- Website design with discrete files, database website connection etc. It gave me a lot of skills.

# Follow the steps to run the project 
> #### If you wish, you can look at the visual explanation in the lower pane.

- ### 1- First we need to install `python` .
  - if you wish install `sqlite3` browser.

- ### 2- We need to download the necessary libraries. You can do this by typing the following commands in the terminal.
  - #### `pip install Django` and add extension `jinja` .

- ### 3- In the file directory we are in, we write `python manage.py runserver` to the terminal. When you copy and paste this address, which will give us the local host and port address, the website will appear.

- ### 4- Now you can surfing on my website. You can register , log in, log out , You can surfing on pages (ex. home, about, stories). You can click my links on footer.

- ### 5- You can login to the admin panel by creating an admin user. So what does this panel do? How do I create an admin user?
   - #### A-) In the file directory we are in, we write `python manage.py createsuperuser` to the terminal for create admin user. than register.
   - #### B-) In addition to the website address, we can reach our admin panel login page by typing /admin
   - #### C-) Enter your admin informations.
   - #### D-) Now you are in admin panel.
   - #### E-) You can add users, remove users and change users' authorization. You can add and remove stories and edit their information.
   - #### F-) There is also a filter in the story panel to filter the stories by the time they were added and the name.
   - #### G-) In short, you can manage website and database settings from this screen.
   - #### H-) Also, when you log in from here and return to the home page, the user will be logged in.

- ### 6- Inside the `static` file there are css, javascript, jquery codes and photos that I use.

- ### 7- Inside the `templates` file there are pages html files.

- ### 8- Thanks for your time.

###### information: When I first designed the story section, I thought it was a movie screen, then it became very cliché, I will change the extension and db names to story as soon as possible.
----
# Visual representation
> ### Pages

https://github.com/NumaIYI/website-sqlite3-connection-with-django/assets/128406291/45176071-8485-4d58-859d-094b85d7db17


> ### Home Page

https://github.com/NumaIYI/website-sqlite3-connection-with-django/assets/128406291/17415022-5424-4600-84ab-93e2a368ee1d

> ### Register and after submit

https://github.com/NumaIYI/website-sqlite3-connection-with-django/assets/128406291/bdb14c2e-f33e-4a94-839a-b8c411522619

> ### Login and after submit

https://github.com/NumaIYI/website-sqlite3-connection-with-django/assets/128406291/ae26cb1d-6a20-438d-8658-04ca07180092

> ### Logout and after click

https://github.com/NumaIYI/website-sqlite3-connection-with-django/assets/128406291/e7ebbeb2-ee27-4c3b-b8d6-b906a668bec2

> ### Admin panel and users

https://github.com/NumaIYI/website-sqlite3-connection-with-django/assets/128406291/71808ff7-d2ba-4dfc-9d26-2587aabaf438

> ### Admin Stories page and story edit page
> ##### You can see name is movies this is my bad sory.
https://github.com/NumaIYI/website-sqlite3-connection-with-django/assets/128406291/42e90eb1-e41a-460c-b39f-56d6ebddaf3b


> ### Example of add Story, You can doing same things for delete and change.

https://github.com/NumaIYI/website-sqlite3-connection-with-django/assets/128406291/4004166e-128f-4791-843c-79d4993763f4



----
# Tables

## Pages Table

| Page | Navbar | Body features  | Footer | Extension main/ ... | 
| ------------- | ------------- | ------------- | ------------- | ------------- | 
| Home  | Classic(Page shortcuts)  | Searching, Widgets, Highlights, Info | Classic(links) |  | 
| About  | Classic(Page shortcuts) | About compay ,us and my links  | Classic(links)  | about | 
| Stories  | Classic(Page shortcuts) | Stories with links  | Classic(links)  | movies | 
| Story  | Classic(Page shortcuts) | Selected story page  | Classic(links)  | movies/(int) | 
| Register  | Classic(Page shortcuts) | Register screen | Classic(links)  | user/register/ | 
| Login  | Classic(Page shortcuts) | Login screen | Classic(links)  | user/login |
| Admin  | Admin shortcuts | Login screen then Admin panel | hasn't  | admin |
| User  | Admin shortcuts | Users add remove change | hasn't   | admin/auth/user  |
| Movies(stories) | Admin shortcuts | Stories panel | hasn't   | admin/movie  |
| Movie change(stories) | Admin shortcuts | story; add, remove, change |  hasn't  | admin/movies/movie |

> ## In this project, there is no function table because 5 different software languages are used and there are too many functions.
----
# Our diagram like this
### The admin panel gives an order and changes are made in the database in line with this order and this change is transferred to the website through the db website connection. 

----
# **My links**

[Project link](https://github.com/NumaIYI/website-sqlite3-connection-with-django)

[Linkedin acoount](https://tr.linkedin.com/in/ahmed-numan-%C3%A7ift%C3%A7i-96305a243 "Linkedin hesabım")

**Via mail : numanbey11@gmail.com**

[Instagram](https://www.instagram.com/ahmednuman.ciftci/)
