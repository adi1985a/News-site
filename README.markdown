# NewsPortal

## Overview
NewsPortal is a responsive HTML-based news website featuring world and national news, articles, blogs, videos, and photo galleries. Built with Tailwind CSS, it includes a hero section, breaking news ticker, weather widget, newsletter, and poll. Enhanced with Font Awesome, Animate.css, and JavaScript for dynamic date/time updates.

## Features
- **Responsive Layout**: Adapts to mobile and desktop with Tailwind CSS grid and flexbox.
- **Navigation**: Sticky nav with dropdowns for World and National news categories.
- **Hero Section**: Gradient background with featured article and floating image.
- **Breaking News Ticker**: Marquee animation for live updates.
- **Content Sections**: Top stories, featured articles, videos, blogs, galleries, and resources.
- **Sidebar**: Weather widget, latest news, popular tags, newsletter form, and poll.
- **Interactivity**: JavaScript updates date/time every second; hover effects and animations via Animate.css.
- **Styling**: Tailwind CSS, custom CSS, Google Fonts (`Poppins`), and Font Awesome icons.
- **SEO**: Meta tags for viewport and description.

## Requirements
- Web browser (e.g., Chrome, Firefox, Safari)
- Internet connection for external resources:
  - Tailwind CSS (`https://cdn.tailwindcss.com`)
  - Font Awesome (`https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css`)
  - Animate.css (`https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css`)
  - Google Fonts (`Poppins`)
  - Unsplash images
- No local assets required (all resources are CDN-hosted).

## Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
2. Host the site on a web server (e.g., Apache, Nginx) or open `index.html` directly:
   ```bash
   python -m http.server 8000
   ```
3. Access the site at `http://localhost:8000`.

## Usage
1. Open the website in a browser to view the homepage.
2. **Interface**:
   - **Top Bar**: Shows current date/time (updates every second) and login/register links.
   - **Navigation**: Click links or dropdowns to access categories (e.g., World Politics, National Sports).
   - **Hero Section**: View featured article with "Read more" or "Watch video" buttons.
   - **Main Content**: Browse top stories, articles, videos, and blogs.
   - **Sidebar**: Check weather, latest news, tags, subscribe to newsletter, or vote in poll.
   - **Gallery/Resources**: View photo galleries or download reports.
   - **Contact**: Submit inquiries via the contact form (placeholder).
3. **Actions**:
   - Search news using the search bar (placeholder).
   - Hover over cards for scale/animation effects.
   - Click links to navigate (most are placeholders).

## File Structure
- `index.html`: Main page with all sections and scripts.
- `README.md`: This file, providing project documentation.

## Notes
- The site is in English (`lang="en"`) for broad accessibility.
- All images are sourced from Unsplash; ensure internet access for loading.
- Forms (newsletter, contact, poll) are placeholders; add backend for functionality.
- The commented mobile menu toggle requires additional HTML for activation.
- The DeepSite watermark is included but can be removed if not needed.
- Links (e.g., articles, galleries) are placeholders; replace with real URLs.
- No local CSS/JS files; all styling is inline or CDN-based.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, open an issue on GitHub or email contact@newsportal.com.