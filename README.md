# Nested Tables Form Validation

A responsive web form implementation featuring nested tables with client-side validation. This project demonstrates how to create complex table structures with form inputs and implement comprehensive form validation using vanilla JavaScript.

## 🚀 Features

- Nested table structures with clean, professional styling
- Client-side form validation
- Responsive design
- Input field error handling
- Real-time error feedback
- Form data collection and processing
- Cross-browser compatibility

## 📋 Prerequisites

No special prerequisites are required. The project uses:
- HTML5
- CSS3
- Vanilla JavaScript

No external libraries or frameworks are needed.

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/nested-tables-form.git
```

2. Navigate to the project directory:
```bash
cd nested-tables-form
```

3. Open `index.html` in your preferred web browser.

## 💻 Usage

1. Fill in the form fields in both the main table and nested tables
2. Required fields are validated upon form submission
3. Error messages appear under invalid fields
4. Successfully submitted form data is logged to the console

### Form Structure

The form consists of:
- Main table with 4 columns and 5 rows
- Two nested tables in different cells
- Input fields in each cell
- Submit button at the bottom

## 🎨 Customization

### Styling

The CSS is organized in the `<style>` section of the HTML file. Key customizable elements include:

```css
.outer-table {
    /* Modify outer table styles */
}

.nested-table {
    /* Modify nested table styles */
}

input[type="text"] {
    /* Modify input field styles */
}

button {
    /* Modify button styles */
}
```

### Validation Rules

Modify the validation logic in the JavaScript section:

```javascript
// In the submit event listener
inputs.forEach(input => {
    // Add or modify validation rules here
});
```




- Inspiration from various form validation implementations
- Best practices from Mozilla Developer Network (MDN)
- Web accessibility guidelines from W3C

## 📊 Project Status

This project is currently in development. Users are welcome to contribute and suggest improvements.# Nested-table-using-html-css-and-js
