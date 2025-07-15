#  Toddler & Child Intent Dataset (MAMA v1)

This dataset contains 54,486 child utterances designed to support Natural Language Processing (NLP) tasks involving early childhood speech. It focuses on intent classification across a diverse range of everyday expressions by children.

The dataset is suitable for training models in child-friendly conversational AI, such as educational companions, assistive robots, or developmental research tools like the MAMA project.


## About the Dataset

The original dataset contained 9,100 utterances, collected over 2 years from children aged 2 to 10, including my son and four nephews. Conversations were observed and recorded in **natural environments**, such as homes and schools, during everyday activities.

Each utterance was manually categorized into one of the following **11 intent classes**:

- Complaint  
- Emotion  
- Comfort  
- Command  
- Refusal  
- Distress  
- Question  
- Desire  
- Need  
- Imitation  
- Gratitude


##Data Collection & Augmentation Process

###  Real-world Collection
- Utterances were captured during casual, real-life conversations with children in homes and school settings.
- The speech was transcribed naturally, preserving the vocabulary, tone, and phrasing typical for young children.

###  Augmentation via LLMs
To increase the dataset’s diversity and ensure class balance, manual augmentation was performed using ChatGPT and GitHub Copilot.

A sample augmentation prompt used:
 "I'm working on a dataset of children's statements across various categories and intents. I’ll be sending you individual statements from this dataset. For each statement, please generate 10 different augmentations that remain friendly, age-appropriate, and suitable for young audiences. Ensure that the variations preserve the original intent and tone, and reflect vocabulary and phrasing that children can easily understand."_

 All LLM-generated examples were reviewed and cleaned to maintain quality and developmental relevance.
After augmentation, the dataset expanded from **9,100 to 54,486 utterances**, with an even distribution across categories.





