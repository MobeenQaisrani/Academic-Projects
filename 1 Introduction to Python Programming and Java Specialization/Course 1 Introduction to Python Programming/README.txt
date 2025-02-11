# 🐶 Dog Age to Human Age Calculator  

This Python program calculates a dog's age in human years based on specific conversion rules. It validates user input and provides appropriate responses for incorrect values.

---

## 📌 How It Works  
- Prompts the user to enter a dog's age in years.  
- Checks if the input is valid (numeric and positive).  
- Uses predefined conversion rules to determine the human age.  
- Displays the result in the format:  
  **"The given dog age X is Y in human years."**  
- Rounds the result to **2 decimal places**.  
- Handles invalid inputs:  
  - If the input is text-based → prints a message containing **"invalid"**.  
  - If the input is negative → prints a message containing **"negative"**.  

---

## 🛠 Conversion Rules  
| Dog Years | Human Years (Per Dog Year) |
|-----------|----------------------------|
| 1st Year  | 15 Years                   |
| 2nd Year  | 12 Years                   |
| 3rd Year  | 9.3 Years                   |
| 4th Year  | 8 Years                    |
| 5th Year  | 7.2 Years                   |
| 6+ Years  | 7 Years per Dog Year        |

For example:  
- **3 dog years → 36.3 human years**  
- **6 dog years → 50.4 human years**  

---

## ▶️ How to Run the Program  
1. **Download the `dog_age_calculator.py` file.**  
2. **Run it in Python:**  
   ```bash
   python dog_age_calculator.py
