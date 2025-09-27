# Adobe Fonts Setup for Avenir Next

## To complete the font setup:

1. **Go to Adobe Fonts**: Visit [fonts.adobe.com](https://fonts.adobe.com)
2. **Search for Avenir Next**: Find the Avenir Next font family
3. **Create a Project**: Create a new project and add Avenir Next
4. **Get the Kit URL**: Copy the embed code that looks like:
   ```html
   <link rel="stylesheet" href="https://use.typekit.net/ABCD1234.css">
   ```
5. **Replace in HTML**: Update line 16 in `index.html`:
   ```html
   <!-- Replace YOUR_PROJECT_ID with your actual Adobe Fonts project ID -->
   <link rel="stylesheet" href="https://use.typekit.net/YOUR_PROJECT_ID.css">
   ```

## Font Weights Available:
- Avenir Next Ultra Light (weight: 200) - Used for subtitle
- Avenir Next Bold (weight: 700) - Used for main title
- Other weights available: 300, 400, 500, 600

## Current Implementation:
- Main title: "WELCOME TO FOYER" - Avenir Next Bold (700)
- Subtitle: "YOUR BESPOKE TICKETING SOLUTION" - Avenir Next Ultra Light (200)
- Both are uppercase with appropriate letter spacing
