# should_perform_logical_boolean_operations()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Knowing the difference between Logical Operators and Bitwise operator. https://code.tutsplus.com/articles/understanding-bitwise-operators--active-11301
##### 2. Why the test failed at first?
    Answer: Because expectedResult variable is an empty array.
##### 3. Why you corrected the test that way?
    Answer: Because each of the array results to one, that is either True or False
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_do_bitwise_and_boolean_operation()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Knowing the bitwise with operator & on it. https://code.tutsplus.com/articles/understanding-bitwise-operators--active-11301
##### 2. Why the test failed at first?
    Answer: Because the comparator is 0. it doesn't match the expected result
##### 3. Why you corrected the test that way?
    Answer: Because comparing the value and mask with & will result to the current value of the expected variable. 
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_do_bitwise_or_boolean_operation()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Knowing the bitwise with operator | on it. https://code.tutsplus.com/articles/understanding-bitwise-operators--active-11301
##### 2. Why the test failed at first?
    Answer: Because the comparator is 0. it doesn't match the expected result
##### 3. Why you corrected the test that way?
    Answer:  Because comparing the value and mask with | will result to the current value of the expected variable. 
##### 4. Do you have further questions on this knowledge point?
    Answer: 
    
# should_do_bitwise_not_operation()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Knowing the bitwise with operator ~ on it. https://code.tutsplus.com/articles/understanding-bitwise-operators--active-11301
##### 2. Why the test failed at first?
    Answer: Because the comparator is 0. it doesn't match the expected result
##### 3. Why you corrected the test that way?
    Answer: Because if you put ~ on the value, it will negate the value of it. And the expected should be the current value oof the expected variable.
##### 4. Do you have further questions on this knowledge point?
    Answer: No