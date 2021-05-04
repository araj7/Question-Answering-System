# Question-Answering-System

The program answers Who, What, When and Where questions and is cabaple of handling questions from any domain. It provides answers in complete sentences
that are specific to the question asked. It takes an approach approach similar to that of the AskMSR system, and reformulates the question as a series of "answer patterns" and looks for it in Wikipedia, where one can find an exact match to one of the patterns.

For instance, if the question was "Where is Malosky Stadium?". the program can reformulate that question using the answer patterns "Malosky Stadium is located
in", "Malosky Stadium is found in" or even "The address of Malosky Stadium is". The program has multiple patterns associated with each possible type of question (Who, What, When, and Where) but, it only answers to questions for which an exact match is found to least one of the answer patterns. The program can recognize questions it can't answer and responds as **answer not found**.

The program runs interactively, and prompts the user for questions until the user says "exit". When the program starts it outputs this message "Hello! This is a question answering created by Amit Raj. Please type your query. If you are done, Please type 'Exit' to leave the program.". After that a user can enter his question and the system responds with an answer that is a complete sentence, and it does not contain any information beyond that which the user asked the question. I kept a log file that records the user’s questions, the searches that have actually been executed, the raw results obtained from Wikipedia, and finally the generated answer. 
