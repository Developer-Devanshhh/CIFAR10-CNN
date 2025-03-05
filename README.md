# CIFAR-10 Image Classification with Deep Learning


### 1) CNN Model
- Used Conv2D, MaxPooling2D, Flatten, Dense, Dropout, and Batch Normalization layers.
- Applied ReLU activation for non-linearity and Softmax for classification.

### 2) Data Preprocessing & Augmentation
- Normalized pixel values to [0,1].
- Applied Data Augmentation (rotation, flipping) for better generalization.
        
### 3) Training and Validation
- Used Categorical Crossentropy as the loss function.
- Optimized using Adam optimizer.
- Trained the model for 30 epochs with early stopping to prevent overfitting.
      
### 4) Evaluation
- Plotted accuracy & loss curves to analyze model performance.
- Calculated Precision, Recall, F1-score, and Overall Accuracy.
        
  
  ## Results: 77% accuracy
