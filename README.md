# FastAPI **Property API**
**CRU API** designed to handle REST petitions to **create, read and update** properties in a mongo database. It can save images in a static folder and asociate them to properties. It can also create owners and asociate the properties to them. The price of a property with a given ID can be updated. **Testing** has been implemented for the methods in the routers for both the properties and the owners. 

## Steps to try the **Property API**

1. **Clone the repository**
2. **Create a virtual environment**

   % python -m venv env

3. **Activate the virtual environment**

   % source env/bin/activate
4. **Install the requirements**

   % pip3 install -r requirements.txt
6. **Run the tests**

   % pytest
8. **Run the API**

   % python main.py
10. **Enjoy**

Once the service is runnig, you can access the API in your browser using the url:
    http://127.0.0.1:8000/
The **documentation** can be visited in the swagger using the url:
    http://127.0.0.1:8000/docs
There you can test all the features.
