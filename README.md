# CodeAlpha_chatbot
This project is a simple rule-based chatbot built using Python. It interacts with users through text input and responds with predefined replies based on recognized phrases. The chatbot runs in a loop until the user types "bye", making it a great introduction to conversational programming.

here the the code for the project.

def chatbot():
    print("Welcome to the Chatbot! Type 'bye' to exit.\n")
    
    while True:
        user_input = input("You: ").lower()

        if user_input == "hello":
            print("Bot: Hi!")
        elif user_input == "how are you":
            print("Bot: I'm fine, thanks!")
        elif user_input == "bye":
            print("Bot: Goodbye!")
            break
        else:
            print("Bot: I don't understand that.")

chatbot()
