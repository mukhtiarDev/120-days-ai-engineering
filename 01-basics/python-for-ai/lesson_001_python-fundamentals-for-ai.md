

Day 1 of 120: Python Fundamentals for AI Engineering

Python is the number one language for AI because of its simplicity and massive ecosystem.

Key concepts you must know today:
- Variables and data types: int, float, str, bool, list, dict, tuple
  - int: Whole numbers like epochs = 10
  - float: Decimals like learning_rate = 0.01
  - str: Text like model_name = "GPT-4"
  - bool: True/False states like is_trained = True
  - list: Changeable collections like layers = ["conv", "relu", "pool"]
  - dict: Key-value data like metrics = {"loss": 0.23, "accuracy": 0.94}
  - tuple: Unchangeable structures like input_shape = (224, 224, 3)
- Control flow: if and else, for loops, while loops
  - if/else: Runs code conditionally (e.g., if loss < 0.1: stop_training())
  - for loops: Iterates through sequences (e.g., looping over items in a list)
  - while loops: Runs continuously until a targeted condition evaluates to False
- List comprehensions: clean one-line loops
  - Short inline syntax to create new lists from existing sequences dynamically
- Functions: def, return, default arguments
  - Reusable code blocks made with 'def', sending outputs back using 'return'
- Error handling: try and except blocks
  - Catches bugs or bad data safely during runtime to prevent immediate crashes

Why Python for AI?
NumPy, PyTorch, TensorFlow, LangChain, HuggingFace are all Python.
Fast to write. Huge community. Best library support on the planet.

Real example:
data = [1, 2, 3, 4, 5]
squared = [x * x for x in data]
# Result is [1, 4, 9, 16, 25]

Practice today: Write a function that takes a list of numbers and returns the mean, min, and max.

# Complete executable solution code:
def calculate_stats(numbers):
    if not numbers:
        return None, None, None
    try:
        mean_val = sum(numbers) / len(numbers)
        min_val = min(numbers)
        max_val = max(numbers)
        return mean_val, min_val, max_val
    except TypeError:
        return "Error: The list must contain only numbers."

# Testing the code
data_sample = [1, 2, 3, 4, 5]
mean, minimum, maximum = calculate_stats(data_sample)
print(f"Mean: {mean}, Min: {minimum}, Max: {maximum}")

Day 1 complete. 119 days to go.

#Python #AIEngineering #Day1of120 #LearningInPublic
