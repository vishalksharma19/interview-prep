__Internal working of Hashset__  
Internally, HashSet utilizes HashMap to store its elements, using the elements as keys in the HashMap and a dummy value (often PRESENT) for the values, ensuring uniqueness and efficient lookup.  
__HashSet's Internal Structure__:  
•	Underlying Data Structure: HashSet is implemented using a HashMap internally.   
•	Key-Value Pairs: Adding an element to a HashSet is stored as a key in the underlying HashMap, with a constant value (e.g., PRESENT).  
•	Uniqueness: The HashMap's key uniqueness property ensures that the HashSet only stores unique elements.  
•	No Value Access: You don't directly access the values in the HashMap when working with a HashSet. The focus is on the keys (the elements of the set).   

__What are the four pillars of OOPS.__  
The four pillars of Object-Oriented Programming (OOP) are Abstraction, Encapsulation, Inheritance, and Polymorphism.   
Here's a brief explanation of each:  
__Abstraction:__  
Hides complex implementation details and shows only essential information to the user.  
<img width="436" alt="image" src="https://github.com/user-attachments/assets/8c9d7c2a-35d8-4918-b2b0-c2b50144e670" />

__Encapsulation:__  
Bundles data (attributes) and methods (functions) that operate on that data within a class, restricting direct access to the data from outside the class.  
<img width="512" alt="image" src="https://github.com/user-attachments/assets/b53e6a55-f05a-489d-b40f-f3ec8df91b6f" />  
<img width="509" alt="image" src="https://github.com/user-attachments/assets/32ecdbb8-f8f5-472a-8513-72faea4621bd" />  

__Inheritance:__  
Allows a class (child class) to inherit properties and methods from another class (parent class), promoting code reusability and a hierarchical structure.  
<img width="356" alt="image" src="https://github.com/user-attachments/assets/7d694c5a-2192-455f-b03d-6942204bd0b3" />  

__Polymorphism:__  
Enables objects of different classes to be treated as objects of a common type, allowing for flexibility and extensibility in code.  
The word ‘polymorphism’ means ‘having many forms’. In Java, polymorphism refers to the ability of a message to be displayed in more than one form. This concept is a key feature of Object-Oriented Programming and it allows objects to behave differently based on their specific class type.  
<img width="398" alt="image" src="https://github.com/user-attachments/assets/927f803f-c4bc-41ee-aac1-8bdf137f5c0d" />  
__Method Overloading__  

Method overloading in Java means when there are multiple functions with the same name but different parameters then these functions are said to be overloaded. Functions can be overloaded by changes in the number of arguments or/and a change in the type of arguments.    
<img width="362" alt="image" src="https://github.com/user-attachments/assets/a1229cd4-907e-46af-8d7e-05d08561dd71" />  

__Method Overriding__  

Runtime Polymorphism in Java known as Dynamic Method Dispatch. It is a process in which a function call to the overridden method is resolved at Runtime. This type of polymorphism is achieved by Method Overriding. Method overriding, on the other hand, occurs when a derived class has a definition for one of the member functions of the base class. That base function is said to be overridden.    
  <img width="380" alt="image" src="https://github.com/user-attachments/assets/0c74779d-2b0e-40e4-b370-d3a8f4aa4e9b" />  

__Virtual Functions__  

 It allows an object of a derived class to behave as if it were an object of the base class. The derived class can override the virtual function of the base class to provide its own implementation. The function call is resolved at runtime, depending on the actual type of the object.  
 

    




