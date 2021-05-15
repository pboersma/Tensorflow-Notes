# Basic Tensorflow Functions
## Tensor Math Operations
- `tf.add(x, y)` - Adds two tensors of the same type, x + y.
- `tf.subtract(x, y)` - Subtracts tensors of the same type, x - y.
- `tf.multiply(x, y)` - Multiplies two tensors *element-wise* *.
- `tf.pow(x, y)` - Takes the element-wise x to the power of y.
- `tf.exp(x)` - Equivelant to `tf.pow(e, x)` where e the the Euler's number (2.718 ...).
- `tf.sqrt(x)` - Equivelant to `tf.pow(x, 0.5)`.
- `tf.div(x, y)` - Takes the element-wise division of x and y.
- `tf.truediv(x, y)` - Same as `tf.div()`, except casts the arguments as a float.
- `tf.floordiv(x, y)` - Same as `tf.truediv()`, except it rounds down the final answer into an integer.
- `tf.mod(x, y)` - Takes the element-wise remainder from division.


----
1. **Element-wise** - Also know as the Hadamard product is a binary operations that takes two matrices of the same dimensions and produces another matrix of the same dimension as the operands, where each element i, j is the product of elements i, j of the original two matrices
2. **Euler's number** - The number e, also known as Euler's number, is a mathematical constant approximately equal to 2.71828, and can be characterized in many ways. It is the base of the natural logarithm. It is the limit of ⁿ as n approaches infinity, an expression that arises in the study of compound interest 