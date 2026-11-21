# My Budget Tracker

A personal budget and expense tracker built step by step as a web development course project.
This is the **Week 2** version: HTML structure, tables, forms, multimedia and CSS selectors.
It does not calculate or respond to clicks yet. JavaScript comes in later weeks.

## What I built

### index.html
- **Header**: a logo (`<img>` with `src`, `alt` and `width`), the main heading and a short tagline.
- **How to use this tracker**: a collapsible `<details>` / `<summary>` help section.
- **Add Expense form**: a `<form>` with inputs for name, amount, category (a `<select>` with five options: Food, Transport, Rent, Entertainment, Other) and date. Every input has a matching `id` and `<label for>`. The button uses `type="button"` and does nothing yet.
- **Your Expenses**: a table using `<thead>`, `<tbody>`, `<tr>`, `<th>` and `<td>` with five rows of sample data.
- **Budgeting Tips**: a YouTube video embedded with an `<iframe>` (with `width`, `height`, `title` and `frameborder`).
- **Footer**: copyright text.

### style.css
- **Element, class and ID selectors** to style the page and make each section look different.
- **Table styling**: `border-collapse: collapse`, cell padding, a colored header row and alternating row colors.
- **Advanced selectors used**:
  - Descendant selector: `#expense-list td`
  - Position pseudo-class: `tbody tr:nth-child(even)`
  - Direct child selector: `#expense-form > label`
  - Negation pseudo-class: `input:not([type="date"])`
  - Focus state: `input:focus, select:focus`
- **Interactive styles**: `tbody tr:hover` changes the row color, and `cursor: pointer` is set on the button and the `<summary>`.

### logo.svg
A simple coin icon used as the site logo.

## How to run
Open `index.html` in a web browser. Keep `index.html`, `style.css` and `logo.svg` in the same folder. The video needs an internet connection.

## Coming next
JavaScript to make the form add real expenses to the table.
