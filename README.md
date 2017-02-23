# Master the JavaScript Interview: What’s the Difference Between Class & Prototypal Inheritance?

>_"The result is that JavaScript’s object system has a confusing split personality, which means that JavaScript developers need to know a bit about both prototypes and classes."_

Learning both prototypes and classes can seem redundant, but both (or a combination of both) will show up when on the job. 

### Inheritance is when you design your types around what they __are__; Compoisition is when you design your types around what they __do__. 

Inheritance encourages you to try to predict the future - this can be an issue when working with clients, for exmaple. There is no way to predict what types of changes or updates they may want after the code's structure has already been built.

Composition (used with prototypal inheritance) allows you to be more flexible and dynamic. If a client surprises you with a sudden change, it won't be necessary to re-write and re-structure entire blocks of code. 

#### Breaking it down further:

__Inheritance__ 

Pros: 
*Seems very straight forward, can be used quite literally
*Good for the smallest of small projects (with no plans to grow)

Cons: 
*Unnecessarily creating parent objects that don't actually apply to all the children objects
*Duplicating functionality (thus, creating unnecesary redundantcies) 
*forces you to attempt to predict the future

__Prototypal Instance__ - Objects inherit directly from other objects.

Pros:
*Accept their state as a function perameter, so different objects can share the same state

Cons:




###### codepen links:
[class inheritance] 
[prototypal inheritance]