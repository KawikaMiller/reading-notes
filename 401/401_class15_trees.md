# Binary Trees Explained

Imagine you're standing outside and there's a box at your feet. The box contains something, maybe it's a word or a number. You look forward and you notice you're actually standing at a fork in the road - one path leads left from the box and the other leads right. At the end of each of those fork paths there is another box with another something inside of it, and from that box there is another fork in the road. This pattern can keep repeating itself until you reach the end of a forked path with no box and no more paths forking from it.

This is basically how a binary tree works, where each box represents a node on the binary tree. Each node has two paths, a left or right path, which potentially leads to another node. And when you run out of paths/nodes you've reached the end of your tree.


Now imagine that you're The Flash and you're able to run down all of these paths and examine what's in every one of these boxes in the blink of an eye. That's essentially how traversing a binary tree works. We start at the very first box and follow a path all the way to the end, then come back up until there's an un-traversed path to go down and follow that until the end. Then you repeat this process until you've examined all of the boxes / nodes or until you've found a specific thing that you were looking for in the boxes.