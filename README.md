# Email Signature Generator

A simple, customizable email signature generator for the members of Eko India Financial Services. This web-based tool allows Eko's members to create professional and branded email signatures with a consistent look and feel across the organization.

## Features

- Live preview of the signature as you type
- Easily add personal and professional links
- Auto-formatting of mobile phone numbers
- Auto capitalization of names
- Responsive design for desktop and mobile
- Company branding with logo and social media links
- "See Sample" feature for quick demonstration
- Step-by-step instructions for implementation in Gmail


## Usage Instructions

1. Fill in your personal details in the form:
   - Name
   - Designation
   - Phone number (10-digit Indian mobile format)
   - Up to 3 additional personal/professional links

2. The signature preview updates automatically as you type

3. Copy the generated signature from the preview box

4. Add to Gmail:
   - Open Gmail and go to Settings
   - Navigate to the "Signature" section
   - Create a new signature and paste your copied HTML
   - Save changes

## Technologies Used

- Vue.js 3 (loaded via CDN)
- HTML5
- CSS3
- JavaScript (ES6+)
- No build tools or server-side dependencies required

## How to fork this for your own organization?

To customize this signature generator for your own organization:

1. Fork the repository on GitHub: [Fork this project](https://github.com/ekoindia/email-signature/fork)

2. Update the company configuration in the `companyDetails` object in `index.html`:
   ```javascript
   const companyDetails = {
     name: "Your Company Name",
     shortName: "YourCompany",
     website: "https://yourcompany.com",
     // Update all other company-specific details
     // Add your own URLs and social media links
   };
   ```

3. Replace the logo:
   - Add your logo to the `assets` folder
   - Update the `logo_url` property in the configuration

4. Customize the styling:
   - Modify the `styles/signature.css` file to match your brand colors and style

5. Update the disclaimer text and any legal notices

6. Test thoroughly with various inputs before deploying to your organization

