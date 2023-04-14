# Stacks and Queues Cheat Sheet

Stacks and Queues are data structures of `nodes` placed one after another. Each `node` holds a `value` as well as a reference to the `next` node in the stack/queue but it DOES NOT reference it's previous node.

Think of a Stack as a *vertical* arrangement of nodes and a Queue as a *horizontal* arrangement of nodes.

Stacks and Queues share some similar methodology but use different terminology

---

## Stacks

- **Push** : When a node is added to a stack, it is *pushed*

- **Pop** : When a node is removed from a stack, it is *popped*.

- **Top** : The top of the stack, i.e. the first node

- **Peek** : When we check the value of the top node, i.e. `return top.value`

- **isEmpty** : A method that checks to see if the top is `null` or not. If it is return `true`, if not return `false`.

- **FILO** : "First In Last Out"; The first item added in the stack will be the last item popped out of the stack

- **LIFO** : "Last In First Out"; The last item added to the stack will be the first item popped out of the stack.

Imagine a tower of blocks stacked on top of each other. The first block you place is at the bottom of the stack and as you `push` more blocks into the stack, the newest block is always at the top.

But now you want to start deconstructing your tower of blocks. So you remove the top most block, or the last block you added, from the stack - this is `LIFO`. When you've made it to the very last block and remove it from the stack - this would be `FILO`.

---

## Queues

- **Enqueue** : When a node is added to a queue, it is *enqueued*

- **Dequeue** : When a node is removed from a queue, it is *dequeued*

- **Front** : The front of the queue, i.e the first

- **Rear** : The rear of the queue, i.e. the last node

- **Peek** : When we check the value of the front node, i.e. `return front.value`

- **isEmpty** : a method that checks to see of the front is `null` or not.

- **FIFO** : "First In First Out"; The first item in the queue will be the first item out of the queue

- **LILO** : "Last In Last Out"; The last item in the queue will be the last item out of the queue

Imagine you're standing in line at a store. The *first* person in line gets rung up for their purchases and then leaves the store - `FIFO`. Now the next person steps forward and the process repeats itself until there are no more people standing in line - `LILO`. 