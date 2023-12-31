# AirBnB_clone

```
This project created as a clone of BackEnd of AirBnB website.

We are encouraged to complete tasks about cloning the AirBnB website,
the purpse is to learn how does this websites work
and to learn the problem solving.
```
[-> AirBnB](https://github.com/abdelemjidessaid/AirBnB_clone)


### 📂️ models

* Models Directory:
    ```
    Directory that holds all models of the porject which is
    class that is pices of data.
    ```
    [-> Link to models dir](https://github.com/abdelemjidessaid/AirBnB_clone/tree/main/models)


#### 📃️ BaseModel

* Purpese:
    ```
    Class of BaseModel created for reason, which is to avoid the repetition
    of some functions (dry) concept.

    All Model classes inherit from BaseModel next methods and attributes:
        - id (string): each instance should have an id.
        - created_at (object): object of datetime class, which contains
          the date & time of creation of this object.
        - update_at (object): object of datetime class, which contains
          the date & time of last update.
        - save (method): function that updates the update_at attribute.
        - __str__ (method): function that returns a string representation
          of the instance.
        - to_dict (method): function that returns a dictionary
          representation of the instance.
    ```
    [-> base_model.py](https://github.com/abdelemjidessaid/AirBnB_clone/tree/main/models/base_model.py)

#### 📂️ engine

* Engine Directory:
    ```
    Subdirectory that holds module of project Engine.
    ```
    [-> Link to engine dir](https://github.com/abdelemjidessaid/AirBnB_clone/tree/main/models/engine)


#### 📃️ file_storage

* File Storage:
    ```
    This is the engine of this project.
    ```
    [-> Link to file_storage.py](https://github.com/abdelemjidessaid/AirBnB_clone/blob/main/models/engine/file_storage.py)


### 📃️ Console

* Purpse of console:
    ```
    console is a comandline interpreter, that manages the data of
    website as (create, update, delete and display objects) created.
    ```
* Examples:
    ```
    $ ./console.py
    (hbnb) help

    Documented commands (type help <topic>):
    ========================================
    EOF  help  quit

    (hbnb) 
    (hbnb) 
    (hbnb) quit
    $
    ```
[-> Link to console.py](https://github.com/abdelemjidessaid/AirBnB_clone/blob/main/console.py)