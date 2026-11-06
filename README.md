# Kandeel Co. — Security Systems & Solutions Website

A multi-page business website concept for presenting Kandeel Co.'s security, smart-home, networking, and related technical products and services. The front end organizes product categories, company information, services, and contact details into a browsable company catalogue.

> **Project type:** Multi-page business and product-catalogue front end  
> **Status:** Static front-end implementation

## Preview

**Live Demo:** [https://a-kandeel.github.io/Kandeelco-security-solutions-ecommerce-website/]

- **Repository:** https://github.com/A-Kandeel/Kandeelco-security-solutions-ecommerce-website

## Features

- Main landing page introducing the company and its offerings.
- Dedicated About, Products, Services, and Contact pages.
- Product catalogue sections covering categories such as:
  - Security cameras
  - Attendance devices
  - Video and audio intercom systems
  - Fire alarm systems
  - Smart-home systems
  - Networking equipment
- Navigation between product categories and detailed product pages.
- Contact information and links to social media.
- Custom CSS styles, local image assets, and Font Awesome icons.

## Built With

- HTML5
- CSS3
- JavaScript
- Font Awesome

The repository is structured as a static website and does not include a package-based build setup.

## Main Pages

| Page | Purpose |
| --- | --- |
| `index.html` | Main company landing page and product highlights |
| `Templates/About_us.html` | Company information |
| `Templates/Products.html` | Product catalogue |
| `Templates/ProductsPg2.html` | Additional product categories |
| `Templates/Services.html` | Services overview |
| `Templates/Contact_us.html` | Contact page |

## Project Structure

```text
Kandeelco_e-commerce_site/
├── index.html
├── Templates/
│   ├── About_us.html
│   ├── Contact_us.html
│   ├── Products.html
│   ├── ProductsPg2.html
│   └── Services.html
├── css/
├── js/
│   └── app.js
└── IMGs/
```

The repository also contains local font and icon assets. Some asset directory and file names preserve their original capitalization and spelling; keep those paths unchanged when editing references.

## Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/A-Kandeel/Kandeelco-security-solutions-ecommerce-website.git
   ```

2. Open the project folder.
3. Open `index.html` in your browser.

For a more consistent local preview, serve the folder with a simple static development server, such as Visual Studio Code Live Server.

## Important Implementation Notes

- Despite the repository name, the inspected implementation is a **front-end product catalogue and company website**, not a complete e-commerce platform. No shopping cart, checkout, payment processing, or order-management backend was identified.
- The login form references `login.php`, but that PHP file is not present in the repository. Authentication should therefore not be presented as implemented.
- The contact form uses a `mailto:` destination, which opens the visitor's configured email application; it is not a server-side contact workflow.
- Product descriptions and other page copy should be reviewed and replaced with final business content before production use.

## Possible Next Improvements

- Implement product enquiry or quote-request flows.
- Connect contact and authentication interfaces to secure backend services if those features are required.
- Add product search, filtering, and structured product details.

## License

No license file is currently included in this repository. All rights remain with the project owner unless a license is added.
