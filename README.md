# evolution-based-ai

## TODO

- research current evolution based algorithms
- define the environment

## The idea

Neural Networks are not intelligent, it's the process of training that is

I was thinking a lot about the idea of free will in human beings and I got to a conclusion that this crucial aspect of human cognition is most likely just a simple function, simple operation.
We attribute all our identity to this concept that is super simple - it's just decision maker, but the data that comes to it is complicated.
So I started wondering how are NNs trained these days. The problem is they are all focusing on gathering better and better datasets, improving the data, optimizing it. While it's the opposite that we should be focusing on. We should get rid of datasets completely and start training bottom-up.
The idea is that we start with a simple mech-microbe that doesn't know anything, it just lives and we deploy multiple of them and put in an isolated place where they have no information whatsoever. Then we add impulses and it either lives or not. Live and death are not to be implemented. They became a mechanism of their existance - we repeat evolution in some sense. They should develop fear of death autonomically as a group.
That is the problem - we see AI as a single entity, but what grants intelligence is not an individual property. Both: fear of death and intelligence are phenomena that are result from factors that spread beyond individual. For fear of death means losing information accumulated in a group, while intelligence being the process that selects. I hear you saying: evolution is not intelligent. I do not intend to argue something I don't know, what I'm pointing to is not to say that it is, but that result of whatever evolution is doing is intelligence. It is iterative process that operates on **spiecies** by exploiting **individuals** and develops intelligence on them. Intelligence emerges from authonomy and freedom, not vice-versa. What we need to emulate is evolution, not intelligence per say.

### Current architecture

This below is current model of AI.
```
         ______________
         |_____NN_____|
         |  datasets  |
input -> |architecture| -> output
         |  weights   |
         |____________|
_________________________________
        <---------------
backward propagation occurs only
during training/re-training/finetuning
and results in a stable NN
```

### New architecture

I propose that to achieve artificial intelligence, we need to move focus from a static NN trained in iterations on changing datasets to one that emphasizes input as a crucial element in operation of the NN and training faculty.

I propose that NN should have a fluid architecture. The layers must change action to action.
Input should be re-thought in sense that they should not have single type, but they should consist of "parameters" themselves.

Imagine following:

```

     inputA           ->         NN               ->    output
_________________         ____________________
parameter1_tensor          just architecture
parameter2_tensor            and weights
parameter3_tensor
      ...
                       <------------------------
                  back propagation coming from input
______________________________________________________________

```

Input technically is part of NN in above schema, but I distincted it for the sake of clarity, to emphasize the importance of the fact that input itself is a high-order-tensor that will be changing.
In terms of architecture the change is we remove static dataset as a source of training and instead unlock backpropagation for input data.
We replace emphasis of gathering **good datasets** with building **good set of input parameters**.
When I refer to input parameters I refer to types of information that is provided in input.
This in result influences NN architecture, so the Entity becomes more "fluid".
What changes is architecture and not the weights only, the whole model evolves.


### Autonomy

To ensure the model can autonomically redefine its architecture, we need to ensure 2 things:
- that it doesn't train (in an original sense of the word), but focuses specific architectural change (design change, rather than weights change, but maybe both)
- that it has mechanism to achieve above - that might require a detection model that provides parameters and addresses architectural change

In other words we want to achieve meta-training where model detects novel information and trains the other model to adjust for it.
We need to think about individual neural network models as "functions" instead of entire brains.
This is closer to the idea of synthetic data training, for the models should get rid of information that is not synthetic. The difference is that the synthetic data in this architecture serves is not supposed to improve model, but to be used to define specific function of the set of models.
How to achieve it is the big challenge.

```

____________________               _____________________________
| detection model  |------------>  | detected input parameters |
|__________________|               |  and model architecture   |
               ^                   |___________________________|
               |                      |
               |                      |
               x----------------------x
                Update knowledge tree
```


In this architecture, the "detection" model plays role of detection mechanism for the kind of interactions it has.
It contains a tree knowledge and if there's something new, it adjusts the "brain" model.
It differentiates from what is known and defines parameters for what is unknown.



