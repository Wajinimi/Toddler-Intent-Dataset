#  Contributing to the Toddler & Child Intent Dataset (MAMA v1)

First off, thank you for considering a contribution to this project. Your support helps us build better child-focused AI systems rooted in empathy, playfulness, and natural language.

This dataset is designed to reflect how young children (ages 2–10) naturally speak and express their needs, emotions, and intentions. Contributions should maintain that spirit.



## What You Can Contribute

You can help in several ways:

###  1. Add New Child Utterances
- Provide original or observed utterances from children aged 2–10
- Include an appropriate `intent` label (see intent list below)
- Ensure utterances are natural, friendly, and age-appropriate

###  2. Submit LLM Augmentations
- Use ChatGPT or similar tools to generate synthetic variations of existing utterances
- Stick to child-friendly tone and vocabulary
- Use prompts consistent with the original dataset methodology

###  3. Clean or Improve Existing Samples
- Spot typos or awkward phrasing? Feel free to suggest cleaner versions
- Help fix misclassified intents or ambiguous utterances



##  Intent Categories

Please label utterances using one of the following 11 categories:

- `Complaint`  
- `Emotion`  
- `Comfort`  
- `Command`  
- `Refusal`  
- `Distress`  
- `Question`  
- `Desire`  
- `Need`  
- `Imitation`  
- `Gratitude`

Descriptions for each category will be added in the near future. When in doubt, feel free to open an issue or ask before labeling.



## How to Submit Contributions

1. Fork this repo 
2. Create a new branch  
   Example: `add-new-utterances-emotion`
3. Add your data to `data.csv` (or propose changes)
4. Commit with a clear message  
   Example: `Added 15 new 'Desire' utterances from school conversations`
5. Open a Pull Request (PR)
   Please describe what you added/changed and why

##  Style Guide

- Use simple, toddler-friendly phrasing
- Utterances should sound natural-like something a real child would say
- Keep utterances short (1–15 words is ideal)
- No slang or sarcasm unless it's child-typical ("Nooo!", "Mine!", etc.)



##  Review Process

All contributions are reviewed to ensure:
- The language is age-appropriate
- Labels are consistent with the dataset's intent
- Augmented data doesn't introduce bias or unnatural phrasing


##  Example (LLM Augmentation Prompt)

> “I'm working on a dataset of children's statements across various categories and intents.  
> I’ll be sending you individual statements from this dataset.  
> For each statement, please generate 10 different augmentations that remain friendly, age-appropriate, and suitable for young audiences.  
> Ensure that the variations preserve the original intent and tone, and reflect vocabulary and phrasing that children can easily understand.”



##  Thank You

Your contributions help build AI systems that better understand and support young children.  
Whether you're a parent, educator, developer, or researcher, thank you for helping make this dataset better!

