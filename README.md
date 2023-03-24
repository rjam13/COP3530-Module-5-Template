# Assignment 5
> # Dijkstra's Algorithm

In this assignment you will program Dijkstra's Algorithm using a custom graph class.

## Objectives

TODO #1: Implement the incidentEdges function in ExtendedGraph.java

TODO #2: Implement the initializeSingleSource function in Path.java

TODO #3: Implement the dijkstra function in path.java

This assignment will test your grasp on Dijkstra's algorithm.  
The steps are found within each function and it is your job to code it out.  

## Testing

* Testing can be done through Maven with the command, <br>
  `mvn test` <br>
* To run more specific tests, run the command <br>
  `mvn -Dtest=BinarySearchTree#TESTCASEHERE test` <br>
  where `TESTCASEHERE` is the test case you want to run. These test cases can be found in **src/test/java/BinarySearchTreeTest** <br>
  * For example,  `mvn -Dtest=BinarySearchTree#test_put test` tests your put method.

The results can be found in the command line or in **target/surefire-reports/BinarySearchTreeTest.txt** after execution.

**Part of grading will be these test cases.**

Alternatively,

To test your BST, the main() in TestBST.java creates an instance of your BST and tests it. It makes use of the printTreeStructure() method that we've provided on BinarySearchTree . This prints out the internal structure of the tree so you can verify your operations are behaving correctly.

