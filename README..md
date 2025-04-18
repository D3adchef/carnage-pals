# Carnage Pals

Continuing the theme from my Events page, I decided to expand on the Carnage Pals universe by creating a sample registration page.  
This page is designed for users to sign up for our mailing list, purchase digital trading card packs, or create their own custom character.  
The concept is part of a fully playable online TCG (Trading Card Game), where users can either buy randomized card packs or build a unique card by submitting character details. The system then generates randomized stats for battle.

---

## 🔧 HTML & Bootstrap Setup

I started by setting up a basic HTML5 document structure and linking **Bootstrap 5.3 via CDN**.  
I used a fluid container to organize the overall page layout, ensuring responsiveness across different screen sizes.

---

## 📝 Registration Form (Form Components & Layout)

The form was built using Bootstrap’s form components and layout grid:

- Included placeholders for inputs and used proper labels for accessibility.
- Required fields were enforced with Bootstrap's built-in validation.
- **Age** and **Sex** are implemented as `<select>` dropdowns.
- "How did you hear about us?" is implemented with **radio buttons**.
- Checkbox included for agreement to terms and conditions.
- Submit button styled with `.btn-dark` and custom glow effects via CSS.

---

## 📊 Table for Displaying Data

- Responsive table wrapped in `.table-responsive` to adapt on smaller screens.
- Used `.table`, `.table-striped`, and `.table-hover` for readability and interaction.
- Hard-coded data simulates user submissions.

---

## 🖼️ Images and Visual Layout

- Included a **responsive banner**
