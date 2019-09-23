### should_get_range_of_primitive_int_type()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to be aware of MAX_VALUE and MIN_VALUE for int

2.Why the test failed at first?
* Because of the lack of expected result

3. Why you corrected the test that way?
* Because the given represents Integer.MAX_VALUE and Integer.MIN_VALUE

4. Do you have further questions on this knowledge point?
* No questions so far.


### should_get_range_of_primitive_short_type()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to be aware of MAX_VALUE and MIN_VALUE for short

2.Why the test failed at first?
* Because of the lack of expected result

3. Why you corrected the test that way?
* Because the given represents Short.MAX_VALUE and Short.MIN_VALUE

4. Do you have further questions on this knowledge point?
* No questions so far.



### should_get_range_of_primitive_long_type()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to be aware of MAX_VALUE and MIN_VALUE for long

2.Why the test failed at first?
* Because of the lack of expected result

3. Why you corrected the test that way?
* Because the given represents Long.MAX_VALUE and Long.MIN_VALUE

4. Do you have further questions on this knowledge point?
* No questions so far.



### should_get_range_of_primitive_byte_type()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to be aware of MAX_VALUE and MIN_VALUE for byte

2.Why the test failed at first?
* Because of the lack of expected result

3. Why you corrected the test that way?
* Because the given represents Byte.MAX_VALUE and Byte.MIN_VALUE

4. Do you have further questions on this knowledge point?
* No questions so far.



### should_overflow_silently()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is that overflow does not cause errors but the result may not be the expected one.

2.Why the test failed at first?
* Because of the incorrect expected result

3. Why you corrected the test that way?
* Because when MAX_VALUE is incremented, it will cause it to overflow and reset to the MIN_VALUE or zero

4. Do you have further questions on this knowledge point?
* No questions so far.



### should_underflow_silently()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is that underflow does not cause errors but the result may not be the expected one.

2.Why the test failed at first?
* Because of the incorrect expected result

3. Why you corrected the test that way?
* Because when MIN_VALUE is decremented, it will cause it to underflow and reset to the MAX_VALUE

4. Do you have further questions on this knowledge point?
* No questions so far.



### should_throw_exception_when_overflow()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to catch occurences that will overflow

2.Why the test failed at first?
* Because add() is not yet implemented

3. Why you corrected the test that way?
* Because there is built in function using Math.exact()

4. Do you have further questions on this knowledge point?
* No questions so far.



### just_prevent_lazy_implementation()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to catch occurences that will overflow

2.Why the test failed at first?
* Because add() is not yet implemented

3. Why you corrected the test that way?
* Because there is built in function using Math.exact()

4. Do you have further questions on this knowledge point?
* No questions so far.



### should_take_care_of_number_type_when_doing_calculation()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is the different number types

2.Why the test failed at first?
* Because of the lack of expected result

3. Why you corrected the test that way?
* Because of the existing logic for integer division and multiplication

4. Do you have further questions on this knowledge point?
* No questions so far.



### should_truncate_number_when_casting()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is the different number types

2.Why the test failed at first?
* Because of the lack of expected result

3. Why you corrected the test that way?
* Because of the existing logic for getting short value for integer

4. Do you have further questions on this knowledge point?
* No questions so far.



### should_increment()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is the different ways of incrementing a variable

2.Why the test failed at first?
* Because of the lack of expected result

3. Why you corrected the test that way?
* Because of the existing logic for implementation of var++

4. Do you have further questions on this knowledge point?
* No questions so far.



### should_increment_2()
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is the different ways of incrementing a variable

2.Why the test failed at first?
* Because of the lack of expected result

3. Why you corrected the test that way?
* Because of the existing logic for implementation of ++var

4. Do you have further questions on this knowledge point?
* No questions so far.
