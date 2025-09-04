# GitHub Profile Setup Instructions

This repository contains the special GitHub profile README that appears on your GitHub profile page.

## How to Use This Profile

1. **Repository Name**: This repository must be named exactly `ThyKinslayer` (matching your GitHub username) to appear on your profile.

2. **Upload to GitHub**:
   ```bash
   git remote add origin https://github.com/ThyKinslayer/ThyKinslayer.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Actions**:
   - Go to your repository settings
   - Navigate to "Actions" > "General"
   - Ensure "Allow all actions and reusable workflows" is selected
   - The workflow will automatically run every 6 hours to update your activity

4. **Customize the Profile**:
   - Edit `README.md` to personalize your information
   - Update social links in the "Connect With Me" section
   - Modify the tech stack badges to reflect your skills
   - Add or remove featured repositories

## Features Included

### 🎨 Dynamic Elements
- **Typing Animation**: Shows rotating text about your role
- **GitHub Stats**: Displays your contribution stats and most used languages
- **Streak Stats**: Shows your commit streak
- **Activity Feed**: Auto-updates with your recent GitHub activity
- **Contribution Snake**: Animated snake eating your contributions

### 📊 Statistics
- GitHub contribution statistics
- Language usage breakdown
- Repository showcase cards
- Trophy collection
- Profile visitor counter

### 🔄 Automated Updates
- Recent activity updates every 6 hours
- Contribution snake animation updates
- All powered by GitHub Actions

## Customization Tips

### Updating Personal Information
1. Replace "Shaun Venter" with your actual name
2. Update company information (currently "PureParagon")
3. Modify the bio and interests
4. Update social media links

### Adding/Removing Tech Badges
Find more badges at [shields.io](https://shields.io/) and [simple-icons](https://simpleicons.org/)

### Featured Repositories
Update the repository names in the "Featured Projects" section to showcase your best work.

## Repository Structure
```
.
├── README.md                    # Main profile page
├── .github/
│   └── workflows/
│       └── update-readme.yml    # GitHub Actions workflow
├── .gitignore                   # Git ignore file
└── SETUP.md                     # This file
```

## Troubleshooting

**Profile not showing?**
- Ensure the repository name matches your username exactly
- Make sure README.md is in the root directory
- Repository must be public

**GitHub Actions not working?**
- Check that Actions are enabled in repository settings
- Verify the workflow file syntax
- Check the Actions tab for error logs

**Stats not loading?**
- GitHub stats services sometimes have rate limits
- Try refreshing the page after a few minutes
- Check if the services are online

## Credits

This profile uses several amazing open-source projects:
- [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) for statistics
- [github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) for streak stats  
- [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) for typing animation
- [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) for trophies
- [snk](https://github.com/Platane/snk) for contribution snake
- [github-activity-readme](https://github.com/jamesgeorge007/github-activity-readme) for activity feed

Enjoy your new GitHub profile! 🚀
