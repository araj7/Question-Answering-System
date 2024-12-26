# Question Answering System

## Overview
The Question Answering System is a dynamic program designed to answer **Who**, **What**, **When**, and **Where** questions across any domain. It provides concise, complete sentences tailored specifically to the user's query.

Inspired by the approach used in the AskMSR system, this program reformulates questions into a series of "answer patterns" and searches Wikipedia for exact matches. The system ensures the responses are specific, contextually relevant, and derived from reliable sources.

---

## Key Features

### **1. Answer Pattern Matching**
The program transforms input questions into multiple answer patterns. For instance:
- Input: "Where is Malosky Stadium?"
- Reformulated Patterns:
  - "Malosky Stadium is located in..."
  - "Malosky Stadium is found in..."
  - "The address of Malosky Stadium is..."

This pattern-based search ensures a higher likelihood of finding precise answers.

### **2. Comprehensive Question Handling**
The system can handle various question types:
- **Who**: Identifies and provides information about people or entities.
- **What**: Explains concepts, definitions, or objects.
- **When**: Delivers time-based responses, such as dates or events.
- **Where**: Supplies location-based answers.

### **3. Intelligent Error Handling**
If no matching pattern is found, the system gracefully informs the user with a message: 
> "Answer not found."

### **4. Interactive User Experience**
The program operates interactively, engaging users until they decide to exit. Upon startup, it displays the following message:
> "Hello! This is a Question Answering System created by Amit Raj. Please type your query. If you are done, please type 'Exit' to leave the program."

Users can enter questions and receive accurate answers in natural language. The system ensures that answers remain focused and do not include extraneous information.

### **5. Logging and Transparency**
The program maintains a detailed log file, capturing:
- User queries
- Executed searches
- Raw results from Wikipedia
- Generated responses

This feature enhances traceability and allows users to review system performance.

---

## How It Works
1. **Input**: The user enters a question.
2. **Processing**:
   - The system reformulates the question into multiple answer patterns.
   - It searches Wikipedia for exact matches.
3. **Output**:
   - If a match is found, the system generates a complete and accurate response.
   - If no match is found, the system responds with: 
     > "Answer not found."
4. **Interaction**: The program continues to prompt for questions until the user types "Exit."

---

## Example Interaction
**User**: Where is Malosky Stadium?

**System**: Malosky Stadium is located in Duluth, Minnesota.

**User**: Who invented the light bulb?

**System**: The light bulb was invented by Thomas Edison.

**User**: Exit

**System**: Goodbye!

---

## Author
This program was developed by **Amit Raj** as a demonstration of practical question-answering capabilities using natural language processing and Wikipedia integration.

---

## Future Enhancements
- Support for additional question types such as "Why" and "How."
- Integration with other knowledge bases beyond Wikipedia.
- Enhanced natural language understanding for more complex queries.

---
