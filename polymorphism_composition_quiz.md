# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

1A. The definition of the word polymorphism is the condition of a condition that has many events.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

2A. It is applied when we have a parent class that has a reference that can be used by it's children.  For example, the parent class would be a person with name, age attributes. It's children could be Waiter, Waitress, Chef, Manager which would share these attributes with their parent.

3. What can we use to implement polymorphism in Java?

3A. We can add in interfaces which sets promises for classes to adhere too. In the example above, all the children would promise to have a name and have an age.

4. How many 'forms' can an object take when using polymorphism?

4A. There are 2 types of polymorphism, Dynamic and Static.

5. Give an example of when you could use polymorphism.

5A. When you have many classes sharing the same attributes, setting up a parent filters down to it's children.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

6A. It is when class has a relationship with another class.

7. When would you use composition? Provide a simple example in Java.

7A. When assigning a class to another. For example, a Person class could be assigned a car.

8. What is/are the advantage(s) of using composition?

8A. It is flexible compared to inheritence and can be changed in runtime.

9. When an object is destroyed, what happens to all the objects it is composed of?

9A. Any functions that used the object would no longer work and either have to be refactored or deleted.
