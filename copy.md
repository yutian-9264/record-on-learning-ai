https://www.reddit.com/r/deeplearning/comments/i1so7x/comment/g01gkey/

[batchnormalized](https://www.reddit.com/user/batchnormalized/)：

I wholeheartedly disagree with the crowd that says you need a masters on the subject. I did an undergrad in physics and math but never even coded seriously, and currently I am an ML Engineer at a top tech company. Depending on your background it may be easier or harder to teach yourself but it is certainly possible. This is what I did, starting from never having programmed professionally:

1.  Get decent at Python. Get comfortable with the standard Data Science toolkit (I.e. Scikit-Learn, Pandas, NumPy, etc.)
2.  Find an undergrad ML course online and do enough of it to understand foundational ML algorithms and concepts (e.g. logistic regression and classification, SVM, Naive Bayes, K-Means, PCA, cross validation, bias vs. variance, stochastic gradient descent, etc.). You can also just read a book, I personally read the relevant parts of [Bishop’s book](http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop%20-%20Pattern%20Recognition%20And%20Machine%20Learning%20-%20Springer%20%202006.pdf).
3.  Read [“Hands-On Machine Learning with Scikit-Learn and Tensorflow”](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291) to solidify the connection between the theory and practice of ML and for a lighter intro to deep learning. Implement some basic models like the aforementioned plus tree based ensemble modes.
4.  Read [“The Deep Learning Book”](https://www.deeplearningbook.org/)’s first part dealing with foundational deep learning models.
5.  Pick an area of deep learning that you’re interested in. I picked CNNs to start. Read the papers under that section from [“Awesome Deep Learning Papers”](https://github.com/terryum/awesome-deep-learning-papers). I started with the oldest/most basic model (AlexNet) because it felt easier to grasp to start.
6.  Get access to a computer with a GPU, learn a DL framework (I started with Keras, it’s relatively simple to pick it up just from the docs and Stack Overflow). Look at their examples, look at other implementations of your model, and use them as templates to build your own. I personally built my own computer, and there are a lot of great guides online for how to build deep learning rigs at varying price points, like [this one](https://towardsdatascience.com/build-a-deep-learning-rig-for-800-4434e21a424f), [this one](https://towardsdatascience.com/how-to-create-your-own-deep-learning-rig-a-complete-hardware-guide-2bba792b001b), or [this one](https://medium.com/@nicksharvey/a-powerful-affordable-machine-learning-rig-for-2k-c96ce4bf16b8).
7.  Once you’ve code completed your model comes learning how to debug. Debugging in DL is it’s own skill. I learned a lot from following [Josh Tobin’s guide to debugging neural networks](http://josh-tobin.com/troubleshooting-deep-neural-networks.html).

After this last step I had gone from never doing ML to building working instances of AlexNet, GooLeNet, and ResNet. I am not currently implementing DQN (almost done!) and will likely implement a LSTM for a work project. After the AlexNet project I felt pretty comfortable with picking up a paper, figuring out how to implement it, and debugging it successfully.

Full disclaimer:

*   It’s taken me over 2 years to go from step 1 to step 7. I had to do it while also doing a full time job.
*   Halfway through that process I became a Data Scientist professionally which allowed me to refine my Python, shell scripting, and software engineering. (Never did DL at work though)
*   I have a very strong mathematical background which made it easier to pick up the theory.
*   I did a little bit of academic research in my undergrad so I was relatively comfortable reading and learning from academic papers.

I wouldn’t say I’m a deep learning expert but I feel comfortable that I can build a production DL application. Career-wise when I started step 1 I was a product analyst. After step 3 I was a data scientist, and right towards the end I became an ML engineer.