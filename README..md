Carnage Pals
Continuing the theme from my Events page, I decided to expand on the Carnage Pals universe by creating a sample registration page. This page is designed for users to sign up for our mailing list, purchase digital trading card packs, or create their own custom character. The concept is part of a fully playable online TCG (Trading Card Game), where users can either buy randomized card packs or build a unique card by submitting character details. The system then generates randomized stats for battle.

HTML & Bootstrap Setup
I started by setting up a basic HTML5 document structure and linking Bootstrap 5.3 via CDN. I used a fluid container to organize the overall page layout, ensuring responsiveness across different screen sizes.

Registration Form (Form Components & Layout)
The form was built using Bootstrap's form components and layout grid.

I included placeholders for inputs and used proper labels for accessibility.

The form includes required fields and utilizes Bootstrap's built-in validation classes.

For age and sex, I used <select> dropdown menus.

For the "How did you hear about us?" section, I used radio buttons.

A checkbox was added for agreement to terms and conditions.

I added a Submit button styled with Bootstrap's .btn-dark class, and applied custom hover and glow effects using CSS for improved aesthetics.

Table for Displaying Data
I created a responsive table using .table-responsive to ensure the layout adapts on smaller screens.

The table includes striped rows and hover effects for readability and interaction.

It displays hard-coded sample data simulating user registrations.

Images and Visual Layout
I included a responsive banner image using the .img-fluid class, ensuring it stretches across the page and scrolls naturally (not fixed).

A second image — the Carnage Pals logo — was placed below the welcome text. It uses the .rounded-circle and .img-fluid classes for styling and responsiveness. I spaced it slightly away from the top banner to avoid visual congestion.

Buttons (Visibility Control)
Two buttons were added for user actions:

Buy Packs: Always visible on all screen sizes.

Build Custom Character: Hidden on small screens using .d-none .d-md-block utility classes.

Navigation Bar
The navbar includes links to Home, About, and Contact sections.

On smaller screens, the navbar collapses into a responsive hamburger menu using Bootstrap's built-in collapse functionality.

Bonus Feature
I implemented a custom glowing popup alert upon form submission instead of a standard alert box, providing a more immersive horror-themed interaction.
