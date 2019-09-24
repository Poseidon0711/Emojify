# Emojify
We are going to use word vector representations to build an Emojifier.
Have you ever wanted to make your text messages more expressive? Our emojifier app will help you do that. So rather than writing "Congratulations on the promotion! Let’s get coffee and talk. Love you!" the emojifier can automatically turn this into "Congratulations on the promotion! 👍 Lets get coffee and talk. ☕️ Love you! ❤️"

We will implement a model which inputs a sentence (such as "Let's go see the baseball game tonight!") and finds the most appropriate emoji to be used with this sentence (⚾️). In many emoji interfaces, we need to remember that ❤️ is the "heart" symbol rather than the "love" symbol. But using word vectors, we'll see that even if your training set explicitly relates only a few words to a particular emoji, our algorithm will be able to generalize and associate words in the test set to the same emoji even if those words don't even appear in the training set. This allows us to build an accurate classifier mapping from sentences to emojis, even using a small training set.

In this project, we’ll build a sophisticated model that incorporates an LSTM.

