# recsys
Lecture materials for "recommender systems" @ http://www.masterdatascience.es. In this lecture, we build a recommender system from the scratch using different techniques.

## Libraries
- You might want to try [surprise](http://surpriselib.com) or
- Take a look to this repo about [recommenders](https://github.com/Microsoft/Recommenders) by Microsoft

  ```python
  A question a get a lot from people using Recommenders repo: What recommendation algorithm should 
  I use with my data? 

  Here's is a hack to get you started in less than 30 min.

  1. Go to the quick start examples. There you'll see a table of notebook examples including an algorithm, 
  dataset, environment and a short description.
  2. See which dataset is more similar to your data. For example, if you have e-commerce data, 
  there is Amazon, if you have text content, there is MIND, etc.
  3. Take your dataset and put it in the exact same shape as the data in the notebook. If you have more fields, 
  just ignore them for the moment.
  4. Run the notebook.

  You have just run a recommendation algorithm with your dataset and have your first baseline.

  Now you can iterate, include your whole dataset and start learning the details of the algorithm you are using.

  Hope this is helpful.
  ```
  by [Miguel Fierro](https://miguelgfierro.com)

- Association rules with [mlxtend](http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/association_rules/)
