## General coding stuff

#### OOP - Object Oriented Programming
- Encapsulation - Group related methods/attributes into a single entity to limit unnecessary access to data
- Inheritance - Reuse common functionality 
- Abstraction - Allows the creation of abstract classes that defines the base of more concrete sub-classes with more concrete implementation
- Polymorphism - Lets different classes be recognized as a common superclass to enable the use of overriding and overloading

#### SOLID Principles
- Single Responsibility - Only have one job, one reason to change the logic
- Open-Close Principle - Behaviour should be open to extension but closed to modification
- Liskov Substitution Principle - Derived classes should be substitutable with its base class
- Interface Segregation Principle - No class should be forced to implement methods it doesn't use. Create smaller, more focused interfaces instead
- Dependency Inversion Principle - Use abstractions or injections instead of direct dependencies between modules

#### Frontend vs Backend
Frontend
- is what the user interacts with
- is how the app will look like

Backend
- is what determines how the user interactions or data will be handled
- the behaviour of the app

#### Lazy Loading
Where you delay the initialization or rendering of an item until it is needed

#### Entity Framework
Uses a code-first approach where you can first create the models and their relations and then create the database based on this

#### Middleware
Handles requests and responses. ie: transform/validation

#### Dependency Injection
Where an object receives other objects/functions/services that it needs to use instead of instantiating them internally. Decouples them and helps for mocking/testing
- via constructor 
- via method
- via setter

#### Extension Methods
Lets you add new functionality or methods to existing types by utilizing the `this` keyword in the parameters

#### Unit Testing
Checks if the block of code or function works as intended, both succeeding and failing.

#### var, let, cons
var
- scope: global or function
- **can** be re-declared **and** updated

let
- scope: block
- **cannot** be re-declared **but can** be updated

const
- scope: block
- **cannot** be re-declared **and** updated

#### Routing
Frontend
- for component navigation

Backend
- for handling client-side requests

#### Modules
?

#### HTTP methods
Post
- Used to create
- Used to submit an item in the request to the backend

Put
- Used to create **but will replace/overwrite if it already exists**
- Used to replace existing instances of the payload

Get
- Used to retrieve data



