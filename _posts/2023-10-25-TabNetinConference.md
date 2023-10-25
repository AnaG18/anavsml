# Discussing TabNet and my first conference

I have a very exciting event coming up this weekend. I am officially part of a conference! 

For the first time I get to present a poster, which I am second author on, in a conference talking about biomedical engineering. It is actually
my second time presenting a poster I made in front of an audience in a very cool research experience at Carnegie Mellon's Robotics Institute
called [Robotics Institute Summer Scholars (RISS)](https://riss.ri.cmu.edu/). It was a very different experience with a different audience. 

This is also the first Biomedical Engineering Conference I attend so I am really excited! 

Not that it really matters, but I present at the [24th Annual Alberta Biomedical Engineering Conference](https://schulich.ucalgary.ca/biomedical/news-events/annual-alberta-biomedical-engineering-conference) on Saturday with the 31# poster from 
11 to 12:30. 

One of my main goals with this goal is to practice my writing and vocabulary skills as I often find myself struggling very bad to find
the right words to say. So, I will attempt to describe a key component in the research I am presenting which is TabNet! 

## What the hell is TabNet? 

As far as I can say, with very simple words, TabNet is a Deep Learning architecture for tabular data. 
Neural netwroks have proven to be super usfeul with data like image and audio (unstructured data), but it hasn't been outstanding while dealing with structured data. This is why 
TabNet makes a great breakthrough because it achieves really great performance for structured, tabular data while also bringing great interpretability of the decisions it takes. 

The key things I have understood it has are: *Batch Normalization*, *Feature transfomer*, *Attentive transformer* and *Masking*

A very simple diagram the flow of data through TabNet: 

Raw Input Data &rarr; Batch Normalization &rarr; Feature Transformer &rarr; N-STEP block &rarr; Feautre Importance and Output 

The STEP Block is configuration of the following: 
- Attentive Transformer
- Masking
- Feature Transformer
- Split
- ReLU (Rectifying Linear Unit)
