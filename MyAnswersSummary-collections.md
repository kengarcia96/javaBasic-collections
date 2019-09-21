# Answers Summary

## Questions to Answer
Please answer the following 4 questions for each unit test:
1. What is the knowledge point of the test? Where is the official document to the knowledge point?
2. Why the test failed at first?
3. Why you corrected the test that way?
4. Do you have further questions on this knowledge point?

## CollectionsTest

#### should_go_through_an_iterator / create_list
1. Use hasNext and Next Iterators for iterating an array list
https://www.cs.usfca.edu/~srollins/courses/cs112-f07/web/notes/iterators.html
2. It failed at first because the implementation is blank.
3. Corrected it by using while loop then iterate values came from iterator then add it in list.
4. None.

#### should_predict_linked_list_operation_result
1. Evaluate the use of ListIterator and its methods.
https://www.geeksforgeeks.org/arraylist-listiterator-method-in-java-with-examples/
https://www.javatpoint.com/java-listiterator-remove-method
2. It failed at first because the expected result is not correct and it is not the strings that has been added in the LinkedList.
3. Corrected it by evaluating the LinkedList and the ListIterator. Answer is Amy, Bob and Carl because Juliet was added but it has been removed also.
4. None.


#### should_reflects_back_to_original_list_for_sub_range
1. Learning in using sublist and clear methods.
https://www.geeksforgeeks.org/arraylist-sublist-method-in-java-with-examples/
2. It failed at first because the initial value is 0.
3. Corrected it by listing all the integers that was added, identify values included in the sublist and remove it from the whole list. The remaining is the expected answer
4. None.

#### should_create_a_sequence_without_putting_all_items_into_memory (Sequence)
#### should_generate_distinct_sequence_on_the_fly (DistinctIterable)

#### Sequence / SequenceIterator
1. Learn how to create and experience having own logic in a class like Sequence instead of using pre-defined or readily available commands in Java.
2. It failed at first the test related to this because the logic in the methods under the Sequence is missing.
3. Corrected it by evaluating and supplementing according to the requirement
4. None.

#### DistinctIteratable
1. Learn and create your own logic in Iterators
https://www.geeksforgeeks.org/how-to-use-iterator-in-java/
2. It failed at first the test related to this because the logic in the methods under the DistinctIteratable is missing.
3. Corrected it by evaluating and supplementing according to the requirement
4. None.

#### ArrayTest/MyStack
1. Learn and create your own logic in MyStack
https://www.callicoder.com/java-stack/
2. It failed at first the test related to this because the logic in the methods under the MyStack is missing.
3. Corrected it by evaluating and supplementing according to the requirement. 
Push values into array storage, accessing array through using increment count. Ensure Capacity means once it reached the limit, array storage needs to expand capacity by x2 of its original so I created a logic on that by putting the present array storage values in temporary array. 
Then expand the storage array. Then as per test requirement, Stack needs to be pop and put into separate array so I created in pop section way to access the last pushed variable in order to be put first in the new array.
4. None.
