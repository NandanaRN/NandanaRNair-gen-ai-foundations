# Question 1: The Vector Conflict

Yes, Sentence 1 and Sentence 2 showed some similarity even though the word "light" had different meanings. This happens because CountVectorizer only counts words and does not understand their meaning. Since both sentences contain the word "light", it considers them similar.

# Question 2: The Context Blindspot

The Bag-of-Words approach ignores the meaning and context of words. It only focuses on word frequency. Because of this, search engines or chatbots may misunderstand sentences when the same word has different meanings.

# Question 3: The GenAI Architectural Fix

Modern LLMs like GPT and LLaMA use self-attention and context-aware embeddings to understand word meanings. They look at surrounding words to determine the correct context. Therefore, the word "light" gets different vector representations based on its meaning in each sentence.
