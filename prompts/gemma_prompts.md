Prompt1 (Summarisation) 
Summarise the following text in one sentence: 
Machine learning is a subset of artificial intelligence that focuses on building systems that learn from data and improve their performance over time without being explicitly programmed.

Prompt2 (Summarisation) 
Summarise the following technical text in two sentences: 
Computer networks enable multiple devices to communicate and share data with each other over wired or wireless connections. They are built using layered architectures, such as the OSI and TCP/IP models, which divide communication tasks into manageable layers. Networking protocols like TCP, UDP, and HTTP define rules for data transmission, ensuring reliability, speed, and correct delivery. However, network performance can be affected by factors such as latency, bandwidth limitations, packet loss, and security vulnerabilities.

Prompt3 (Code Help1) 
Explain what the following Python function does in simple terms: 
def multiply_numbers(a, b): 
return a * b

Prompt4 (Code Help2) 
Refactor the following Python function to make it clearer and more readable: 
def calc(x,y):return x+y

Prompt5 (Code Help3) harder 
Explain what the following Python function does, refactor it for clarity, and generate unit tests using the built-in unittest framework:
def process_data(data):
    result=[]
    for i in range(len(data)):
        if data[i]%2==0:
            result.append(data[i]**2)
        else:
            result.append(data[i]*3)
    return result

Prompt6 (Structured output JSON) 
Extract the programming language and purpose from the following text and output valid JSON only: 
"This Python function calculates the total price including tax."
