# ProducerConsumerProblem

Producer- Consumer Problem

Project Information
Title: Producer Consumer Problem
Group No.: Project 32
Members: 
Neel Patel       (SJSU ID: 012468599)
Tanmay Jambhekar (SJSU ID: 012525188)


Abstract

Producer-Consumer Problem is a classic example of multi-process synchronization problem. It presents two processes (Producer and Consumer) 
sharing the same buffer used as a queue. The Producer generates data and puts it in the queue and at the same time consumer takes data out 
of the queue. The problem arises when the producer tries to add data when the buffer is full, or the consumer tries to take data when the 
buffer is empty. This project is about finding a solution to the producer – consumer problem using a bounded buffer presented in the textbook.  The project uses standard counting semaphores to represent mutex and mutex lock rather than using binary semaphores. The aim is 
to have the producer and consumer, running on separate threads to move items to and from a buffer that is synchronized with empty, full 
and mutex locks. This results in prevention from synchronization error and deadlocks.
