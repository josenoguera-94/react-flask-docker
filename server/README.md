# **Flask App**


## **For testing**

- `cd server` First

- `docker build -t pythonapp .` 

- `docker run -p 80:5000 -v ${PWD}:/app pythonapp` In Windows

- `docker run -p 80:5000 pythonapp bash` 

- `docker run -it -p 80:5000 pythonapp`