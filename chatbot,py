# DeepushBot - A Simple Rule-Based Chatbot

def get_response(message):
    message = message.lower()

    # Predefined keyword-response map
    response_map = {
        "hi": "Hey! I'm DeepushBot. How can I assist you today?",
        "hello": "Hello there! Ask me anything about Tamizhan Skills courses.",
        "course": "We provide training in Python, Web Development, Data Science, and more.",
        "python": "Our Python course includes hands-on projects, from basics to advanced.",
        "web": "Our Web Development course covers HTML, CSS, JavaScript, and backend tools.",
        "fee": "Our courses are affordable. Visit our site for detailed fee structure.",
        "duration": "Courses typically range from 4 to 12 weeks depending on the topic.",
        "certificate": "Absolutely! You will receive a certificate upon successful completion.",
        "thanks": "You're welcome! 😊",
        "bye": "See you soon! 👋 Have a great day!"
    }

    # Match user input with keywords
    for keyword in response_map:
        if keyword in message:
            return response_map[keyword]

    return "I'm not sure how to respond to that. Try asking about our courses, fees, or duration."

def run_deepushbot():
    print("🤖 Hello! I’m DeepushBot – Your guide to Tamizhan Skills.")
    print("Type 'exit' anytime to end the chat.\n")

    while True:
        user_input = input("You: ").strip()
        if user_input.lower() == 'exit':
            print("DeepushBot: Thank you for chatting. Goodbye! 👋")
            break

        reply = get_response(user_input)
        print("DeepushBot:", reply)

# Start chatbot
run_deepushbot()
