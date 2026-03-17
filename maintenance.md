# Maintenance Documentation

## Overview
This document explains how to maintain and update the Top Travel Destinations website. It is intended to help another person understand the structure of the website and make changes when needed.

## Website Structure and Organization
The website is organised into HTML files, one CSS folder, one images folder, and supporting markdown files.

### Main Files
- `index.html` – Home page
- `destinations.html` – Destination information
- `tips.html` – Travel tips
- `prices.html` – Prices and seasons
- `contact.html` – Contact form
- `css/style.css` – Main stylesheet
- `images/` – Stores website images

## Updating Text Content
To update text, open the required HTML file in Visual Studio Code and edit the paragraph, heading, list, or table content. Save the file and refresh the browser to view the changes.

## Adding New Pages
To add a new page:
1. Create a new HTML file in the main project folder.
2. Add the same header, navigation, and footer used on the other pages.
3. Link the stylesheet using `css/style.css`.
4. Add a new link in the navigation menu on all existing pages.
5. Test the page locally before uploading it to GitHub.

## Adding or Replacing Images
To add or replace an image:
1. Save the image inside the `images` folder.
2. Use a simple lowercase filename with no spaces.
3. Update the image path in the HTML if needed.
4. Check that the `alt` text describes the image correctly.

## Modifying Navigation
The navigation menu is located inside the `<header>` section of each HTML page. If a menu item is changed, the same update should be made on all pages to keep the navigation consistent.

## Uploading Changes to GitHub
To upload changes:
1. Save the updated files on the computer.
2. Open the GitHub repository.
3. Upload the changed files or use Git.
4. Commit the changes with a clear message.
5. Wait for GitHub Pages to update the live site.

## Common Troubleshooting Problems

### Problem: Images do not appear
- Check that the image file is inside the `images` folder.
- Check that the filename matches exactly.
- Make sure the file extension is correct.

### Problem: CSS does not load
- Check that the stylesheet link is written as `css/style.css`.
- Confirm that `style.css` is inside the `css` folder.

### Problem: Links do not work
- Make sure the page names in the navigation match the file names exactly.
- Check for spelling mistakes.

### Problem: GitHub Pages site does not update
- Wait a few minutes and refresh the page.
- Confirm that the files were uploaded to the correct repository.
- Check that GitHub Pages is enabled in repository settings.

## Recommended Maintenance Schedule
- Check links and images once a month
- Update destination information when needed
- Review prices and season tables regularly
- Test the website in different browsers after major updates
- Check the GitHub Pages site after every upload

## Future Improvements
Possible future improvements include:
- adding more destinations
- adding more detailed travel information
- improving the contact form
- adding JavaScript for more interactivity
- including more accessibility features

## Conclusion
Regular maintenance is important to keep the website accurate, accessible, and easy to use. A clear file structure and consistent navigation make future updates easier.
