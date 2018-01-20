# Testing

**Goals 2018**

*  Become more proficient in unit testing
*  Learn how unit testing works with frameworks

**Resources**       
[Unit Testing in JavaScript Part 1](https://www.youtube.com/watch?v=Eu35xM76kKY)        
[Unit Testing in JavaScript Part 2](https://www.youtube.com/watch?v=XsFQEUP1MxI)        

**Table of Contents**       
[What is Unit Testing?](#what-is-unit-testing)      
[Basic Example of Unit Testing](#basic-example-of-unit-testing)     


Unit testing was something I was weak on in 2017, part of the reason being because most of the resources I used didn't talk about it much.  Following the [web dev roadmap from 2017](https://github.com/kamranahmedse/developer-roadmap) I did briefly look into Mocha, but didn't get into it much.

I realize it's a big part of web development and even though I might not see the usefulness of it at my level, knowing about it and how it works is one of those things I just have to do.

I want to start with getting an understanding of what Unit Testing is then moving onto to how to use it with frameworks

## What is Unit Testing?

From wikipedia: 
> "In computer programming, unit testing is a software testing method by which individual units of source code, sets of one or more computer program modules together with associated control data, usage procedures, and operating procedures, are tested to determine whether they are fit for use."

I like the less verbose description of unit testing from [Fun Fun Function](https://www.youtube.com/watch?v=Eu35xM76kKY):
> "...a software development technique where you divide your software up into small isolated units and then you write automated test for those that verify that each unit works as expected"

From the research I've done so far, it seems like the main reason why Unit Testing exist is to make complex code more maintainable.

## Basic Example of Unit Testing

As I go through [Unit testing in JavaScript part 2](https://www.youtube.com/watch?v=XsFQEUP1MxI) I will try to apply the concepts in my own example:

```js
if (freeShipping({
    items: [
        { price: 2},
        { price: 4},
        { price: 6},
    ]
}) !== 12) {
    throw new Error('Check fail: Doesn\'t qualify for free shipping');
};

if (freeShipping({
    items: [
        { price: 2},
        { price: 2},
        { price: 2},
    ]
}) !== 6) {
    throw new Error('Check fail: Doesn\'t qualify for free shipping');
};
```

The above code is an example of **Test Driven Development**.  The *freeShipping()* function isn't defined yet, but a test is.  There are two test conditions that will throw in error if the function evaluates to a value < 12.

From [Unit testing in JavaScript Part 2](https://www.youtube.com/watch?v=XsFQEUP1MxI) Test Driven Development is when:
> ...we only write code when there exist a test that requires that code to exist.

So in this simple example, the above implementation would throw an error that *freeShipping()* does not exist.

> One part of unit testing is that you constantly try to put yourself in these situations where the next step becomes obvious.

By implementing the *freeShipping()* function, the original error goes away and a new error is throw, which are the errors defined in the testing conditions.

Following the principle of only writing code necessary for the test to pass, a simple return statement like below would theoretically satisfy the condition for the first test:

```js
function freeShipping(order) {
    return 12
}
```

This is obviously a hard coded value that doesn't check the object for the total price, but it is technically following the principles of TDD.

As a test to see if additional code is needed, there is a second conditional test.  Returning *12* from the freeShipping function would cause this test to throw an error, so additional code is needed to satisfy both test cases:

```js
if (freeShipping({
    items: [
        { price: 2 },
        { price: 4 },
        { price: 6 },
    ]
}) !== 12) {
    throw new Error('Check fail: Doesn\'t qualify for free shipping');
};

if (freeShipping({
    items: [
        { price: 2 },
        { price: 2 },
        { price: 2 },
    ]
}) !== 6) {
    throw new Error('Check fail: Doesn\'t qualify for free shipping');
};

function freeShipping(order) {
    return order.items.reduce((prev, curr) => curr.price + prev, 0);
}
```

Now both prices use the data from the passed in object to sum up the total price.  In this case, both values being tested against (check to see if total price is 12 and 6) are hard coded, but again it's a valid example of TDD.  At each step, only the necessary code is written to satisfy the testing conditions.

