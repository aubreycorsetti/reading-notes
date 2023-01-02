# Day 7 Notes

## Stacks and Queues

### Implementation: Stacks and Queues

> **My Explanation**

Let's say you have 5 rainbow colored dishes with a number in a queue that you want to stack in a certain order.

1. First you want to check which plate number you want to add! (this will be called your Node) It looks like we want to add the #4 blue plate to the top. We will have the color of the plate be it's value.

2. Next, we want to stack the gray #5 plate on top. To do this we need to assign the next propert of plate #5 (Node #5) to the plate that is the highest up on the stack! (The #4 blue plate)

3. Good Job! Now your new gray #5 plate is added to your rainbow stack. Now we need to indicate that It's the top plate(Node) in the stack! To do this, we re-assign our top reference to the newest plate we added (plate #5/Node #5)

4. Yay! You did it! That is how you push a Node onto a stack.

> **Here is what that would look like in Python!**

### *Stack implementation using a list*

stack = []

### *Push elements onto the stack*

stack.append(1)

stack.append(2)

stack.append(3)

### *Print the stack*

print(stack)  # Output: [1, 2, 3]

### *Pop an element from the stack*

x = stack.pop()

print(x)  # Output: 3

print(stack)  # Output: [1, 2]

### *Queue implementation using a list*

queue = []

### *Enqueue elements*

queue.append(1)

queue.append(2)

queue.append(3)

### *Print the queue*

print(queue)  # Output: [1, 2, 3]

### *Dequeue an element*

x = queue.pop(0)

print(x)  # Output: 1

print(queue)  # Output: [2, 3]

> *Things I want to know more about*

I want to learn more about how to write effective code.

Click to return [Home!](../README.md)
