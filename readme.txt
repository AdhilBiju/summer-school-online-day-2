1. Universal Selector (*)

-Where used: At the top of style.css.

-Purpose: Applies margin: 0% and padding: 0% to all elements, ensuring a consistent baseline by removing default spacing from all HTML elements.

2. Type Selectors (hr)

-Where used:
    hr styles all horizontal rules (removes border, sets width, color, height, and margin).

-Purpose: Directly targets HTML elements to apply consistent typography and layout.

3. Class Selectors (.profile-card, .pfp-section, .second-letter, .hobby-img, .contact-img, .list)

-Where used:

    .profile-card: Styles the main card container (width, margin, border, border-radius, box-shadow, text-align, background, overflow, and margin-top).

    .pfp-section: Applies a linear gradient background to the profile picture section.

    .second-letter: Changes the font size and color for a specific letter, likely for visual emphasis.

    .hobby-img, .contact-img: Styles images for hobbies and contact sections (height, padding, hover effect).

    .list: Adjusts text alignment and padding for a list.

-Purpose: Targets elements with specific classes for modular, reusable styling.

4. ID Selector (#hobby)

-Where used:

    #hobby: Styles the element with the ID "hobby" (font size, family, weight, underline, and underline color).

-Purpose: Applies unique styles to a single, specific element.

5. Pseudo-Class Selector (.contact-img:hover)

-Where used:

    .contact-img:hover: Adds a scaling transform and transition effect when hovering over elements with the contact-img class.

-Purpose: Enhances interactivity and user experience by providing visual feedback on hover.

6. Descendant selector (section ol)

-Purose: section ol targets ordered lists inside any <section> (sets font size, family, color, and weight).

7. Group selector (p, section ol)

-where used: p styles all <p> (paragraph) tags (font size, family, weight, and color). And section ol targets ordered lists inside any <section>

-Purpose: Grouped selectors make your stylesheet more organized and readable by clearly showing which elements share the same styles.