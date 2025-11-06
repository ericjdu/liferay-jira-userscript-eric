# Jira for CSEs – Userscript

**Version:** 3.1  
**Author:** _(Your Name)_  
**Match URL:** `https://liferay.atlassian.net/*`  

---

## Overview

This userscript enhances the Jira interface for Customer Support Engineers (CSEs) by:

1. Adding **pastel-colored status lozenges** for easier readability.  
2. Inserting a **Patcher portal link** based on the account code in Jira issues.  
3. Highlighting the editor when writing **internal notes** for quick visual distinction.  

---

## Features

### 1. Status Colors
- Visual enhancement for Jira issue statuses.  
- Different statuses now have pastel backgrounds and readable text colors.  
- Works for both lozenge badges and inline status displays.

### 2. Patcher Link Field
- Automatically adds a **Patcher portal link** next to the account code field.  
- If the account code is missing, shows a placeholder with muted styling.  
- Clicking the link opens the corresponding account page in a new tab.

### 3. Internal Note Highlight
- Highlights the editor **yellow** when writing internal notes.  
- Removes highlight when clicking **Reply to Customer**.  
- Dynamically checks for internal comment visibility before applying styles.  

---

## Installation

1. Install a userscript manager like [Tampermonkey](https://www.tampermonkey.net/) or [Greasemonkey](https://www.greasespot.net/).  
2. Create a new userscript and paste the code from `Jira for CSEs.user.js`.  
3. Save and reload Jira pages.  
