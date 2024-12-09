# Mindgrub Government Services Website Project Brief

## Project Overview
- Project Name: Mindgrub Government Services Website
- Objective: Create a static website for government services division
- Target Launch: [Date]
- GitHub Repository: mindgov_ai

## Available Resources
1. Current Website
   - URL: https://gov.mindgrub.com/
   - Purpose: Reference for current content and design

2. Local Assets Directory
   - Location: /Users/willf/smartIndex/mindgrub/
   - Files:
     * mindgov_setup_guide.md
     * mindgovLogo.png
     * partnerGov.png
     * webmindgovBrochure.pdf

3. Brand Assets
   - Logo: Red logo from PDF
   - Colors: Blue/red text over white background
   - Design Elements: [Any specific design guidelines]

## Required Pages & Content

### 1. Landing Page
- Header:
  * Logo placement
  * Navigation menu
- Hero Section:
  * Company certifications (WOSB, HUBZone)
  * Address: 1418 S. Carey St. Baltimore, MD
- Feature Blocks:
  * [List all 3 blurbs]

### 2. About Us Page
- Company Overview
- Partnerships section:
  * NASA
  * State of California
  * City of Baltimore
- Team photo integration

### 3. Careers Page
- Job listings section
- Application upload functionality
- Contact form

### 4. NAICS Codes Page
- [Complete list of NAICS codes with descriptions]

## Technical Requirements

1. Technology Stack:
   - HTML5
   - CSS3
   - Vanilla JavaScript
   - Static site deployment ready for GitHub Pages

2. Development Guidelines:
   - Mobile-responsive design
   - Semantic HTML
   - Documented code
   - Accessibility compliance

3. Deliverables:
   - Source code in GitHub repository
   - Documentation
   - Deployment instructions

## Additional Notes
- Include comprehensive code comments for team handoff
- Focus on maintainability
- Include setup instructions

## Code Documentation Examples

### JavaScript Documentation Example:
```javascript
/**
 * @fileoverview Main JavaScript file for Mindgrub Government Services website
 * @version 1.0.0
 * @author [Your Name]
 * @lastModified 2024-12-09
 */

/**
 * @class JobApplication
 * @description Handles all job application form functionality
 * @param {HTMLFormElement} form - The job application form element
 */
class JobApplication {
    constructor(form) {
        this.form = form;
        this.init();
    }

    /**
     * @method init
     * @description Initializes form event listeners and validation
     * @returns {void}
     */
    init() {
        // Implementation
    }
}
```

### HTML Documentation Example:
```html
<!-- 
    Component: Main Navigation
    Description: Primary navigation header for the website
    Dependencies: style.css
    Usage: Included on all pages for consistent navigation
-->
<nav class="main-nav">
    <!-- Navigation items -->
</nav>
```