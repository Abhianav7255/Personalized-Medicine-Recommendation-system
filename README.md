# Personalized Health Care

This project is a web-based application that provides alternative medicine recommendations. Users can input a medicine name, and the application will suggest alternative medicines, complete with links to purchase them.

---

## Features

- User-friendly interface for selecting medicines.
- Integration with `PharmEasy` for easy access to purchasing options.
- Stylish and responsive design using Bootstrap and Select2.
- Displays a list of recommended alternatives for selected medicines.

---

## Technologies Used

- **HTML5**
- **CSS3**
- **Bootstrap 4.5**: For responsive and modern UI design.
- **Select2**: For enhanced dropdown functionality.
- **Jinja2**: For rendering dynamic content (used in the template).

---

## Prerequisites

1. **Python** and Flask for backend functionality.
2. A list of medicines and their alternatives stored in a backend system or database.

---

## File Structure

```plaintext
project-directory
├── templates
│   ├── index.html  # Main HTML template
├── static
│   ├── css  # Custom CSS (if any)
│   ├── js   # Custom JavaScript (if any)
├── app.py        # Flask backend
├── requirements.txt
```

---

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/personalized-health-care.git
   cd personalized-health-care
   ```

2. **Install Dependencies:**

   Ensure you have Python installed, then run:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application:**

   ```bash
   python app.py
   ```

4. **Access the Application:**

   Open your browser and navigate to:

   ```
   http://127.0.0.1:5000
   ```

---

## How to Use

1. **Select a Medicine:**
   Use the dropdown menu to select the name of a medicine.

2. **Get Recommendations:**
   Click the "Recommend Medicine" button to see alternatives.

3. **Purchase Medicines:**
   Use the "Click to Buy" button next to each recommended medicine to open its purchasing link on `PharmEasy`.

---

## Example Output

1. User selects `Paracetamol` from the dropdown.
2. Application displays recommendations:

   ```plaintext
   Recommended Medicines for Paracetamol:
   1. Crocin
   2. Dolo 650
   3. Calpol
   ```

Each recommendation has a "Click to Buy" button linking to its respective page on `PharmEasy`.

---

## Contributions

Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author

**[Abhinav Kumar](https://github.com/Abhianav7255)**
