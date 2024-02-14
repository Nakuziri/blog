### What is Flask?

So, after trying to do some research on the various amounts of frameworks that are compatible with HTML & CSS, you might,ve stumbled upon a framwork called Flask, which is specifically written in Python. As mentioned before, Flask is a Framework that out of the various different ones, is made to allow Python to be used with HTML & CSS. This makes it very unique as it allows you to insert the functionality of Python within your web applications. This means you can now have the ability for more advanced options within writing your code. Alongside that, it also allows you to use different ways to route your urls and set up your web pages; However, this isn't the only thing that it's capable of as it allows you to impliment Structured Query Language into your code (Also known as SQL) for the functionality of pairing up your website with a data base, allowing you to keep track of information and making the overall use of your website better.

## Why might these functionalities be useful?

I am aware of the fact that I've stated the additional functionalities that comes with this specific framework, but to get deeper into its capabilites, I'd love to set some examples. The use of this framework and its paired functionalities are but arent limited to: Storing data and sending it out to users allowing things like personal accounts or puchases of goods through said website possible; Advanced capabilites to buttons or specific codes,an example can be the upcoming code snippet used for signing in my users through connecting Python with SQL by retrieving their login information from my database.

    if request.method == 'GET':
        usernameLog = request.form['usernameLog']
        passwordLog = request.form['passwordLog']
        cursor = conn.cursor()
        cursor.execute(f"SELECT * FROM `users` WHERE `Username` = '{usernameLog}' ")

        result = cursor.fetchone()

>Note: this code is used to search for one specific user within my data base and if it finds it, the code checks if the inputed password is equvilent to the one within the data base to allow the user to login successfully. 

Things like this allow my website to be used at a higher scale due to its notable capabilities.

###