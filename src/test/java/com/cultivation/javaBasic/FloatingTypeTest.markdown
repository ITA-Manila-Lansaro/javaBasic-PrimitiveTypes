# should_not_get_rounded_result_if_convert_floating_number_to_integer()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Casting one variable/object to another type. https://study.com/academy/lesson/how-to-convert-float-to-int-in-java.html
##### 2. Why the test failed at first?
    Answer: Because Integer.MAXVALUE doesn't match to the actual result
##### 3. Why you corrected the test that way?
    Answer: Because 2 is the result if you convert 2.75f to int 
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    

# should_judge_special_double_cases()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Knowing the different double functions and how to judge the number if it is infinity or NAN. https://www.tutorialspoint.com/java/lang/double_isinfinite.htm
##### 2. Why the test failed at first?
    Answer: Because method isInfinity and isNan doesn't return a right boolean that satisfy the assert
##### 3. Why you corrected the test that way?
    Answer: Because that's the right way to judge the double if it is infinite or Not a number
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    
# should_not_round_number_when_convert_to_integer()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Casting one variable/object to another type. https://study.com/academy/lesson/how-to-convert-float-to-int-in-java.html
##### 2. Why the test failed at first?
    Answer: Because Integer.MAXVALUE doesn't match to the actual result
##### 3. Why you corrected the test that way?
    Answer: Because 2 is the result if you convert 2.75f to int 
##### 4. Do you have further questions on this knowledge point?
    Answer: No

# should_round_number()
##### 1. What is the knowledge point of the test? Where is the official document to the knowledge point?
    Answer: Understanding Math.round. In workplace 
##### 2. Why the test failed at first?
    Answer: Because Long.MAXVALUE is not the expected value
##### 3. Why you corrected the test that way?
    Answer: Because that's the best available round method
##### 4. Do you have further questions on this knowledge point?
    Answer: No
    