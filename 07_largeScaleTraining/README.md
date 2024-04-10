## Homework 7 outputs

### Cerebras outputs
https://github.com/leannmlindsey/ai-science-training-series/blob/main/07_largeScaleTraining/mytest_1024.log

https://github.com/leannmlindsey/ai-science-training-series/blob/main/07_largeScaleTraining/mytest_512.log

https://github.com/leannmlindsey/ai-science-training-series/blob/main/07_largeScaleTraining/mytest_2048.log

Observations: The batch size of 512 finished faster than the batch size of 1024, while the batch size of 2048 had an error and was unable to finish.

### Graphcore outputs
https://github.com/leannmlindsey/ai-science-training-series/blob/main/07_largeScaleTraining/homework7.log


Accuracy on test set: 98.56%

I lowered the learning rate, increased the epochs and increased the batch size.

learning_rate = 0.01

epochs = 25

batch_size = 32

test_batch_size = 80 

### Sambanova outputs
https://github.com/leannmlindsey/ai-science-training-series/blob/main/07_largeScaleTraining/BertLarge.ntasks16.out

https://github.com/leannmlindsey/ai-science-training-series/blob/main/07_largeScaleTraining/BertLarge.ntasks4.out

Both models ended with an error, and although I tried many times, I always had the same error.  I would imagine that with less parallism, the overall execution time would increase.  

### Groq outputs
https://github.com/leannmlindsey/ai-science-training-series/blob/main/07_largeScaleTraining/groq_output.txt

I changed the input from dummy to custom.  The model ran with the same printed output with no errors.
