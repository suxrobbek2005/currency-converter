# Currency Converter

A simple project to create a **Currency Converter** using Python. This project will fetch live exchange rates from the [National Bank of Uzbekistan](https://nbu.uz/uz/exchange-rates/json/) API and allow users to convert between different currencies.

---

## Project Description

The **Currency Converter** application will:
- Fetch real-time exchange rates from the given API.
- Allow the user to input the amount they want to convert.
- Support conversions between various currencies, including USD, EUR, RUB, UZS, etc.
- Display the conversion result in a clear and user-friendly format.

---

## Learning Objectives

By completing this project, students will:
1. Learn how to use APIs and handle JSON data in Python.
2. Understand the basics of HTTP requests using the `requests` library.
3. Practice designing user-friendly console-based programs.
4. Improve their problem-solving and debugging skills.

---

## Requirements

Before starting this project, ensure you have the following:
- Python 3 installed on your computer.
- Basic understanding of Python programming.
- Internet connection to access the exchange rates API.

### Libraries Needed
Install the required library using the following command:
```bash
pip install requests
```

---

## Instructions

1. **Setup the Project:**
   - Create a new folder named `currency-converter`.
   - Inside the folder, create a Python script file named `converter.py`.

2. **API Integration:**
   - Use the URL: [https://nbu.uz/uz/exchange-rates/json/](https://nbu.uz/uz/exchange-rates/json/) to fetch the exchange rates.
   - Parse the JSON data using Python's `json` module.

3. **User Input:**
   - Ask the user to input:
     - The amount of money they want to convert.
     - The currency they want to convert from.
     - The currency they want to convert to.

4. **Perform Conversion:**
   - Calculate the converted amount based on the exchange rate.

5. **Display Results:**
   - Show the user the result of the conversion in a clear format.

6. **Bonus Tasks (Optional):**
   - Add error handling for invalid inputs (e.g., unsupported currencies or invalid numbers).
   - Allow the user to perform multiple conversions without restarting the program.
   - Save the conversion history to a file.

---

## Example Output

```
Welcome to Currency Converter!

Available Currencies: USD, EUR, RUB, UZS, etc.

Enter the amount: 100
Enter the currency to convert from (e.g., USD): USD
Enter the currency to convert to (e.g., UZS): UZS

Conversion Result: 100 USD = 1,200,000 UZS
```

---

## Submission

- Submit your `converter.py` file.
- Make sure the program runs without errors and meets the project requirements.

---

## Resources

- [Python `requests` library documentation](https://docs.python-requests.org/en/latest/)
- [Python `json` module documentation](https://docs.python.org/3/library/json.html)
- [Exchange rates API](https://nbu.uz/uz/exchange-rates/json/)

Good luck and happy coding! 🚀
