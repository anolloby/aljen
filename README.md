# For My Beautiful Wife, Navy

A beautiful, interactive website created as a special gift. This is a static website that displays a romantic message with animations, music, and a photo gallery.

## 🌟 Features

- Interactive opening screen with a tappable circle
- Password protection (hint: "It's how we greet each other every day")
- Animated heart and love messages
- Background photo slideshow
- Music player ("I Got You")
- Fully responsive design for mobile and desktop

## 📦 What's Included

- `index.html` - Main website file
- `audio/` - Contains the music file
- `images/` - Contains the photo gallery (24 photos)
- `nav.js` - Navigation script (currently unused)

## 🚀 How to Deploy

This is a static website with no backend requirements, making it very easy to deploy for free!

### Option 1: GitHub Pages (Recommended - FREE)

GitHub Pages is the easiest and fastest way to deploy this website:

1. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on **Settings** (in the repository menu)
   - Scroll down to **Pages** (in the left sidebar under "Code and automation")
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** or **master** branch (whichever is your default)
   - Select **/ (root)** as the folder
   - Click **Save**

2. **Access Your Website:**
   - After a few minutes, your website will be live at:
   - `https://anolloby.github.io/aljen/`
   - GitHub will show you the URL on the Pages settings page

3. **Updates:**
   - Any changes you push to the main branch will automatically update the website

**Note:** GitHub Pages works perfectly for this website since all files are under 100MB and the repository is public.

### Option 2: Netlify (FREE)

Netlify offers continuous deployment with a simple drag-and-drop interface:

1. **Sign up for Netlify:**
   - Go to [netlify.com](https://www.netlify.com/)
   - Sign up with your GitHub account (free)

2. **Deploy from GitHub:**
   - Click **Add new site** → **Import an existing project**
   - Choose **GitHub** and authorize Netlify
   - Select your `aljen` repository
   - Click **Deploy site** (no build settings needed for static sites)

3. **Custom Domain (Optional):**
   - Netlify provides a free subdomain (e.g., `yoursite.netlify.app`)
   - You can add a custom domain in the settings if you have one

4. **Access Your Website:**
   - Your site will be live at the URL provided by Netlify
   - Auto-deploys on every push to the main branch

### Option 3: Vercel (FREE)

Vercel is another excellent option for static websites:

1. **Sign up for Vercel:**
   - Go to [vercel.com](https://vercel.com/)
   - Sign up with your GitHub account

2. **Import Repository:**
   - Click **Add New** → **Project**
   - Import your GitHub repository
   - No framework preset or build settings needed
   - Click **Deploy**

3. **Access Your Website:**
   - Your site will be live at the URL provided by Vercel
   - Auto-deploys on every push to the main branch

### Option 4: Traditional Web Hosting

If you have traditional web hosting (shared hosting, VPS, etc.):

1. **Download Your Files:**
   ```bash
   git clone https://github.com/anolloby/aljen.git
   ```

2. **Upload via FTP/SFTP:**
   - Use an FTP client (FileZilla, Cyberduck, etc.)
   - Upload all files to your web hosting's public directory:
     - `public_html/` or `www/` or `htdocs/` (varies by host)
   - Make sure to upload:
     - `index.html`
     - `audio/` folder with all contents
     - `images/` folder with all contents
     - `nav.js`

3. **Access Your Website:**
   - Visit your domain (e.g., `https://yourdomain.com`)

### Option 5: Local Testing

To test the website on your computer before deploying:

1. **Simple Python Server:**
   ```bash
   # Navigate to the project directory
   cd /path/to/aljen
   
   # Python 3
   python3 -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   Then open: `http://localhost:8000`

2. **Node.js Server:**
   ```bash
   # Install http-server globally (one time)
   npm install -g http-server
   
   # Run server
   cd /path/to/aljen
   http-server
   ```
   Then open: `http://localhost:8080`

3. **VS Code Live Server:**
   - Install the "Live Server" extension in VS Code
   - Right-click on `index.html`
   - Select "Open with Live Server"

## 🔧 Troubleshooting

### Audio Not Playing
- Most browsers block autoplay. The user will need to click the play button after entering the password
- Make sure the `audio/i got you.mp3` file is uploaded correctly

### Images Not Loading
- Verify that the `images/` folder contains all 24 `.jpg` files
- Check that file names match exactly (they're case-sensitive on some servers)

### Password Not Working
- The correct password is: `hi` (lowercase)
- Make sure to type it exactly

## 📱 Mobile Compatibility

This website is fully responsive and works great on:
- Desktop browsers (Chrome, Firefox, Safari, Edge)
- Mobile phones (iOS Safari, Chrome, Firefox)
- Tablets

## 💝 Personal Note

This is a personal romantic gift. Feel free to customize:
- Change the password in `index.html` (line 612)
- Update the message text
- Add or remove photos in the `images/` folder
- Change the music file in the `audio/` folder

## 📄 License

This is a personal project. All rights reserved.

---

**Made with ❤️ for Navy**
