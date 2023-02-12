#hbnb---the-console
This repository contains the initial stage of a student project to build a clone of the AirBnB website. This stage implements a backend interface, or console, to manage program data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

#repository-contents-by-project-task
| Tasks                         | Files                  | Description           |
| ------------------------------| ---------------------- | ----------------------|
| 1: Pep8                       | N/A                    | All code is pep8 compliant |
| 2: Unit Testing               | /tests                 | All class-defining modules are unittested |
| 3. Make BaseModel             | /models/base_model.py  | Defines a parent class to be inherited by all model classes|
| 4. Update BaseModel w/ kwargs | /models/base_models.py | Add functionality to recreate an instance of a class from a dictionary representation |
| 5. Create FileStorage class | /models/engine/file_storage.py /models/_ init _.py /models/base_model.py | Defines a class to manage persistent file storage system |
| 6. Console 0.0.1 | console.py | Add basic functionality to console program, allowing it to quit, handle empty lines and ^D |
| 7. Console 0.1 | console.py | Update the console with methods allowing the user to create, destroy, show, and update stored data |
| 8. Create User class | console.py /models/engine/file_storage.py /models/user.py | Dynamically implements a user class |
| 9. More Classes | /models/user.py /models/place.py /models/city.py /models/amenity.py /models/state.py /models/review.py | Dynamically implements more classes |
| 10. Console 1.0 | console.py /models/engine/file_storage.py | Update the console and file storage system to work dynamically with all classes update file storage |

https://github.com/Ashiegbu/AirBnB_clone#:~:text=update%20file%20storage-,General%20Use,-First%20clone%20this
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=First%20clone%20this%20repository.
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=Once%20the%20repository,AirBnB_clone%24%20./console.py
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=When%20this%20command,(hbnb)
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=This%20prompt%20designates%20you%20are%20in%20the%20%22HBnB%22%20console.%20There%20are%20a%20variety%20of%20commands%20available%20within%20the%20console%20program.

https://github.com/Ashiegbu/AirBnB_clone#:~:text=the%20console%20program.-,Commands,-*%20create%20-%20Creates%20an
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=*%20create%20-%20Creates%20an%20instance%20based%20on%20given%20class
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=on%20given%20class-,*%20destroy%20-%20Destroys%20an%20object%20based%20on%20class%20and%20UUID,-*%20show%20-%20Shows%20an
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=class%20and%20UUID-,*%20show%20-%20Shows%20an%20object%20based%20on%20class%20and%20UUID,-*%20all%20-%20Shows%20all
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=class%20and%20UUID-,*%20all%20-%20Shows%20all%20objects%20the%20program%20has%20access%20to%2C%20or%20all%20objects%20of%20a%20given%20class,-*%20update%20-%20Updates%20existing
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=a%20given%20class-,*%20update%20-%20Updates%20existing%20attributes%20an%20object%20based%20on%20class%20name%20and%20UUID,-*%20quit%20-%20Exits%20the
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=*%20quit%20-%20Exits%20the%20program%20(EOF%20will%20as%20well)

https://github.com/Ashiegbu/AirBnB_clone#:~:text=will%20as%20well)-,Alternative%20Syntax,-Users%20are%20able
Users are able to issue a number of console command using an alternative syntax:
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=Usage%3A%20%3Cclass_name%3E.%3Ccommand%3E(%5B%3Cid%3E%5Bname_arg%20value_arg%5D%7C%5Bkwargs%5D%5D)

Advanced syntax is implemented for the following commands:
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=the%20following%20commands%3A-,*%20all%20-%20Shows%20all%20objects%20the%20program%20has%20access%20to%2C%20or%20all%20objects%20of%20a%20given%20class,-*%20count%20-%20Return%20number
 https://github.com/Ashiegbu/AirBnB_clone#:~:text=*%20count%20-%20Return%20number%20of%20object%20instances%20by%20class
 * show - Shows an object based on class and UUID
 * destroy - Destroys an object based on class and UUID
 * update - Updates existing attributes an object based on class name and UUID