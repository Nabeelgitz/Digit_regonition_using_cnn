## Challenges Faced & How We Overcame Them in Improving Accuracy & Efficiency  

### Challenges Faced:  
1. **Overfitting on MNIST** – Model performed well on training data but slightly worse on test data.  
2. **Computational Inefficiency** – Training took longer due to the large dataset and multiple convolutional layers.  
3. **Limited Generalization** – The model struggled with variations in custom handwritten images.  
4. **Low Accuracy on Noisy Images** – Slight distortion in digits led to misclassification.
    
### Solutions:
1. **Use Regularization to prevent overfitting of the model** 
2. **Increase epochs to for learning rate**
3. **Preprocess the data , normalize and resize it , to increase model accuracy**  
4. **Use data Augumentation , to get all expected data for model training** 
5. **Use one hot encoding to prevent numerical variance**


