# X-TECH Landing Page

A modern, responsive landing page designed to convert traffic into sales. Built with HTML, CSS, and Tailwind CSS.

## Features

- 🎨 Modern, clean design
- 📱 Fully responsive layout
- ⚡ Fast loading with optimized assets
- 🎯 Conversion-focused design
- 📊 Call-to-action buttons
- 💬 Customer testimonials
- 🔗 Social media integration

## Project Structure

```
src/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── assets/             # Images and icons
│   ├── logo-xtech-.png
│   ├── hero-devices.png
│   ├── arrow-curly-left.png
│   ├── arrow-curly-right.png
│   ├── map.png
│   └── ... (other assets)
├── package.json        # Project dependencies
├── vercel.json         # Vercel configuration
└── README.md           # This file
```

## Local Development

1. Clone the repository
2. Navigate to the project directory
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open your browser and visit `http://localhost:3000`

## Deployment on Vercel

### Method 1: Deploy via Vercel CLI

1. Install Vercel CLI:

   ```bash
   npm i -g vercel
   ```

2. Login to Vercel:

   ```bash
   vercel login
   ```

3. Deploy:
   ```bash
   vercel
   ```

### Method 2: Deploy via GitHub

1. Push your code to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect it's a static site
6. Click "Deploy"

### Method 3: Drag & Drop

1. Go to [vercel.com](https://vercel.com)
2. Drag and drop your project folder
3. Vercel will automatically deploy it

## Configuration

The project includes a `vercel.json` file with optimized settings:

- Static file serving
- Proper routing
- Cache headers for better performance

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styles and animations
- **Tailwind CSS** - Utility-first CSS framework
- **Responsive Design** - Mobile-first approach

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - feel free to use this project for your own purposes.

## Support

If you have any questions or need help with deployment, please open an issue in the repository.
