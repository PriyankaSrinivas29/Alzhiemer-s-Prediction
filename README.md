# ALZHEIMER’S PREDICTION 
Alzheimer's disease (AD) is a progressive neurodegenerative disorder characterized by cognitive decline and memory loss. 
Alzheimer's disease is characterized by the accumulation of abnormal protein aggregates in the brain, including beta-amyloid plaques and tau tangles. These protein deposits lead to the degeneration and death of brain cells.

### ARCHITECTURE
The CNN model is constructed using a combination of convolutional blocks and normalization blocks.
Input layers: The input layer specifies the shape of the input images.
Initial convolutional layers : It extract features from the input images. Initial convolutional layers act as feature detectors, identifying simple patterns and structures in the input images.
Convolutional blocks (conv_block) consist of convolutional layers, batch normalization, and max-pooling.
Flatten Layer: After the convolutional layers, a flatten layer is used to convert the 2D feature maps into a 1D vector, preparing the data for the fully connected layers.
Normalization blocks (norm_block) consist of a dense layer, batch normalization, and dropout.

### METHODOLOGY
  Data Collection
  Importing Libraries
  Data Preprocessing Steps
  Data Augmentation for Enhanced Generalization
  Data Splitting for Training and Validation
  Building the Deep Learning Model and Compiling It
  Model Training and Validation
  Preprocessing for Prediction
  Prediction
