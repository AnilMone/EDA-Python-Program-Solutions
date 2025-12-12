# EDA Python Program Solutions

**Advanced Python Problem-Solving for Innomatics Research Lab**

> Complete solution set for the Innomatics EDA (Exploratory Data Analysis) Python Programmer assignment featuring 6 optimized LeetCode problems.

---

## 📋 Problems Included

### 1. Defanging an IP Address
**File:** `01_defanging_ip_address.py`
- Replace each period in an IP address with "[.]"
- Simple string manipulation using the `replace()` method
- **Complexity:** O(n) time, O(n) space

### 2. Find Numbers with an Even Number of Digits
**File:** `02_find_even_digit_numbers.py`
- Count how many numbers in an array have an even digit count
- Features both brute force and optimized approaches
- **Complexity:** O(n*m) where m is average digit count

### 3. Number of Good Pairs
**File:** `03_number_of_good_pairs.py`
- Count pairs (i,j) where nums[i] == nums[j] and i < j
- Includes both O(n²) and O(n) hash map solutions
- **Complexity:** O(n) time (optimized), O(n) space

### 4. How Many Numbers Are Smaller Than the Current Number
**File:** `04_smaller_numbers_than_current.py`
- For each element, count how many smaller elements exist
- Features sorting-based optimization
- **Complexity:** O(n log n) time, O(n) space

### 5. Subtract the Product and Sum of Digits of an Integer
**File:** `05_subtract_product_sum_digits.py`
- Extract digits and calculate product and sum
- Compare mathematical approaches vs. string conversion
- **Complexity:** O(log n) time (where n is the number)

### 6. XOR Operation in an Array
**File:** `06_xor_operation_array.py`
- Generate array based on formula and perform XOR operations
- Multiple implementations using different approaches
- **Complexity:** O(n) time, O(1) space

---

## 🎯 Learning Objectives

✅ String manipulation and replacement techniques
✅ Array iteration and counting algorithms
✅ Hash map/dictionary optimization
✅ Sorting and ranking algorithms
✅ Mathematical digit extraction
✅ Bitwise operations and XOR logic
✅ Time and space complexity analysis
✅ Multiple solution approaches for each problem

---

## 📊 Key Features

- **Clean, readable code** with comprehensive comments
- **Multiple approaches** for each problem (brute force + optimized)
- **Complexity analysis** included (Time & Space)
- **Test cases** for validation
- **Detailed docstrings** explaining logic
- **Production-ready solutions** following best practices

---

## 🚀 Getting Started

### Prerequisites
- Python 3.6 or higher
- Basic understanding of Python syntax
- Familiarity with LeetCode problem format

### Running the Solutions

Each file can be run independently:

```bash
python 01_defanging_ip_address.py
python 02_find_even_digit_numbers.py
python 03_number_of_good_pairs.py
python 04_smaller_numbers_than_current.py
python 05_subtract_product_sum_digits.py
python 06_xor_operation_array.py
```

---

## 📝 Usage Example

```python
from solution import Solution

sol = Solution()

# Example 1: Defang IP Address
result = sol.defangIPaddr("1.1.1.1")
print(result)  # Output: "1[.]1[.]1[.]1"

# Example 2: XOR Operation
result = sol.xorOperation(5, 0)
print(result)  # Output: 12
```

---

## 🎓 Ideal For

- BCA/B.Tech students preparing for tech interviews
- Competitive programming practice
- Data Science role preparation
- LeetCode practice and mastery
- Understanding algorithm optimization
- FAANG/MAANG company interviews

---

## 📈 Progression Path

1. **Beginner:** Focus on understanding basic approaches
2. **Intermediate:** Study optimized solutions and complexity
3. **Advanced:** Compare approaches and implement variations
4. **Expert:** Customize solutions for specific use cases

---

## 💡 Key Insights

- **String operations** in Python are efficient for text manipulation
- **Hash maps** reduce complexity from O(n²) to O(n)
- **Sorting** can provide elegant solutions with O(n log n) complexity
- **Bitwise operations** are powerful for mathematical problems
- **Time vs Space tradeoff** is crucial in algorithm design

---

## 📚 Resources

- [LeetCode Problem List](https://leetcode.com/)
- [Python Algorithm Complexity](https://wiki.python.org/moin/TimeComplexity)
- [Bitwise Operations Guide](https://www.geeksforgeeks.org/bitwise-operators-in-python/)
- [Python Data Structures](https://docs.python.org/3/tutorial/datastructures.html)

---

## 👨‍💻 Author

**AvilMone**  
*BCA Final Year Student*  
*Innomatics Research Lab Intern*  
Focused on Data Science, Python, and Competitive Programming

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add more optimal solutions
- Improve existing code
- Add test cases
- Fix bugs or improve documentation

---

## ⭐ Acknowledgments

- **Innomatics Research Lab** for the assignment opportunity
- **LeetCode** for the excellent problem set
- **Python community** for outstanding documentation

---

## 📞 Contact & Support

For questions or suggestions:
- GitHub: [@AnilMone](https://github.com/AnilMone)
- LinkedIn: Connect for career opportunities
- Issues: Use GitHub issues for bug reports

---

**Last Updated:** December 2025  
**Status:** Complete & Tested ✅  
**Ready for Interview Prep:** Yes ✨
