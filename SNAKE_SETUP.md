# 🐍 Kingdom of Code Snake Setup

## How to Deploy the Epic Snake Game

### 1. **Copy the Files**
Copy these files to your `AgnayS/AgnayS` repository:
- `.github/workflows/snake.yml` → GitHub Action
- The updated `README.md` with snake section

### 2. **Repository Setup**
1. Make sure your repository is named `AgnayS/AgnayS` (GitHub profile repo)
2. The repository must be **public** for the snake to work
3. Make sure GitHub Actions are enabled in repository settings

### 3. **First Run**
1. Push the files to your main branch
2. Go to **Actions** tab in your repository
3. Click on **"Generate Snake Game"** workflow
4. Click **"Run workflow"** to trigger the first generation
5. Wait ~2-3 minutes for it to complete

### 4. **Custom Colors**
The snake uses Kingdom colors:
- **Dark mode:** AutoJobs green (#00D4AA) snake eating colorful contributions
- **Light mode:** Architect blue (#2E86AB) snake with rainbow dots
- **Contribution colors:** Mix of your brand colors (green, blue, orange)

### 5. **How It Works**
- **Automatic:** Runs daily at midnight UTC to update
- **Manual:** You can trigger it anytime from Actions tab
- **Output:** Creates SVG files in an `output` branch
- **Display:** README shows different versions for light/dark mode

### 6. **Troubleshooting**
- **Snake not showing?** Check Actions tab for errors
- **Wrong colors?** Modify the `color_snake` and `color_dots` in snake.yml
- **Not updating?** Make sure you have commits to "eat"!

### 🎮 **Result**
Your profile will show an animated snake that:
- Eats your GitHub contribution squares chronologically
- Grows longer as it consumes more contributions
- Updates daily with new commits
- Switches colors based on light/dark mode
- Represents your coding journey visually

**The snake becomes part of your Kingdom of Code story!** 🏰🐍