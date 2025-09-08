# AI Use Log - Rosalind #3
- Tool/model & version: Gemini (Built into Colab latest version)
- What I asked for: An automatic error : Gemini error told me: TypeError: 'int' object is not iterable; 
- Snippet of prompt(s): This error insinuates I was missing something that Colab could loop. It prompted me to assign a variable named "odd_sum = 0"
- What I changed before committing: I went to chat GPT to further explore this error and why it would want me to do this. (See next entry)
- How I verified correctness (tests, sample data): (I went to chat GPT to further explore this error.)


# AI Use Log - Rosalind #3
- Tool/model & version: Chat GPT 5
- What I asked for: I asked Chat GPT what is Odd_Sum and how to use that to complete adding the sum of my odd numbers in the code I had generated so far. 
- Snippet of prompt(s): "What is += doing and is odd_sum a built in command?" and "So how would I use this for the code I've generated here: ros_range = 201 for number in range(ros_range): if number % 2 == 1: odd_sum"
- What I changed before committing: I assigned odd_sum = 0  and then added: odd_sum += number and print(odd_sum) on lines 5 and 7 respectively. 
- How I verified correctness (tests, sample data): I checked my code by removing the faulty parts and runnning the code. It produced a list of all the odd numbers. I added the new functions and it produced a sum. My answer was correct on first attmept with Rosalind. I know now I can subsitute any value for the range function and the code should run the same for odd related problems.
