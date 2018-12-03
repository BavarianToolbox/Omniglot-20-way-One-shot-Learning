# Omniglot-20-way-One-shot-Learning
## Using a Siamese CNN to perform 20-way one-shot classification on 20 alphabets from the Omniglot data

This project was inspired by the [Fellowship.AI challenge problem](https://fellowship.ai/challenge/), and is for the most part a replication of this [Siamese Neural Net](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf).

Thanks and acknowledgements:
- [Koch el al](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf) for doing the legwork regarding model architecture and hyperparameter tuning
- [Brenden Lake](https://github.com/brendenlake) for preparing and supplying the Omniglot data
- [Lake et al](https://web.mit.edu/cocosci/Papers/Science-2015-Lake-1332-8.pdf) for their work on one-shot learning and human-level concept learning

## Installation Instructions

Running the training loop requires a significant amount of memory. I used a Paperspace instance with 30 GB RAM as well as a hefty GPU to accelerate training.

First clone the repo and install the dependencies.

```
git clone https://github.com/BavarianToolbox/Omniglot-20-way-One-shot-Learning
cd Omniglot-20-way-One-shot-Learning
sudo pip install -r requirements.txt
```

Then downloading and extracting of the data is all handled in the notebook, so now you're ready to roll. Run the notebook. Use the Python3 kernel and the latest versions of tesorflow and keras.

```
jupyter notebook
```

Happy learning!
