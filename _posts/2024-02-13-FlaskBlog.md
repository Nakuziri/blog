### What is Flask?

So, after trying to do some research on the various amounts of frameworks that are compatible with HTML & CSS, you might've stumbled upon a framework called Flask, which is specifically written in Python. As mentioned before, Flask is a Framework that out of the various different ones, is made to allow Python to be used with HTML & CSS. This makes it very unique as it allows you to insert the functionality of Python within your web applications. This means you can now have the ability for more advanced options within writing your code. Alongside that, it also allows you to use different ways to route your URLs and set up your web pages; However, this isn't the only thing that it's capable of as it allows you to implement Structured Query Language into your code (Also known as SQL) for the functionality of pairing up your website with a data base, allowing you to keep track of information and making the overall use of your website better.

## Why might these functionalities be useful?

I am aware of the fact that I've stated the additional functionalities that come with this specific framework, but to get deeper into its capabilities, I'd love to set some examples. The use of this framework and its paired functionalities are but aren't limited to Storing data and sending it out to users allowing things like personal accounts or purchases of goods through said website possible; Advanced capabilities to buttons or specific codes, an example can be the upcoming code snippet used for signing in my users through connecting Python with SQL by retrieving their login information from my database.

    if request.method == 'GET':
        usernameLog = request.form['usernameLog']
        passwordLog = request.form['passwordLog']
        cursor = conn.cursor()
        cursor.execute(f"SELECT * FROM `users` WHERE `Username` = '{usernameLog}' ")

        result = cursor.fetchone()

>Note: this code is used to search for one specific user within my database and if it finds it, the code checks if the inputted password is equivalent to the one within the database to allow the user to log in successfully.<

Things like this allow my website to be used at a higher scale due to its notable capabilities.

### Information on difficulty and advice

Of course, starting to learn Flask was anything but a walk in the park; however, with the amazing help of my teachers and peers throughout my lessons, I managed to learn everything that I know now. This includes things like setting up Routes to my webpage, learning the ability to debug my code which didn't come easy as well, and of course, managing databases with SQL alongside Python. With all that, it was a very difficult situation for me to simply catch on and absorb all my information. My resource was asking my friends for advice so I could learn from them as they always knew things that I did not. On top of that, asking my teacher to explain something to me whenever I was troubled with something was always my best approach but I did feel conflicted since I wanted to try to learn things on my own. I'd personally recommend that if you as the reader do not have anyone to help you learn this, you can always search for things online to learn Flask as this internet is an amazing source of information. 

Whenever it came down to the difficulties aforementioned, I admit that I did struggle as I searched for some advice on the internet myself to assist me in setting up routing; However, my teacher always guided me with his amazing slides and presentations that effectively explained to me the purpose of everything and how to properly implement things.

### My Social Media Project 

At the moment, I am working on a Social Media Project with the theme being that it's made for nerds/geeks like myself to discuss the current situation with things such as the state of computer components, games, etc. The name of my website is Joystick as it serves to be a place for all geeks as aforementioned. I've managed to log all my progress throughout my website as I've made a landing page, picked a proper theme with colors, created a registration and sign-in page, and I'm even in the process of making a proper feed page while utilizing all of the functionalities of Flask. I plan on treating this as my own personal project since it majorly intrigues me and I plan on using all the effective skills I've learned from this project on future ones such as planning them out properly and everything else I've mentioned before.

