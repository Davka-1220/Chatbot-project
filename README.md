print("Hello! I'm StudyBot. Ask me anything (type 'bye' to exit).")

while True:
    user_input = input("You: ").lower()
    
    if 'hello' in user_input:
        print("Bot: Hi there! How can I help you today?")
    elif 'your name' in user_input:
        print("Bot: I'm StudyBot, your personal assistant!")
    elif 'math' in user_input:
        print("Yeah! I can do math")
    elif 'english' in user_input:
        print("I know about english")
    elif 'bye' in user_input:
        print("Bot: Goodbye! Study hard!")
        break
    else:
        print("Bot: I'm not sure how to answer that. Try something else!")
