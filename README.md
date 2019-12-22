# Good-reads

# Seven differences between academia and industry for building machine learning and deep learning models
post by ajit.j

Academia and industry take different approaches to building machine learning and deep learning models

 

Here are seven differences

1) Approach to accuracy: When you are in research or academia, you are focused on increasing accuracy (or some other metric) independent of the cost. An application with 95 percent accuracy may not behave much more differently than one with 96 percent accuracy. In industry, you need to consider the cost of adding that extra percentage especially if the users may not see any value in it

2) Training vs serving: When you are in research mode, you do not have to build and serve models many times. In production, you do. This means serving the model (the pipeline) is as important as training the model

3) Emphasis on Engineering: Extending the above, in commercial systems, the engineering focus (end to end pipeline) matters a lot. Thus, the role of data scientist is complemented with two other roles (the data engineer and the devops engineer)

4) Less emphasis on larger models: Massive models do not make ideal products. They are too expensive to train, too big to fit onto consumer devices, and too slow to be useful to users. In the research phase, you often do not care about the size of the model – but in real life you do.

5) Understanding the baseline: Choosing the baseline is important. On what factors do you choose the baseline and how do you quantify it? How can you show that your algorithm has improved the baseline

6) Understanding the intricacies of data: including privacy, bias and explainibility

7) And my favourite .. focusing on deep learning too early Deep learning models are often expensive to train and hard to explain. Most of the time, in production, they are only useful if their performance is unquestionably superior. Most real-world problems might not even need deep learning. Deep learning needs data, and to gather data, you might first need users. To avoid the catch-22, you might want to launch your product without deep learning to gather user data to train your system.

 
