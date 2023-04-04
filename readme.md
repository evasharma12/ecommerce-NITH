# **Ecommerce Website for NITH**
Buy and sell things just within NITH to increase the availability and lower the expenses.

## **Core features**:

### Signup and Login:

### Product Search:
An efficient search bar which allows easy product search.

### Product Description:
The product descriptions include the owner's phone number. The customer can contact the owner directly.


### Add to Cart:
The buyer can add products to cart and then order them collectively.


### Online Payment Option:
The website includes online payment feature too. 



**The online payment feature should only be used if the buyer trusts the seller.**

  
  
## **Installation Guide:**
- Clone the repository: `git clone https://github.com/evasharma12/ecommerce-NITH.git`
- Go to the project directory: `cd ecommerce-NITH`
- Create a virtual environment and activate it:

 **For Windows:**
 
   `> pip install virtualenv` 
   
   `> virtualenv myenv`
   
   `> myenv\Scripts\activate`
 

 **For macOS or Linux:**
 
   `$ sudo apt-get install python-pip`
   
   `$ pip install virtualenv`
   
   `$ virtualenv myenv`
   
   `$ source myenv/bin/activate`

- Install the Requirements: `pip install -r requirements.txt`
- Make database migrations: `python manage.py makemigrations`
- `python manage.py migrate`
- Run the application: `python manage.py runserver` 

## **Contributors:**
1. Eva Sharma
2. Esha Thakur
3. Garima Gupta
4. Nivedita Gupta


## Admin Access
- **Username:** admin
- **Password:** admin123
