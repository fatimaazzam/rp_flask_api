# Python REST APIs With Flask, Connexion, and SQLAlchemy 

## Planning Part


|     Action	|  HTTP Verb |	   URL Path	             |     Description
| ----------- | ---------- |---------------------      |-------------------------------
|     Read	  |  GET	     |  /api/people	             |  Read a collection of people.
|     Create	|  POST	     |  /api/people	             |  Create a new person.
|     Read	  |  GET	     |  /api/people/lname	       |  Read a particular person.
|     Update	|  PUT	     |  /api/people/lname	       |  Update an existing person.
|     Delete	| DELETE	   |  /api/people/lname	       |  Delete an existing person.




## The dataset :
```python
PEOPLE = {
    "Fairy": {
        "fname": "Tooth",
        "lname": "Fairy",
        "timestamp": "2022-10-08 09:15:10",
    },
    "Ruprecht": {
        "fname": "Knecht",
        "lname": "Ruprecht",
        "timestamp": "2022-10-08 09:15:13",
    },
    "Bunny": {
        "fname": "Easter",
        "lname": "Bunny",
        "timestamp": "2022-10-08 09:15:27",
    }
}
```
