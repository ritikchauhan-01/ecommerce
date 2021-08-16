# ecommerce


In this project , I have created the clone of the ecommerce site like flipkart and amazon.

**Languages and framewrok used : python3 ,django ,Javascript ,HTML ,Css**

When the user is logged in .
We can add items to the cart and checkout the items to our shipping address.

when the user is not aunthenticated I have made the use of cookie so that site working similar when the user is logged in .

Payment option is availabel [Here I have used the paypal script].

To run this you need to create your virtual enviroment and then install the required things.
* clone using $ git clone git@github.com:ritikchauhan-01/ecommerce.git ecommerce && cd ecommerce

#Run

* Install virtualenv
   * on Ubuntu: $ sudo apt install python-virtualenv
   * on Windows: $ pip install virtualenv

* Create a virtual environment
   * on Ubuntu: $ virtualenv venv
   * on Windows: $ virtualenv venv

* Activate the environment:
   * on Ubuntu: $ source venv/bin/activate
   * on Windows: $ ./venv/Scripts/activate
*Install the requirements:
   * $ pip install -r requirements.txt
 
* Make migrations $ python manage.py makemigrations
* Migrate the changes to the database $ python manage.py migrate
* Run the server $ python manage.py runserver

That's it. Open web browser and hit the url http://127.0.0.1:8000/


store page 
![Ecom](https://user-images.githubusercontent.com/56171689/129575173-e5fb89ec-6b59-4425-a34e-ed7f46318af4.png)

cart page
![Ecom (1)](https://user-images.githubusercontent.com/56171689/129575223-a0995ccf-849a-4ba2-86d9-d2af4c7f975b.png)

checkout page
![Ecom (2)](https://user-images.githubusercontent.com/56171689/129575270-fd236d54-2ef5-4148-b84b-c8c2e3ad97da.png)

payment page
![Screenshot from ](https://user-images.githubusercontent.com/56171689/129576223-ca9ada16-a2df-435a-8842-c0f4d8899a13.png)
