# Ece's Daily Cognitive Science Fact

An elegant web application that delivers a daily technical fact about cognitive science, brain regions, and psychology. Each day of the year displays a unique, detailed fact with scientific citations.

## Features

- **365+ Technical Facts**: Comprehensive collection covering brain anatomy, neurotransmitters, psychology, and cognitive processes
- **Date-Based Display**: Shows a consistent fact each day based on the day of year (1-365)
- **Beautiful UI**: Beige-brown gradient design with smooth animations
- **Share Functionality**: Share interesting facts with others
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Technical Details**: Each fact includes specific brain areas, neural mechanisms, and scientific citations

## Deployment

### GitHub Pages

1. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com/new)
   - Create a new repository named `ecesfact`
   - Make it public (required for free GitHub Pages)
   - Don't initialize with README (we already have one)

2. **Push Your Code**:
   ```bash
   cd daily-cognitive-science-fact
   git remote add origin https://github.com/YOUR_USERNAME/ecesfact.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click "Settings" → "Pages"
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"
   - Your site will be live at: `https://YOUR_USERNAME.github.io/ecesfact/`

### Replit

1. **Create a new Repl**:
   - Go to [Replit.com](https://replit.com)
   - Click "Create Repl"
   - Choose "HTML, CSS, JS" template
   - Name it "ecesfact"

2. **Upload Files**:
   - Upload all files: `index.html`, `styles.css`, and `app.js`
   - Or copy and paste the contents into new files in Replit

3. **Run**:
   - Click the "Run" button
   - Your app will be live!

## File Structure

```
daily-cognitive-science-fact/
├── index.html      # Main HTML structure
├── styles.css      # Styling with beige-brown theme
├── app.js          # JavaScript logic and 365+ facts database
└── README.md       # This file
```

## How It Works

- **Daily Facts**: The app uses the day of year (1-365) to select which fact to display. Everyone who visits on the same date sees the same fact.
- **Date Function**: The `getDayOfYear()` function calculates which day of the year it is, ensuring consistent fact display.
- **Share**: Use the share button to copy or share facts via your device's native sharing.

## Customization

### Adding More Facts

Edit `app.js` and add new objects to the `cognitiveFacts` array:

```javascript
{
    title: "Your Fact Title",
    text: "Your detailed technical fact description here...",
    source: "Source citation"
}
```

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --background: #d2b48c; /* Beige-brown background */
}
```

## Technologies Used

- HTML5
- CSS3 (with CSS Variables, Gradients, and Animations)
- Vanilla JavaScript (no dependencies)

## License

Free to use and modify for personal or educational purposes.

---

**Enjoy learning about cognitive science!**
