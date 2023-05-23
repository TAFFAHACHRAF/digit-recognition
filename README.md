## Project Structure

The project is structured as follows:

```
C:.
├── README.md
└── V1
├── main.py
├── training.py
├── data
│ ├── sample_submission.csv
│ ├── test.csv
│ └── train.csv
└── model
├── W1.npy
├── b1.npy
├── W2.npy
└── b2.npy


5. Provide instructions on how to run the project. Include any dependencies or setup required.

6. If applicable, explain the architecture or algorithm used in your code. You can include diagrams, code snippets, or mathematical equations to enhance the explanation.

7. Document important functions, classes, or methods in your code. Describe their purpose, inputs, and outputs. Use code blocks or syntax highlighting to make the code snippets more readable. Here's an example:

```python
### `forward_prop(W1, b1, W2, b2, X)`

Performs forward propagation in the neural network.

**Arguments:**

- `W1`: Weight matrix for the first layer.
- `b1`: Bias vector for the first layer.
- `W2`: Weight matrix for the second layer.
- `b2`: Bias vector for the second layer.
- `X`: Input data.

**Returns:**

- `Z1`: Output of the first layer linear transformation.
- `A1`: Output of the first layer after applying the ReLU activation function.
- `Z2`: Output of the second layer linear transformation.
- `A2`: Output of the second layer after applying the softmax activation function.
