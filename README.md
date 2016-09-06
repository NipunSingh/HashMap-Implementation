# HashMap Implementation in Java

## Background

  Wrote this as part of the [KPCB Fellows] (http://kpcbfellows.com/) application process. Was a Finalist in the KPCB Fellows program.  

## Design Choices

  Used seperate chaining to handle key collisions. Used a  LinkedList as the datastructure to handle the chaining.
  Used a load factor of 0.75 since empirically this gives the best peformance and is also what the standard HashMap uses in Java.

