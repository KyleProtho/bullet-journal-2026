# 2026 Digital Bullet Journal

A simple, elegant web page for downloading two versions of a 2026 Bullet Journal. Built with vanilla HTML and CSS, designed to be hosted on GitHub Pages.

## 🌟 Features

- **Clean, modern design** with a warm color palette
- **Two download options**:
  - Full Bullet Journal (Word Doc)
  - Modular Version (ZIP Folder) - recommended for computers with lower RAM
- **Responsive layout** that works on desktop and mobile devices
- **Smooth animations** and hover effects for better user experience
- **Optional donation link** via Venmo

## 📁 Project Structure

```
bullet-journal-2026/
├── index.html                      # Main HTML file
├── styles.css                      # Stylesheet with modern design
├── bullet-journal-2026.docx        # Full version download
├── bullet-journal-2026-modular.zip # Modular version download
├── .gitignore                      # Git ignore file
└── README.md                       # This file
```

## 🚀 Getting Started

### Viewing Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/KyleProtho/bullet-journal-2026.git
   cd bullet-journal-2026
   ```

2. Open `index.html` in your web browser:
   - Double-click the file, or
   - Right-click and select "Open with" → your browser of choice

### Deploying to GitHub Pages

1. Go to your repository settings on GitHub
2. Navigate to **Pages** in the left sidebar
3. Under **Build and deployment**, select **main** branch as the source
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/bullet-journal-2026/`

## 🎨 Design

The page features:
- **Typography**: Inter font family for a modern, clean look
- **Color Scheme**: Warm orange (#FCA356) with neutral grays
- **Background**: Subtle radial gradient circle for visual interest
- **Buttons**: Contrasting primary (orange) and secondary (white) styles
- **Micro-interactions**: Smooth hover effects and transitions

## 🛠️ Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #FCA356;  /* Orange accent */
    --text-color: #2D2D2D;     /* Dark gray text */
    --bg-color: #FFFFFF;       /* White background */
    --circle-color: #FFF0DE;   /* Light peach circle */
}
```

### Updating Text

Edit the content in `index.html`:
- Title: Line 15
- Introduction: Line 16
- Button labels: Lines 19-27
- Footer text: Lines 30-31

### Changing the Venmo Link

Update the `href` attribute on line 31 in `index.html`:

```html
<a href="https://account.venmo.com/u/YOUR-USERNAME?txn=pay&amount=3.00" target="_blank" class="venmo-link">Send via Venmo</a>
```

## 📄 License

This project is open source and available for personal use.

## 🙏 Acknowledgments

Created with care to help you start 2026 with clarity and focus.