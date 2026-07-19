# Custom Random Password Generator

A customizable Python script that generates secure, random passwords based on user-specified criteria. It allows you to define the exact minimum count of alphabets, digits, and special characters you want in your password.

## Features

* **Custom Character Counts:** Specify exactly how many letters, numbers, and symbols you want.
* **Smart Padding:** If the total requested length is longer than your specified character counts, the script fills the remaining length with a completely random mix of all character types.
* **High Entropy:** Shuffles the final character sequence to ensure the layout of letters, numbers, and symbols is completely unpredictable.
* **Input Validation:** Prevents errors by checking if your specified character counts exceed the total password length[cite: 1].

## Requirements

* Python 3.x

No external libraries are required, as the script relies entirely on Python's built-in `string` and `random` modules[cite: 1].

## How to Run

1. Clone or download this repository.
2. Open your terminal or command prompt and navigate to the project directory.
3. Run the script using the following command:

```bash
python "random password.py"
