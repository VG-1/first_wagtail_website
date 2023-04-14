# Let's make our first Wagtail website

Hello, so I just learnt about wagtail and it's use cases and how to create wagtail website so I will just write what I learnt through this tutorial.

Whether you're a web developer, designer, or content creator, this tutorial will provide you with step-by-step instructions on how to build a Wagtail website from scratch.

### First of all what is Wagtail?
Wagtail is open-source Python CMS ( ) being trusted by organisations like NASA, NHS, Caltech,University of Penselvania.

*If I'd to explain wagtail to a 5 year old kid, here is how it will look like*:-

Wagtail is like a tool that helps people make websites. It's like a box of building blocks that you can use to create a website by putting different things together, like text, pictures, videos, and more. It also helps grown-ups who take care of websites to organize and manage all the things that go on the website, like checking if everything looks good and deciding when to show things to other people. Just like how you use your toy blocks to build a tower, Wagtail helps grown-ups build websites!

Now I guess you have got a bit idea of what exactly Wagtail is so without a further let's get straight toward making our first wagtail website.



<!-- Instructions  -->

## Steps to follow:-
We just have to run this commands and believe me at the end of the tutorial you will be able to create your first website.
Just open your terminal and run the commands in terminal.

## First let's check the whether we have an appropriate version of Python 3:

```bash
  python --version
```
The output will look like this:
![alt text](https://user-images.githubusercontent.com/77708101/232137688-906e1929-1863-4fd1-8599-b1a8d69fb8b1.jpeg)

## Create and activate a virtual environment:

Just run this command

```bash
  py -m venv mysite\env
mysite\env\Scripts\activate.bat
# or:
mysite\env\Scripts\activate
```

The output will look like this:
![alt text](https://user-images.githubusercontent.com/77708101/232137694-b044eb9a-91a0-47c7-837a-1bec520c8606.png)

## Install Wagtail

```bash
  pip install wagtail
```
The output will look like this:
![alt text](https://user-images.githubusercontent.com/77708101/232137660-9f17d9ad-de4a-4b2b-99d2-9bd6ae84643d.png)


## Generate your site

```bash
  wagtail start mysite mysite
```
The output will look like this:
![alt text](https://user-images.githubusercontent.com/77708101/232137665-0ef8e1af-b856-41c0-9a68-e96b7c9d3785.png)

## Install project dependencies

```bash
  cd mysite
  pip install -r requirements.txt
```
The output will look like this:
![alt text](https://user-images.githubusercontent.com/77708101/232137670-5f3a4943-873c-4b48-936a-88e17e0f1cc5.png)



## Create the database

```bash
    python manage.py migrate
```
The output will look like this:
![alt text](https://user-images.githubusercontent.com/77708101/232137675-b6f3bb36-18a6-4b10-bcf7-8d66dc6d04f0.png)

## Create an admin user

```bash
    python manage.py createsuperuser
```

The output will look like this:
![alt text](https://user-images.githubusercontent.com/77708101/232139677-f413c909-ff3d-4bda-a062-ead256f0e4ed.png)


## Start the server:


```bash
python manage.py runserver
```

The output will look like this:
![alt text](https://user-images.githubusercontent.com/77708101/232137686-58aba163-700e-45a9-90f4-f4d5b8dbf23c.png)

If everything worked well, we will have our site running on http://127.0.0.1:8000/ 

And you will see a screen something like this:


![alt text](https://user-images.githubusercontent.com/77708101/232143484-3d31fa1c-9fef-40d4-8792-5760d446e886.png)

Now when will click on Admin interface, our admin interface will look like this at http://127.0.0.1:8000/admin :

![alt text](https://user-images.githubusercontent.com/77708101/232144480-6b1b6589-93f1-4b73-bfb6-cd38378079dd.png)

Now we have different features which we can use just link pages, images, documents etc. 

When we will click on images and we will upload a image it will look like this:

![alt text](https://user-images.githubusercontent.com/77708101/232146466-bb21a285-c8e6-4882-8b0f-9bacf4989351.png)

Now, you have successfully created your first wagtail website and you can just explore more about it at https://docs.wagtail.org/en/stable/getting_started/tutorial.html .

I hope this tutorial will help you out to make your first wagtail website :)



<!-- Contact Details -->

## 🔗 You can connect with me here:
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://vinayakgavariya.me/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/vinayakgavariya)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/vinayakgavariya)


