## Lesson 5 - Concurrency

###Introduction


### Learning Objectives
- Know that computers can multitask i.e. do many things at once.
- Understand that a simple program has one flow of control i.e. one thread of execution but programs can have multiple threads of execution.

### Learning Outcomes

**All students will be able to:**

- Know that computers can do multiple things at once.




###Lesson Summary

-   Overview of the role of the control card and control flow. 
-   Introduction to threads.
-   Using threads to play sounds at the same time.

###Starter
Pupils are first invited to set up and connect their Raspberry Pi hardware. They may then load the Sonic Pi application and find their work from the previous lesson. Through questioning, select students to explain what they did in the previous lesson. 

###Main Development

1. Pupils are asked to form a simple line with the original computation cards and act out the program. Ensure that the control card is correctly handed down the line like a relay baton.
	beep
	```


	![alt text](threads.png "concurrency diagram")

	```ruby
	sleep 0.5 
	play 62 
	sleep 0.5 
	play 64 
	sleep 0.5 
	play 65 
	sleep 0.5 
	play 67 
	sleep 0.5 
	play 69 
	sleep 0.25 
	play 72
	```
	
