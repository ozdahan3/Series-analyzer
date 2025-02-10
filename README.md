
# Series Analyzer 🏆

## Overview
Series Analyzer is a Bash script that allows users to input a series of numbers and analyze their properties. The script provides an interactive menu with options to sort the series, find the maximum and minimum values, calculate the average, count the elements, and compute the sum. 

## Features 🚀
✅ Accepts a series of at least **three** positive numbers  
✅ Validates input to ensure all values are **non-negative numbers**  
✅ Displays the series in both **original** and **sorted order**  
✅ Computes **max, min, sum, average, and count** of the series  
✅ Provides an **interactive menu** for easy navigation  
✅ Handles **invalid inputs gracefully**  

## Installation 📥
No installation is required! Just download the script and give it execution permissions.

```bash
chmod +x series_analyzer.sh
```

## Usage 🖥️
Run the script by executing:

```bash
./series_analyzer.sh
```

You can also pass numbers as **command-line arguments**:

```bash
./series_analyzer.sh 10 5 8 3 12
```

## Menu Options
- `1.` Input a new series
- `2.` Display the series (original order)
- `3.` Display the series (sorted order)
- `4.` Find the maximum value
- `5.` Find the minimum value
- `6.` Calculate the average
- `7.` Count the number of elements
- `8.` Compute the sum
- `9.` Exit the program

## Example Output 📝
```
Welcome to the series analyzer menu:
1. Input a Series (Replace the current series)
2. Display the series in the order it was entered
3. Display the series in sorted order (from low to high)
4. Display the Max value of the series
5. Display the Min value of the series
6. Display the Average of the series
7. Display the Number of elements in the series
8. Display the Sum of the series
9. Exit
Enter your choice (1-9): 
```

## Requirements ⚡
- Bash Shell (Linux/macOS)

## Notes ℹ️
🔹 The script uses **global variables** to store the series, which may lead to potential scope conflicts. Consider modifying it to use **local variables** for better encapsulation.  

🔹 The script supports **decimal numbers**, but ensure input values are formatted correctly.

## License 📜
This project is open-source and available under the MIT License.

---
👨‍💻 **Created by [Oz Dahan](https://github.com/ozdahan3)**
