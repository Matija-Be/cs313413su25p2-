COMP 313/413 Project 2 Report Template

TestList.java and TestIterator.java

	TODO also try with a LinkedList - does it make any difference?

		 - it does not make a difference.

TestList.java

	testRemoveObject()

		list.remove(5); // what does this method do?

			 - It remove the value that is at index 5

		list.remove(Integer.valueOf(5)); // what does this one do?

			
    - It removes the integer 5

TestIterator.java

	testRemove()

		i.remove(); // what happens if you use list.remove(77)?

        Does not work 

TestPerformance.java

	State how many times the tests were executed for each SIZE (10, 100, 1000 and 10000)
	to get the running time in milliseconds and how the test running times were recorded.

	SIZE 10
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:   456  374  493  328  427  348  ... (fill these in in ms)
        testLinkedListAddRemove:  391  327  298  368  316  321  
		testArrayListAccess:      343  301  301  322  309  334  
        testLinkedListAccess:     295  342  356  359  309  292 

	SIZE 100
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:   571  381  318  302  351  348  ... (fill these in in ms)
        testLinkedListAddRemove:  334  286  377  293  280  305  
		testArrayListAccess:      324  322  281  340  277  278  
        testLinkedListAccess:     301  352  339  350  292  389

	SIZE 1000
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:   289  300  339  301  339  312  ... (fill these in in ms)
        testLinkedListAddRemove:  309  322  318  335  348  268
		testArrayListAccess:      343  298  333  368  287  340  
        testLinkedListAccess:     302  298  277  306  275  332 

	SIZE 10000
								  #1   #2   #3   #4   #5   #6 	... (as many tests as you ran)
        testArrayListAddRemove:   354  367  289  291  292  309  ... (fill these in in ms)
        testLinkedListAddRemove:  278  299  309  290  311  230
		testArrayListAccess:      327  282  359  290  279  284 
        testLinkedListAccess:     312  303  313  401  339  324 

	listAccess - which type of List is better to use, and why?

		The Array had a better Acces becuase they are able to start from the beggining, middle, or end of the array to find the value. 

	listAddRemove - which type of List is better to use, and why?

        The Linked List had a better time regarding adding and removing becuase they have a more linear time when removing or adding with a linked list. 
		




