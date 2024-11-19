## Deep Learning Project - Suren, Daniel, Mehjabin, Samad
## Neural Network Visualization

This repository provides a comprehensive visualization of the learning process in neural networks, encompassing feedforward calculations, error computation, and backpropagation for weight adjustment. This project enables the detection of errors at each layer of the network.

### Dataset

The project utilizes the `make_circles` dataset from the `sklearn` library.

### Project Structure

The project consists of three primary files:
- **main.py**: 
  - Defines the sequential model.
  - Implements two dense layers using ReLU and Sigmoid activation functions.
  - Utilizes the Adam optimizer for training.
  - Generates the datasets required for training and testing.

- **visualize.py**: 
  - Employs the Pygame library for visualization.
  - Integrates TensorFlow for model handling.
  - Sets the screen dimensions to 1000 pixels in width and height.
  - Defines properties such as color, radius, and value for each neuron.

### Neuron Class

```python
class Neuron:
    def __init__(self, x, y, radius, color, value, font_size=5):
        self.x = x
        self.y = y
        self.radius = radius
        self.color = color
        self.value = value
        self.font_size = font_size
```

- Neurons are represented in blue.
- The first layer contains 2 neurons.
- The second layer consists of 10 neurons.
- The third layer has 1 neuron.

### Network Initialization

```python
def awake(self):
        self.scene.append(Network(100, 530, 3, 18, (0, 0, 255), [linear, relu, sigmoid], [], 2, 10, 1))
```

### Visualizations

![model.png](model.png)
![network2.png](network2.png)
![network3.png](network3.png)

### Results

![charts2.png](charts2.png)
