
# OOPs

## COMPONENTS 
- **class** : defines a set of data elements(attributes) and methods(behavior , function)
  ``` bash
  class Student :
   # members
  ```
- **constructor** : a special type of method(function) used to initialise members of the class 
  ``` bash
   class Student:
    def __init__(self, name, class_): # DEFAULT CONSTRUCTOR 
        self.name = name
        self.class_ = class_  # data members
  ```
- **object** :
  ``` bash
  stu = Student("Victor", 12) # object 
  stu.stuc()
  ``` 
- **reference** : used to refer to an object ex `stu` in  `stu = Student("Victor", 12)`
- **Full code**
  ``` bash
  class Student:
    def __init__(self, name, class_):
        self.name = name
        self.class_ = class_  # data members

    def stuc(self):
        print(self.name, "is in class", self.class_)  # method
  stu = Student("Victor", 12) # object 
  stu.stuc()
  ```
## PILLARS OF OOPS

- **ENCAPSULATION** : binding of methods(function) in a single unit
- **ABSTRACTION** :  a process of handling complexity by hiding unnecessary information from the user
  - ***private*** : accessible only within the class
  - ***protected*** : accessible within class or child class
  - ***public*** : can be used by the object or inhereted class
- **POLYMORPHISM** : utilizing an item for multiple task
  - ***method overloading** : same method name different parameters
   ``` bash
   def product(a,b):
     print(a*b)
   def product(a,b,c):
    print(a*b*c) 
   ```
  - ***operator overloading** : a specific case of polymorphism, where different operators have different implementations depending on their arguments

- **INHERTIANCE** : 
