# Prototype Design Pattern

## What is Prototype Pattern?

Prototype design pattern is used to create a duplicate object or clone of the current object to enhance performance. This pattern is used when the creation of an object is costly or complex.

For Example, An object is to be created after a costly database operation. We can cache the object, returns its clone on next request and update the database as and when needed thus reducing database calls.

## Participants

** Prototype ** - This is an interface which is used for the types of object that can be cloned itself.

** ConcretePrototype ** - This is a class which implements the Prototype interface for cloning itself.