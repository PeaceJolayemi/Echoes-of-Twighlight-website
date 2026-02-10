# Echoes of Twilight Website

**Name:** Peace Jolayemi  
**Student Number:** 10137820
**Course:** IMD1005 - Web Development  
**Assignment:** 02 - Building Your Website  

## Project Overview
This website promotes *Echoes of Twilight*, an upcoming indie visual novel by Whimsitales Studios. The goal is to build trust with casual gamers by clearly showing the game's tone, story, and features before launch on Steam.

The site addresses the problem identified in Assignment 1: casual gamers need a way to quickly understand the game and see proof of quality before wishlisting, because they are skeptical of unfamiliar indie developers due to past experiences with misleading marketing.

## Website Pages

### Page 1 - Home (index.html)
The landing page features:
- **Hero section** with game title and call-to-action
- **Video placeholder** for gameplay footage (to be added before actual launch)
- **Features section** using CSS Grid to highlight key game elements
- Clear navigation to other pages

### Page 2 - Story (about.html)
A supporting page that explains:
- The narrative premise and main character
- Core themes (memory, loss, human connection)
- Developer philosophy and approach
- Builds trust through honest, transparent language

### Page 3 - Contact (contact.html)
A form page where users can:
- Submit their name and email
- Send a message to the studio
- Subscribe to development updates (checkbox)
- Stay connected before the game launches

## Design Changes from Assignment 1

### What Changed and Why:
1. **Simplified layout** - Feedback indicated the design needed clearer hierarchy. I focused on one clear action per page rather than overwhelming users with options.

2. **Restrained language** - Instead of marketing-heavy copy, I used honest, direct language that builds trust ("We didn't want to overpromise").

3. **Video placeholder** - Since we don't have actual gameplay footage for this assignment, I created a clear placeholder that indicates where the video will go in production.

4. **Improved feature descriptions** - Each feature card now includes a brief explanation rather than just a title, addressing user feedback about wanting more clarity.

5. **Added newsletter option** - Based on user testing feedback wanting to follow development, I added a subscription checkbox to the contact form.

## Technical Implementation

### Semantic HTML
All pages use proper semantic elements:
- `<nav>` for navigation
- `<main>` for primary content
- `<header>` for hero sections
- `<section>` for content groupings
- `<article>` for story content
- `<footer>` for site footer

### Flexbox Usage
Flexbox is used for:
- Navigation layout (horizontal centering with gap)
- Main content centering on contact page
- Checkbox and label alignment

### CSS Grid Usage
CSS Grid is used for:
- Features section on home page (3 equal columns)
- Responsive card layout

### Forms & Accessibility
The contact form includes:
- 4 inputs (name, email, message, newsletter checkbox)
- Properly associated `<label>` elements using `for` and `id` attributes
- Appropriate input types (`text`, `email`, `checkbox`)
- Required attributes for validation
- Clear visual feedback on focus

### Box Model
Demonstrated through:
- `box-sizing: border-box` applied globally
- Intentional use of padding for spacing (cards, sections, forms)
- Margin for separation between elements
- Consistent spacing system across all pages

## AI Usage Documentation

### Tools Used:
- **ChatGPT** - Used for learning and debugging

### What AI Helped With:
1. **Understanding CSS Grid syntax** - I asked ChatGPT to explain the difference between `grid-template-columns: repeat(3, 1fr)` and using fixed widths. This helped me understand the Grid layout used in the features section.

2. **Debugging form label association** - When my labels weren't working properly, I asked ChatGPT why, and learned about the importance of matching `for` and `id` attributes.

3. **Box model clarification** - Asked for examples of when to use margin vs padding to better understand spacing concepts.

### Where AI Helped in Code:
```html
<!-- AI-assisted: Used ChatGPT to understand CSS Grid for feature layout -->
```
This comment appears in `index.html` where the Grid layout is implemented.

### What I Wrote Myself:
- All HTML structure and content
- All CSS styling and layout decisions
- Design choices and visual hierarchy
- Color scheme and branding 


## Reflection & Improvements from Assignment 1

### Addressing Previous Feedback:

**Problem Definition (22/30):**
- Original feedback noted the problem statement was "clunky"
- Solution: I refined the language in the website to be clearer and more direct
- User trust is now built through design choices (transparent language, clear structure) rather than just explaining the problem

**User Testing (5/10):**
- Original feedback said testing results were "too thin" and lacked individual voices
- Solution: Added the newsletter checkbox based on specific user feedback about wanting to follow development
- Future improvement: Conduct more detailed testing with specific quotes and individual responses documented

**Design Justification (12/15):**
- Feedback wanted "more of my voice" in explanations
- Solution: Added code comments explaining my reasoning for specific choices
- This README includes more personal reflection on why I made certain decisions

### What I Learned:
1. **Code organization matters** - Keeping CSS organized with comments helps me understand my own code later
2. **Accessibility is built-in** - Proper form labels aren't just for screen readers; they make forms easier for everyone
3. **Trust through simplicity** - Based on Assignment 1 feedback, less marketing language and more honest communication builds better user trust

## Future Improvements
If I had more time, I would:
- Include more detailed story information based on user feedback
- Add character profile cards with images
- Implement responsive design with media queries for mobile devices
- Add smooth scroll animations between sections

## Testing Notes
Tested in:
- Chrome (latest version)
- Firefox (latest version)
- All pages load correctly with consistent styling
- Form validates properly with required fields
- Navigation works across all pages

---

**GitHub Repository:** [Link to be added before submission]  
**Live Site:** [Link to be added before submission]
