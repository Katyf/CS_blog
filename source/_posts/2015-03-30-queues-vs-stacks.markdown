---
layout: post
title: "Queues vs. Stacks"
date: 2015-03-30 18:08:26 -0400
comments: true
categories: Data Structures
---

Q: Queues and stacks are both types of data structures in computer science. So what is the difference between a queue and a stack?

First come, first serve. A queue is a collection of items (nodes) which are kept in a static order. Pricipal operations performed on a queue are enqueing, or adding to the end of the list, and dequeing, or removing from the front of the list. A queue is a FIFO (first in, first out) data structure, meaning that operations are performed on nodes based on the order they came into the queue. Much like a checkout line, the first item (or person) is the queue is the first thing to be taken out of the queue.

A stack is much like a queue, in that it is a collection of items kept in order. However, instead of a FIFO order of operations, stacks are a LIFO (last in, first out) data type. In other words, nodes are added to the end of a stack, but are also removed from the end of the stack.

Q: How are queues and stacks used?

Because of their strict usage pattern, queues and stacks help manage data in more particular and specific ways, contrary to the more flexible array or list. They have limited access, versus an array's random access.
