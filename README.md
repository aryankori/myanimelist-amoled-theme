# MyAnimeList AMOLED Theme 🌙
An ultra-dark, modern AMOLED theme for MyAnimeList with stunning cyan accents. Perfect for night-time browsing and OLED displays.

## ✨ Features
- **True AMOLED Black** - Pure black (#000000) background for perfect OLED blacks
- **Cyan Accents** - Beautiful cyan highlights (#00e5ff) for links and interactive elements
- **Modern Design** - Clean, contemporary styling with smooth borders and shadows
- **Color-Coded Scores** - Intuitive color system for anime/manga ratings
- **Status Colors** - Easy identification of watching/completed/dropped status
- **Custom Scrollbar** - Themed scrollbar that matches the dark aesthetic
- **Eye-Friendly** - Reduced eye strain for extended browsing sessions

## 🎨 Color Palette
- Primary Background: `#000000` (True Black)
- Secondary Background: `#0a0a0a`
- Card Background: `#0f0f0f`
- Accent Cyan: `#00e5ff`
- Text Primary: `#e0e0e0`
- Text Secondary: `#9e9e9e`

## 📦 Installation

### Using Stylus (Recommended)
1. Install [Stylus](https://add0n.com/stylus.html) browser extension
   - [Chrome Web Store](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
   - [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
2. Click on the Stylus icon in your browser
3. Click "Manage"
4. Click "Write new style"
5. Copy and paste the contents of `style.css` into the editor
6. Under "Applies to", add:
   - URL starting with: `https://myanimelist.net/`
7. Give it a name (e.g., "MyAnimeList AMOLED Theme")
8. Click "Save"

### Manual Installation
1. Download or copy the contents of `style.css`
2. Use any CSS injection tool of your choice
3. Apply the styles to `myanimelist.net`

## 📋 Step-by-Step Guide for Beginners

### Method 1: Apply Theme Directly to MyAnimeList (Using Browser Extension)

**Step 1: Install a User Style Manager**
1. Install the [Stylus browser extension](https://add0n.com/stylus.html)
   - For Chrome: [Chrome Web Store Link](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
   - For Firefox: [Firefox Add-ons Link](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

**Step 2: Get the CSS Code**
2. Open the [`style.css` file](https://github.com/aryankori/myanimelist-amoled-theme/blob/main/style.css) in this repository
3. Click the "Raw" button to view the raw CSS code
4. Select all the code (Ctrl+A or Cmd+A) and copy it (Ctrl+C or Cmd+C)

**Step 3: Create New Style in Stylus**
5. Click on the Stylus extension icon in your browser toolbar
6. Click "Manage" to open the Stylus management page
7. Click "Write new style" button
8. Paste the copied CSS code into the code editor

**Step 4: Configure the Style**
9. Give your style a name (e.g., "MyAnimeList AMOLED Theme")
10. In the "Applies to" section, select "URLs on the domain" and enter: `myanimelist.net`
11. Click the "Save" button (usually on the left sidebar)

**Step 5: Apply on MyAnimeList**
12. Visit [MyAnimeList](https://myanimelist.net/) - specifically go to [your anime list](https://myanimelist.net/animelist/) or [manga list](https://myanimelist.net/mangalist/)
13. The theme should now be applied automatically!

### Method 2: Using MyAnimeList's Built-in Style Editor (Advanced)

**Note:** MyAnimeList has character limits for custom CSS, so this method may require trimming the CSS.

**Step 1: Access MAL List Style Settings**
1. Go to [MyAnimeList](https://myanimelist.net/) and sign in to your account
2. Navigate to your anime list: [https://myanimelist.net/animelist/YOUR_USERNAME](https://myanimelist.net/animelist/)
3. Click on "List Style" or "Edit List Style" (usually in the top-right corner)
4. Or directly visit: [https://myanimelist.net/editprofile.php?go=listpreferences](https://myanimelist.net/editprofile.php?go=listpreferences)

**Step 2: Choose Custom CSS Option**
5. Scroll down to the "List Template" section
6. Select a template that allows custom CSS (usually "Classic" or "Modern" templates)
7. Look for the "Advanced CSS" or "Custom CSS" textarea

**Step 3: Add the Theme CSS**
8. Copy the CSS from [`style.css`](https://github.com/aryankori/myanimelist-amoled-theme/blob/main/style.css)
9. Paste it into the Custom CSS textarea
10. If you hit character limits, you may need to minify the CSS or remove comments
11. Click "Save Changes" at the bottom of the page

### Method 3: Edit This Theme Online (For Contributors)

**Option A: Using GitHub's Web Editor**
1. Navigate to this repository: [https://github.com/aryankori/myanimelist-amoled-theme](https://github.com/aryankori/myanimelist-amoled-theme)
2. Click on the file you want to edit (e.g., `style.css` or `README.md`)
3. Click the pencil icon (✏️) labeled "Edit this file" in the top-right
4. Make your changes in the web editor
5. Scroll down to "Commit changes" section
6. Add a commit message describing your changes
7. Click "Propose changes" or "Commit changes"

**Direct Edit Links:**
- [Edit style.css online](https://github.com/aryankori/myanimelist-amoled-theme/edit/main/style.css)
- [Edit README.md online](https://github.com/aryankori/myanimelist-amoled-theme/edit/main/README.md)

**Option B: Using GitHub.dev (VS Code in Browser)**
1. Go to this repository: [https://github.com/aryankori/myanimelist-amoled-theme](https://github.com/aryankori/myanimelist-amoled-theme)
2. Press the period key (`.`) on your keyboard, OR
3. Change the URL from `github.com` to `github.dev` - visit: [https://github.dev/aryankori/myanimelist-amoled-theme](https://github.dev/aryankori/myanimelist-amoled-theme)
4. This opens a full VS Code editor in your browser
5. Edit any files using the familiar VS Code interface
6. Use the Source Control panel (left sidebar) to commit and push changes

**Option C: Using Other Online IDEs**

**CodeSandbox:**
1. Visit: [https://codesandbox.io/](https://codesandbox.io/)
2. Click "Import Project" or "Import from GitHub"
3. Enter this repository URL: `https://github.com/aryankori/myanimelist-amoled-theme`
4. Edit files in the CodeSandbox editor

**Gitpod:**
1. Prefix this repository URL with `gitpod.io/#` - visit: [https://gitpod.io/#https://github.com/aryankori/myanimelist-amoled-theme](https://gitpod.io/#https://github.com/aryankori/myanimelist-amoled-theme)
2. This launches a full cloud development environment
3. Edit files and commit changes directly

**StackBlitz:**
1. Visit: [https://stackblitz.com/github/aryankori/myanimelist-amoled-theme](https://stackblitz.com/github/aryankori/myanimelist-amoled-theme)
2. Edit files in the StackBlitz editor

## 🖼️ Screenshots
*Experience the dark side of anime tracking with our AMOLED theme!*

## 🎯 Compatibility
- ✅ Works on all modern browsers (Chrome, Firefox, Edge, Safari)
- ✅ Compatible with MyAnimeList's current design
- ✅ Optimized for desktop and mobile viewing
- ✅ Perfect for OLED/AMOLED displays

## 🛠️ Customization
Want to personalize the theme? You can easily modify the CSS variables at the top of `style.css`:

```css
:root {
  --primary-bg: #000000;        /* Change background color */
  --accent-cyan: #00e5ff;       /* Change accent color */
  --text-primary: #e0e0e0;      /* Change text color */
  /* ... and more! */
}
```

## 📝 Notes
- This theme uses CSS variables for easy customization
- All important declarations use `!important` to override default MAL styles
- The theme includes hover effects and smooth transitions
- Status and score colors are carefully chosen for readability

## 🤝 Contributing
Feel free to:
- Report issues
- Suggest improvements
- Submit pull requests
- Share your customizations

## 📄 License
MIT License - feel free to use, modify, and distribute!

## 🌟 Support
If you enjoy this theme, consider:
- ⭐ Starring this repository
- 🐛 Reporting bugs or issues
- 💡 Suggesting new features
- 🔄 Sharing with other MAL users

## 🔗 Links
- [MyAnimeList](https://myanimelist.net/)
- [Stylus Extension](https://add0n.com/stylus.html)

---

**Happy browsing! 🎬✨**

Made with ❤️ for the anime community
