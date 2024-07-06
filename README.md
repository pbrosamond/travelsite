# Travel Site

## Project Overview
A travel company has approached you to design a basic travel destination website, leveraging HTML, CSS, and component thinking. Pay attention to the details of the mockup and the instructions below to successfully complete this project.

## Submission Instructions
To submit this deliverable, ensure you push the last git commit to your GitHub repository before the submission deadline. Submit the link to your GitHub repository in Synapse before the submission deadline.

## Tools & Resources
- Convert a creative mockup into a functional multi-page static site using HTML and CSS.
- Download the assets & mockups [here](#) to get a better idea of how your project should appear.
- Keep in mind that the mockups were created for a screen size of 1280px wide.

## Functional Requirements

### Site Structure
The site must have 4 pages:
1. Home Page
2. 3 Destination Pages:
   - Iceland
   - Greece
   - Hawaii

### Home Page
The Home Page must have 4 sections:
1. **Navigation Bar**
   - Will contain working links for each page.
   - Logo (should link to the Home page).
   - Links: Home, Iceland, Greece, Hawaii.

2. **Hero Section**
   - Background color: #FEFAF5.
   - Text content must be left-aligned.
   - Slogan color: #335576.
   - 'Get Started' button background color: #DB7A4E.

3. **Recommendations Section**
   - Title color: #335576.
   - Three cards, one for each destination (Iceland, Greece, Hawaii).
   - Cards linked to the appropriate destination page.
   - Destination name in the bottom right corner of the card.
   - Card styles:
     - Border radius: 5px.
     - Border: 1px solid black with 20% opacity.
     - Box shadow: 0px horizontal offset, 4px vertical offset, 4px blur, black with 20% opacity.

4. **Footer**
   - Background color: #FEFAF5.
   - Footer titles and text color: #335576.
   - Footer subtitles color: #DB7A4E.

### Destination Pages
Each destination page must have 3 sections:
1. **Navigation Bar**
   - Same as the Home Page.

2. **Itinerary Cards for a 3-Day Trip**
   - Friday, Saturday, Sunday.
   - Four itinerary activities per day (e.g., Breakfast, Lunch, Dinner, Snorkeling).
   - Activities background color: #FEFAF5.

3. **Footer**
   - Same as the Home Page.

### Visual Design Requirements
- All pages must match the mockups as closely as possible, being mindful of image distortion and proportions.
- Use the assets provided.
- Identical Navigation Bar and Footer styles across all pages.
- Navigation Bar:
  - Fixed to the top of the page.
  - Background color: #FFFFFF.
  - Site logo/wordmark color: #335576.
  - Currently active page underlined with color: #DB7A4E.

## Implementation Requirements
- Use semantic tags where appropriate (e.g., header, footer, nav, etc.).
- All CSS must be placed in a separate stylesheet and connected to the HTML through the link tag.
- Follow the Travel Site Structure Diagram for file/folder organization.
- Navigation Bar: Menu items must be specified using an unordered list.
- Recommendations Destination Cards: Use the `<a>` tag around the cards to link to the appropriate page.
- Itinerary Cards: Use an unordered list for the itinerary activities.
- Reuse as much styling and code as possible, and build your project around common component code that you can reuse.
- Use the BEM methodology for all your class names.
- Layout of your site must use the Box Model, the CSS display property, and CSS positioning including Flexbox. Do not use floats.

## Diving Deeper
If you have completed the requirements above, you may go above and beyond to demonstrate skills you have been learning. However, any further features you add must not conflict with the provided requirements.

### Suggestions for Diving Deeper
- Make your site responsive so that it looks good at any dimension.
- Add hover animations to links. For example:
  - Navigation menu items: Add an underline to the hovered item.
  - Destination cards: Change border color or add a semi-transparent overlay when hovered.
- Add a "Get Started" page with a form that allows a user to select a destination and provide their contact information and message for the booking process. The page should have the same look and feel as the rest of the site.