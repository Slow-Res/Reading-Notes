# Putting it all together


<br><br>

## What is the single responsibility principle and how does it apply to components?

<br>

> Single responsibility principle means every __class, method, function, component,__ should do one thing, in React every component responsible to render one element. 


<br>


## What does it mean to build a ‘static’ version of your application?

<br>

> Static means, using only props in the project (Fixed Data)

<br>

## Once you have a static application, what do you need to add?

<br>

> We need to make the application interactable, we need to use state.

<br>

## What are the three questions you can ask to determine if something is state?

<br>


> Is it passed in from a parent via props? If so, it probably isn’t state.
        
> Does it remain unchanged over time? If so, it probably isn’t state.

> Can you compute it based on any other state or props in your component? If so, it isn’t state.


<br>

## How can you identify where state needs to live?

<br>

> Identify every component that renders something based on that state.

> Find a common owner component (a single component above all the components that need the state in the hierarchy).

> Either the common owner or another component higher up in the hierarchy should own the state.

> If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


<br>
<br>


## What is a “higher-order function”?

<br>


> Functions that operate on other functions, either by taking them as arguments or by returning them

<br>


## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

<br>

> It returns Callback, where it defins the base value.

<br>


## Explain how either map or reduce operates, with regards to higher-order functions.

<br> 

> It accepts callback as parameter, so they are called high order functions

<br> <br>

## Things I want to know more about

<br>

### I want to know more about the styling methods in React