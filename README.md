# Langchain-for-text-summary
Use openAI model and langchain for summary text, it can be from the website, text and pdf file.

Before you run the program, you need to get the openai API key, to get it :
1. Go to https://platform.openai.com/ and create an account (if you don't have an account)
2. After creating an account, log in to the website
3. Click Your profile picture, then click View API
   
![image](https://github.com/RaffelRavionaldo/Langchain-for-text-summary/assets/94748637/70c51cd6-e6e8-4a0c-a2b2-4ec1eff2c185)

4. After that click Create new secret key, give a name for your secret key then click the green button (Create secret key)
5. Copy your secret key and then paste it into the code (Remember: The secret key will appear once, so you can't see the secret key after you close the pop up, if you forget your secret key you can make another one)

Now you can run the program from summarised text file, Good Luck

# Langchain-for-text-summary
Just change the model from openAI to Llama from hugging face, because it's a free model. The results will not be as good as using openAI.

To use this, you need to get a hugging face access token on this : https://huggingface.co/settings/tokens

the output looks very long and write again the input text, it's because I set max_new_tokens to high, you can try to experiment by reducing it, The beginning of the summary starts with the words CONCISE SUMMARY
