Download Link: https://assignmentchef.com/product/solved-icsi404-assignment-1-the-bit
<br>
For this assignment, you need to create a class, called bit, to represent one bit. You must internally (private) use an integer to represent the one bit; the valid values are 0 (off) and 1 (on).

You must fully implement this interface (source file is provided): public interface IBit { void set(int value); // sets the value of the bit void toggle(); // changes the value from 0 to 1 or 1 to 0 void set(); // sets the bit to 1 void clear(); // sets the bit to 0 int getValue(); // returns the current value bit and(bit other); // performs and on two bits and returns a new bit set to the result bit or(bit other); // performs or on two bits and returns a new bit set to the result bit xor(bit other); // performs xor on two bits and returns a new bit set to the result bit not(); // performs not on the existing bit, returning the result as a new bit

@Override

String toString(); // returns “0” or “1”

}

You must implement the logic for these operations – you cannot use the logic (&amp;, &amp;&amp;, |, ||) operators for these operations. You may use “if” or “switch”.

You must provide a file (bit_test.java) that has a method (void runTests()). Each method of “bit” must be tested in bit_test.java. These tests could throw an exception on failure, print expected and actual values or print “pass” or “fail”, for example. The tests must be adequate to prove that your bit class really works. For example – not should test both cases (start with 0, not yields 1 and start with 1 and yield a 0). Your test cases should be independent of one another. You do not want one failed test to cause another failed test to occur. Your main method should call runTests on bit_test. There should be output that allows a grader to determine that the tests pass or fail. The graders will also have different tests that they will run.