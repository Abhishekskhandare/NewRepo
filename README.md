**Dependency injection** is when we supply a class dependency from outside. For example, if there is a company class which needs a method of the employee class. Now one way is to create the object of employee class inside the company class. But with dependency injection, we will not create the object inside.
Instead, we will pass the employee object into the company class via the constructor or any other way from the outside.
This way our classes employee and company will be loosely coupled, which will make the codes easier to unit test, easier to reuse, and to change also.

Dependency injection can be implemented using:

**Constructor injection**
1. Method injection
2. Property injection
3. Interface based injection

**Types of Dependency services:**
1. Scoped    :-  An instance is the same within a scope(api request), but different across different api scopes.Scope here usually refers to a request received by the application.
2. Singleton :-  A same instance is provided to every controller and service.
3. Transient :-  A new instance is provided to every controller and service.
