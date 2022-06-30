Tutorial
--------
### The Linked List Data Structure

A linked list is a linear data structure similar to an array, but the elements are stored in a way such that each element is a seperate object which contains a pointer to next element/object in the list

Each element of a linked list can be called as `Node` and `head` is a reference to the first element/Node in the linked list , if a list is Empty then the head of the list should be null and to indicate the end of the list the next value of the last element points to null 

There are many types of linkedlists but in this tutorial we are going to discuss about singly linkedlist

Each Element/Node of a linkedlist would be

     class Node{
          
     constructor(val) {

          this.next = null;
          this.data = val;

     }
     };

     
### Creating a list

Suppose you want to construct a linked list of size `n`, then you should create n node's and interlink them with the help of `next` member in the class Node of Each element