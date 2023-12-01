# Codsoft-Task-2
# Simple Calculator using Tkinter

# Program Explanation:

The Python program is a simple calculator GUI application using the Tkinter library. It allows users to perform basic arithmetic operations (addition, subtraction, multiplication, division) and includes buttons for digits, decimal point, and equals. The calculator also has a clear button to reset the input.

# GUI Components:

1. **Display Screen:**
   - An `Entry` widget is used to display the input expression and the result.
   - The `StringVar` named `equation` is used to update the content of the display.

2. **Buttons:**
   - Buttons for digits (0-9), decimal point, and arithmetic operators (+, -, *, /) are created using the `Button` widget.
   - Each button triggers the `press` function when clicked, except for the '=' button, which triggers the `equal` function.
   - The buttons are arranged in a 4x4 grid using the `grid` method.

3. **Clear Button:**
   - A separate "Clear" button is provided to reset the input and clear the display. It triggers the `clr` function.

4. **Color Themes:**
   - The calculator supports two color themes: default and a custom theme. The `them` function is used to switch between these themes.

# Functions:

1. **press(num):**
   - Appends the pressed button's value to the `expression`.
   - Updates the display with the current expression.

2. **equal():**
   - Evaluates the expression using the `eval` function.
   - Displays the result in the entry widget.
   - If an error occurs during evaluation, it displays "Error."

3. **clr():**
   - Clears the current expression and updates the display.

4. **them():**
   - Switches between color themes for the calculator.
   - Updates the foreground (text) and background colors for the display and buttons.

# Color Themes:

- The default theme has a black foreground and white background.
- The custom theme has a dark blue foreground and light blue background.

# Running the Calculator:

1. The program starts by creating a Tkinter window with a title "My Calculator" and a size of 500x600.

2. It includes a display screen, buttons, and a clear button.

3. Users can interact with the calculator by clicking buttons to input digits and operators.

4. The "Clear" button resets the input.

5. The program uses the `eval` function to perform calculations, and any errors during evaluation are handled by displaying "Error."

# Color Theme Switching:

- The `them` function can be used to switch between the default and custom color themes by calling it when needed.

 # Requirements:

- Python 3.x
- Tkinter library (usually included with Python)


# Screenshots

![cal1](https://github.com/Srivarthaniselvam/Codsoft-Task-2/assets/151417502/c023d941-8e0b-41af-a462-e526dd8d2bbc)
![cal2](https://github.com/Srivarthaniselvam/Codsoft-Task-2/assets/151417502/c2237909-93a3-413a-9f96-bbe3abca8570)
![cal3](https://github.com/Srivarthaniselvam/Codsoft-Task-2/assets/151417502/24285fe6-b7a4-46a0-b109-2f41ed7a0e46)
![cal4](https://github.com/Srivarthaniselvam/Codsoft-Task-2/assets/151417502/09dd0e40-f00b-4b97-99eb-ca2a54e1974a)
![cal5](https://github.com/Srivarthaniselvam/Codsoft-Task-2/assets/151417502/856828dc-1ef2-4cb3-b1d5-42b2eca4556d)
![cal6](https://github.com/Srivarthaniselvam/Codsoft-Task-2/assets/151417502/80eb7c19-dc5e-43e8-907f-12f78211524e)

# License:

- This program is open source and can be modified and distributed under the MIT License.

Feel free to customize and enhance the calculator based on your preferences or requirements!
