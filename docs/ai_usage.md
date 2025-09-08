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

# AI USE Log - Rosaling #4
Tool/model & version: Chat GPT 5
- What I asked for: I gave Chat GPT the code I had developed so far: With open ("rosalind 4 example file.txt", "r") as data:Rosalind_text = data.readlines() #print ("".join(rosalind_text)) for line in rosalind_text: print ("".join(rosalind_text[])) if line [] % 2 = 0. I then asked it to help me fix my code for only showing even lines 
- Snippet of prompt(s): "Help me fix this code. I am doing the following task A file containing all the even-numbered lines from the original file. Assume 1-based numbering of lines and I need help finding a command that will count the even lines :with open ("rosalind 4 example file.txt", "r") as data: rosalind_text = data.readlines() #print ("".join(rosalind_text)) for line in rosalind_text: print ("".join(rosalind_text[])) if line [] % 2 = 0
- What I changed before committing: I added a variable called individual and used the command enumerate as well. While I had the "if line % 2 = 0 , I had to go back and add line to prior lines where it was left off (as line was not assigned) and then edit it to: if individual % 2 == 0:. I also added the r.strip command at the end to get rid of extra lines.
- How I verified correctness (tests, sample data): I checked my code first using the sample file and ran the code on this. Once I double checked by comparing it to the actual contents of the file, I downloaded the real Rosalind data set and altered my code to accomodate this new file. I also asked it to show me an alternative way, although I didn't use this alternative code to verify similar results.
