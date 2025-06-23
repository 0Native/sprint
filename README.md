# Launch Tracker - GroundState.AI

A modern, interactive sprint tracking application built with React and Tailwind CSS. Track your launch progress, manage deliverables, and stay motivated with real-time progress visualization.

## Features

- 📊 **Real-time Progress Tracking**: Visual progress ring and statistics
- 🎯 **Sprint Management**: Organize tasks by weeks with completion tracking
- 📋 **Deliverables Management**: Track key project deliverables
- ✏️ **Inline Editing**: Edit tasks and deliverables directly in the interface
- 🎉 **Celebration Effects**: Confetti animations for completed tasks
- 📱 **Responsive Design**: Works on desktop and mobile devices
- 🌙 **Dark Theme**: Beautiful glassmorphism design with dark theme

## Live Demo

Visit the deployed application: [Launch Tracker](https://UofAZ.github.io/Tracker)

## Local Development

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/UofAZ/Tracker.git
   cd Tracker
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`

## Deployment to GitHub Pages

This project is configured for easy deployment to GitHub Pages using the `gh-pages` package.

### Automatic Deployment

1. Make sure your repository is set up on GitHub
2. Update the `homepage` field in `package.json` if needed:
   ```json
   "homepage": "https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME"
   ```

3. Deploy to GitHub Pages:
   ```bash
   npm run deploy
   ```

This will:
- Build the production version of your app
- Deploy it to the `gh-pages` branch
- Make it available at your GitHub Pages URL

### Manual Deployment

If you prefer manual deployment:

1. Build the project:
   ```bash
   npm run build
   ```

2. The built files will be in the `build` folder. You can deploy these files to any static hosting service.

## Project Structure

```
Tracker/
├── public/
│   ├── index.html          # Main HTML template
│   └── manifest.json       # PWA manifest
├── src/
│   ├── App.js              # Main React component
│   └── index.js            # React entry point
├── package.json            # Dependencies and scripts
└── README.md              # This file
```

## Customization

### Updating Sprint Data

To customize the sprint data, edit the `initialSprintData` object in `src/App.js`:

```javascript
const initialSprintData = {
  overallGoal: "Your sprint goal here",
  startDate: '2025-01-01',
  endDate: '2025-01-31',
  weeks: [
    // Your weeks data
  ],
  deliverables: [
    // Your deliverables
  ]
};
```

### Styling

The application uses Tailwind CSS for styling. The main styles are defined inline in the component, including:

- Glassmorphism effects
- Gradient backgrounds
- Animations and transitions
- Responsive design breakpoints

## Technologies Used

- **React 18**: Frontend framework
- **Tailwind CSS**: Utility-first CSS framework
- **Lucide React**: Beautiful icons
- **Create React App**: Build tooling
- **GitHub Pages**: Hosting

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Create a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you encounter any issues or have questions, please open an issue on GitHub.

---

Built with ❤️ for productive sprint tracking 