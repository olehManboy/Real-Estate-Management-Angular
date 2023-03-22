# real-estate-management

A online property management solution for real estate and
physical property management. This can include residential,
commercial, and land real estate. a software developed to
connect property managers and potential buyers.

🚧 **frontend/** work in progress 🚧.

🚧 **backend-fastify/** work in progress 🚧.


![Screenshot](https://ik.imagekit.io/wr5lnrww0q8/REM_Folder/social_GKmc-8vHw.jpg?updatedAt=1631134174081)


## **Dependencies**

### **Frontend**
- [Ionic 6+](https://ionicframework.com/)
- [Angular 13+](https://angular.io/)
- [leaflet 1.7+](https://leafletjs.com/)
- [chartjs 3.5+](https://www.chartjs.org/)

### **Backend**
- [Node](https://nodejs.org/en/)
- [fastify 3+](https://www.fastify.io/)
- [mongoDB](https://www.mongodb.com/)

# **SETUP**

## **Frontend (Part)**

### **1.1 navigate to `frontend/` directory.**

```
#  navigate to frontend 
$ cd frontend
```

### **1.2 Fill the desired environment variables:**  
- navigate to `frontend/src/environments`
- set values to variables (ex. api.url) 
```
  api: {
    url: 'http://localhost:8000/', <-- server URL
    mapKey: '', <-- Leaflet map key
  }
```

### **2. then install dependencies & run ionic serve**

In terminal - command
```
# install dependencies
$ npm install

# serve frontend
& ionic serve
```

<br>
