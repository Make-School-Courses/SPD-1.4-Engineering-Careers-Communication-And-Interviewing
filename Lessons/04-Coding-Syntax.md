# Coding Syntax & Conventions

### [Slides](https://docs.google.com/presentation/d/1vRFEyDCrktTXpN6N8KPltIfXnFtk6HYaSBXu6PjRFIw/edit?usp=sharing)

## Learning Outcomes

By the end of this class,  you should be able to...

1. Recall coding conventions and explain why they are important.
1. Recognize when important coding syntax and conventions have been broken to practice following them closely during technical interviews.

## Activity: Fix the Coding and Syntax Errors and Conventions (25 minutes)

### Part 1: FizzBuzz in JavaScript

Review this code snippet and find what’s wrong with it. What coding syntax errors does it have? Which conventions does it violate? How would you fix these?

Compare your results with 2-3 others and write down anything they caught but you had missed.

```js
function FizzBuzz(targetnum)
{
    for(var i=1; i<targetnum; i++;) {
        let result = "";
        if (i%3 === 0) result += "Fizz";
        if (i%5 === 0) result += "Buzz";
        if (i%3 > 0 & i%5 > 0) result = i
        console.log(result += "\n");
    }
}

FizzBuzz(50);
```

### Part 2: Stack class in Python

Review this code snippet and find what’s wrong with it. What coding syntax errors does it have? Which conventions does it violate? How would you fix these?

Compare your results with 2-3 others and write down anything they caught but you had missed.

```py
import Linked_List from "LinkedList.py"

class Stack:
    def _init_:
        this.List = new Linked_List();
    
    def push(newItem) :
        "Insert the given item on the top of this stack"
        // prepend given item before head node
        this.List.prepend(newItem , index = 0);
    
    def peek() :
        "Return the item on the top of this stack"
        if( this.List.head !== none ) {
            return(this.List.head.data[ 0 ]);
        }else{ return none; }
    
    def pop() :
        "Remove and return the item on the top of this stack"
        topItem=this.peek( );
        this.List.delete(topItem);
        return(topItem);
```

## Homework



## Wrap-Up

Fill out the [Vibe Check Form](https://forms.gle/3tCpS457XudkypmSA) with any thoughts & feelings from class today that you'd like your instructors to know.