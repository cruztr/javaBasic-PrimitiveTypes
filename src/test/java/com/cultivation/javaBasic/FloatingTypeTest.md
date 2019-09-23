### should_not_get_rounded_result_if_convert_floating_number_to_integer()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to convert float to integer

2.Why the test failed at first?
* Because of the lack of input expected result to convert float to integer

3. Why you corrected the test that way?
* I used the floor function to get the integer part

4. Do you have further questions on this knowledge point?
* No questions so far.


### should_judge_special_double_cases()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the tests is to identify infinity and NaN values without errors

2.Why the test failed at first?
* Because there is no implementation for isInfinity and isNaN methods

3. Why you corrected the test that way?
* I used the isInfinity and isNan methods of Float

4. Do you have further questions on this knowledge point?
* No questions so far.


### should_not_round_number_when_convert_to_integer()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to convert float to integer without rounding

2.Why the test failed at first?
* Because of the lack of input expected result to convert float to integer

3. Why you corrected the test that way?
* I used the Math.floor function to get the integer part and typecasted it to int

4. Do you have further questions on this knowledge point?
* No questions so far.


### should_round_number()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to convert float to integer with rounding

2.Why the test failed at first?
* Because of the lack of input expected result to convert float to integer

3. Why you corrected the test that way?
* I used the Math.round function to get result

4. Do you have further questions on this knowledge point?
* No questions so far.