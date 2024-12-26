Create a modern, responsive, and user-friendly website using HTML, CSS, and JavaScript for an SEO company named GOLDIE AGENCY PTE. LTD. The website should include the following sections:

1. Hero Section: Incorporate an eye-catching background image with compelling text and a clear call-to-action button.
2. Services Section: Display the company’s services with each service having an icon, a title, and a brief description.
3. Portfolio Section: Highlight completed projects with each project featuring an image, a title, and a concise description.
4. Testimonials Section: Showcase client testimonials with each including a client’s avatar, name, and testimonial text.
5. Contact Section: Add a contact form, a map with the company’s location, and detailed contact information.
6. Footer Section: Feature the company’s logo, copyright text, social media links, and modal links for legal pages such as privacy policy, terms of service, refund policy, returns policy, and cookies settings.

Design Guidelines:
- Implement a clean, modern, and intuitive design that is easy to navigate and consistent throughout.
- Use a visually appealing color palette that aligns with the company’s branding.
- Ensure the font is legible and complements the company’s style.
- Incorporate icons and visuals to make content engaging.
- Make the website accessible to users with disabilities and provide a seamless experience across devices with responsive design.
- Include a dark mode and light mode toggle to enhance user experience.

Development Guidelines:
- Optimize the website for fast loading speeds and search engine performance.
- Adhere to security best practices and ensure compliance with GDPR and COPPA regulations.
- Build the website to be maintainable, scalable, and easy to update.
- Use blocking JavaScript to load the user’s preferred color scheme, and non-blocking JavaScript for functionalities such as the dark mode toggle, contact form validation, and map integration.
- Validate form inputs on the client side and enable seamless functionality for toggles and the map.

Resources:
- Use placeholder images from https://placehold.co and avatars from https://avatar.iran.liara.run/public.
- Style the website using TailwindCSS via `<script src="https://cdn.tailwindcss.com/3.4.16"></script>`.
- Incorporate icons from Iconify via `<script src="https://cdnjs.cloudflare.com/ajax/libs/iconify/2.0.0/iconify.min.js"></script>`.
- Use fonts from Google Fonts via `<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&family=Poppins:wght@400;500;700&display=swap" rel="stylesheet>`.
- Integrate Google Maps for location display, with the API key configurable through JavaScript variables.

Color Scheme (TailwindCSS Palette):
- Seasalt, French Gray, White, Raisin Black, and Dodger Blue as defined in the given color palette.
```json
{ 'seasalt': { DEFAULT: '#F6F9FA', 100: '#233940', 200: '#467180', 300: '#75a4b3', 400: '#b5ced6', 500: '#f6f9fa', 600: '#f7fafb', 700: '#f9fbfc', 800: '#fbfcfd', 900: '#fdfefe' }, 'french_gray': { DEFAULT: '#AFB1B9', 100: '#222327', 200: '#43454d', 300: '#656874', 400: '#898c99', 500: '#afb1b9', 600: '#c0c1c8', 700: '#d0d1d6', 800: '#dfe0e3', 900: '#eff0f1' }, 'white': { DEFAULT: '#FFFFFF', 100: '#333333', 200: '#666666', 300: '#999999', 400: '#cccccc', 500: '#ffffff', 600: '#ffffff', 700: '#ffffff', 800: '#ffffff', 900: '#ffffff' }, 'raisin_black': { DEFAULT: '#322F40', 100: '#0a0a0d', 200: '#14131a', 300: '#1e1d27', 400: '#292634', 500: '#322f40', 600: '#57516e', 700: '#7c769a', 800: '#a8a4bb', 900: '#d3d1dd' }, 'dodger_blue': { DEFAULT: '#2791F3', 100: '#031d35', 200: '#063a6a', 300: '#09579f', 400: '#0c74d4', 500: '#2791f3', 600: '#51a6f5', 700: '#7dbcf7', 800: '#a8d2fa', 900: '#d4e9fc' } }
```

Content Guidelines:
- Provide minimal but meaningful and impactful placeholder content that is relevant and easy to understand.
- Focus on creating a professional, engaging, and cohesive website that reflects the company’s values and services.

Deliver a single HTML file including the website.