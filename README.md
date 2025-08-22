# Evolution-of-Egyptian-Hieroglyphs-and-Sentiment-Analysis

## Project Aim 

This repository is a seed project that I would like to develop further into a PhD proposal. The idea behind sharing it here is to make the work accessible and to encourage collaboration with people who may find this project interesting. In particular, I hope to connect with researchers in Egyptology, linguistics, and data science who may see potential in combining their expertise with mine to expand on what has been started here.

The contents of this repository began as undergraduate coursework, but I personally feel like the core idea goes beyond a university assignment. It is an exploration of how sentiment analysis, a popular technique in natural language processing can be applied to hieroglyphs in order to trace how the expression of emotions evolved over time in Ancient Egypt. By opening this work, I want to invite discussion, improvement, and interdisciplinary contributions, since research is never done in isolation and grows better when shared.

The repo currently contains a mix of research notes, the original coursework, and some early code I worked on (within the deadline). These represent the first steps in a hopefully much larger direction, and are here both as a record of origin and as an open invitation for collaboration.


## Introduction 

Ever since the discovery of the Rosetta Stone, a decree written in three different scripts, the way hieroglyphs were understood has completely changed. What was once seen as purely unreadable art ended up being recognised as a system of communication that represented phonemes used in Ancient Egypt. The term for the hieroglyphic writing system literally meant “sacred carvings” in Greek (Remler, 2010, p. xi). This discovery suggested that hieroglyphs had their own tone, structure, and grammatical system, but it also provides us with insights into the rituals that were practiced and the lives people led. In this sense, hieroglyphs not only represent the surrounding environment but also offer psychological glimpses into the minds and emotions of individuals who lived thousands of years ago (Ray, 1999, p. iv).

In this research, we focus particularly on the psychological and emotional aspects of the hieroglyphic system by using a popular NLP (Natural Language Processing) technique called sentiment analysis. In today’s highly online world, sentiment analysis plays a crucial role in driving businesses based on customer feedback and reactions to increase overall profit. It is the ability to categorise the emotional tone of characters into various sentiments (like Positive, Negative, and Neutral) to understand the emotional reactions of people based on certain actions taken or done. Sentiment analysis is so powerful that it even drives national and international decisions, simply by analysing how people react and adjusting accordingly. It is safe to say that this technique plays a crucial role in shaping systems of our everyday life to favour us.

Recently, there has been a rise in the trend of using these modern techniques of NLP and data mining, like sentiment analysis, on ancient texts. This not only helps us understand the emotional tone intended to be expressed but also interpret these texts from various languages more accurately without “dumbing them down,” while retaining the complexity of the emotions conveyed when translating or interpreting them. An example of sentiment analysis on ancient texts is poetry in Ancient China. Words in Ancient Chinese are composed of characters called hanzi, which, when tokenized, are discrete in nature. Yet despite their discrete form, the morphemes interwove to create complex imagery and personification that expressed emotions through symbolic meaning (Liu et al., 2024). Similarly, in Ancient Egypt, each hieroglyph, apart from being a form of art, also represented the expression of complex emotions through the discrete nature of these symbols interwoven to form whole sentences, paragraphs, stories, documentation, and even decrees.

In this research, performing sentiment analysis on major texts from the Old Kingdom to the Late Period can give us an idea of how the use of hieroglyphs changed over time and why. With sentiment analysis, we may be able to interpret why the glyphs evolved based on their surroundings and how the purpose of documentation shifted across periods. It can give us insight into what people prioritised, how external situations affected their psychology, and how this could have created the necessity to adapt the hieroglyphic system from one Kingdom to another for various purposes. This research tries to answer three main questions: first, is it possible to detect positive, neutral, and negative emotional tones in transliterations of ancient Egyptian hieroglyphs using simple machine learning models? Second, how does the emotional tone of hieroglyphic texts change over time across the three major kingdoms? And third, are there clear patterns of emotional expression linked to the purpose or type of text, such as religious writing compared to more personal or casual writing?


## The Coursework 

In my second year of university, in a Data Mining module, we were expected to develop a research proposal using text analytics methods and had full leverage to use LLMs (Large Language Models) such as ChatGPT. In the appendix of the coursework, we were required to give examples of the prompts used, with screenshots to support our statements. The coursework itself used a fair amount of AI, from building the dataset to correcting grammatical mistakes and checking whether the flow made sense. The research proposal goes into great detail on the pilot study conducted, the methodology, and the potential risks of using AI and other data mining techniques. It also acknowledges that AI can hallucinate, and therefore the results in this coursework could be entirely inaccurate.

This attempt at sentiment analysis was also selected for an undergraduate research conference within my university, where the ideas documented here - both the coursework and the additional reflections in this repository were presented and discussed. That experience encouraged me to continue developing the project and to consider its potential as a future PhD proposal.

When I started this coursework, I was really new to Ancient Egypt, save hieroglyphs and the complex intricacies that language offers. Because of this, and due to time constraints, the basic pilot study was conducted on English translations. Later on, I came across CLTK, which I realised would have been a far better tool than NLTK (which is currently used in the coursework). Still, I wanted to include the seed of origin of this idea, as I believe research is an ever-evolving process, and I wanted to keep note of the starting point for supporting both research integrity, Feminist AI principles, and for my own future reference to look back on.


### About the Dataset in the Coursework

- The dataset was made with the help of ChatGPT. It was prompted to produce a dataset consisting of key text which showed sentiments from different dynasties.
- Later the Reasoning feature was used to check if the transliterations were close to being correct (at least to ChatGPT) to the texts it provided.
- The dataset may not be accurate at all. I am no expert in the Ancient Egyptian language. The transliterations provided are purely AI's (ChatGPT in this case).
- I made some attempts to find transliterations and their corresponding English texts - but access to such documents were limited due to a requirement for subscriptions, or some of it was not accessible at all even after a lot of searching for databases.














