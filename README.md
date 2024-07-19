# build GPT-2 and GPT-3 and Training From Scratch
- [GPT-2 Paper Link](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
- [GPT-3 Paper Link](https://arxiv.org/pdf/2005.14165)

- This repo holds the from-scratch reproduction of the [GPT-2](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) (124M) model. This code can also reproduce the [GPT-3](https://arxiv.org/pdf/2005.14165) models. While the GPT-2 (124M) model probably trained for quite some time back in the day (2019, ~5 years ago), today, reproducing it You'll need a cloud GPU box.

- Note that GPT-2 and GPT-3 and both simple language models, trained on internet documents, and all they do is "dream" internet documents. For now this is the kind of stuff that the 124M model says if you prompt it with "Hello, I'm a language model," after 10B tokens of training:

```
Hello, I'm a language model, and my goal is to make English as easy and fun as possible for everyone, and to find out the different grammar rules
Hello, I'm a language model, so the next time I go, I'll just say, I like this stuff.
Hello, I'm a language model, and the question is, what should I do if I want to be a teacher?
Hello, I'm a language model, and I'm an English person. In languages, "speak" is really speaking. Because for most people, there's
```

And after 40B tokens of training:

```
Hello, I'm a language model, a model of computer science, and it's a way (in mathematics) to program computer programs to do things like write
Hello, I'm a language model, not a human. This means that I believe in my language model, as I have no experience with it yet.
Hello, I'm a language model, but I'm talking about data. You've got to create an array of data: you've got to create that.
Hello, I'm a language model, and all of this is about modeling and learning Python. I'm very good in syntax, however I struggle with Python due
```
### Training:
- At Initial stage of traing result comes like this:
![alt text](<Screenshot 2024-07-19 132322.png>)