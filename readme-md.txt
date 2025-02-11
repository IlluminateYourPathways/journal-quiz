# Journal Selection Quiz

A React-based quiz application to help users find the perfect journal for their needs.

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/[your-username]/journal-quiz.git
cd journal-quiz
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. To deploy to GitHub Pages:
   - Update the `package.json` "homepage" field with your GitHub Pages URL
   - Run:
```bash
npm run deploy
```

## Development

- `npm start` - Runs the app in development mode
- `npm run build` - Builds the app for production
- `npm run deploy` - Deploys to GitHub Pages

## Embedding in Squarespace

After deploying to GitHub Pages, you can embed the quiz in Squarespace using:

```html
<iframe 
  src="[your-github-pages-url]" 
  width="100%" 
  height="700px" 
  frameborder="0"
  style="border: none; max-width: 800px; margin: 0 auto; display: block;"
></iframe>
```

## License

MIT