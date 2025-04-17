# 🐶 Python OOP Challenge: Build Your Own Digital Pet

Welcome to this week's Python challenge! 🎉

In this challenge, you’ll be creating a virtual pet using Object-Oriented Programming (OOP) concepts in Python. This fun project will help you practice how to use classes, attributes, methods, and constructors.

## 🧠 Objective

The goal of this project is to create a class called `Pet` that will have the following attributes and methods:

### Attributes:
- **name**: the name of your pet
- **hunger**: an integer representing hunger level (0 = full, 10 = very hungry)
- **energy**: an integer representing energy level (0 = tired, 10 = fully rested)
- **happiness**: an integer (0–10)

### Methods:
- **eat()**: reduces hunger by 3 points (but not below 0), and increases happiness by 1.
- **sleep()**: increases energy by 5 points (but not above 10).
- **play()**: decreases energy by 2, increases happiness by 2, and increases hunger by 1.
- **get_status()**: prints the current state of the pet.

### Bonus 🎯
- **train(trick)**: teaches your pet a new trick and stores it in a list.
- **show_tricks()**: prints all learned tricks.

## 🚀 Team Member Responsibilities

Each member of our team will be responsible for specific parts of the project. Here are the tasks and assigned branches:

1. **Mpho** (Branch: `setup-python-GrpAssignment`)
   - Set up the repository, folder structure, and main files (`digitalPet.py`, `main.py`, `README.md`).

2. **Faith** (Branch: `feature-eat-method`)
   - Code and test the `eat()` method. This will reduce hunger and increase happiness.

3. **Derrick** (Branch: `feature-sleep-method`)
   - Code and test the `sleep()` method. This will increase energy.

4. **Lusanda** (Branch: `feature-play-method`)
   - Code and test the `play()` method. This will affect energy, happiness, and hunger.

5. **Yusuf** (Branch: `feature-train-method`)
   - Code and test the `train()` and `show_tricks()` methods. This will add functionality for training and showing learned tricks.

6. **Lesego** (Branch: `feature-get-status`)
   - Code and test the `get_status()` method. This will display the current state of the pet.

7. **Slyvester** (Branch: `feature-main-script`)
   - Create and test the `main.py` file, where the pet object will be created and the logic for the pet's activities will be executed.

8. **Rigde** (Branch: `feature-documentation`)
   - Add README updates, docstrings, and screenshots to explain the project and how to use it.

## 📋 Instructions for Running the Project

1. Clone the repository.
2. Navigate to the project folder in your terminal.
3. Run the `main.py` file to see your pet in action.

```bash
python main.py
