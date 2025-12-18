# youareuglyandyouarepoor.com - Vanilla Site Showcase

## Files Included
- `index.html` - The main page
- `styles.css` - All the styling

## Project Purpose
This is a learning project and showcase of vanilla web development skills. The site demonstrates:
- Hand-coded HTML/CSS (no templates or frameworks)
- Responsive design
- Modern CSS techniques (Grid, Flexbox, gradients)
- Clean, semantic markup

Future plans: TBD. For now, it's proof of concept and a playground for learning.

## Important Note About JMR Motion
JMRMotion.com is a separate site that needs to be transferred from Squarespace. When transferring:
- Make sure Google Workspace email service stays active during migration
- Keep email MX records properly configured
- Test email thoroughly after transfer

## How to Upload to SiteGround

### Option 1: File Manager (Easiest)
1. Log into your SiteGround account
2. Go to Site Tools → File Manager
3. Navigate to `public_html` folder (this is your website root)
4. Upload both `index.html` and `styles.css` to this folder
5. Visit your domain - it should show your new site!

### Option 2: FTP (More Control)
1. Download FileZilla (free FTP client)
2. Get FTP credentials from SiteGround (Site Tools → FTP Accounts)
3. Connect via FileZilla
4. Upload both files to `public_html` folder

## Testing Locally First (Recommended)

### Using VS Code + Live Server:
1. Open VS Code
2. Install "Live Server" extension
3. Right-click on `index.html`
4. Choose "Open with Live Server"
5. It opens in your browser with auto-refresh as you edit

## Customizing Your Site

### Easy Changes:
- Edit the text in `index.html` - change company name, services, about text
- Change colors in `styles.css` - look for hex codes like `#667eea`
- Add your own images (save them in same folder, reference like `<img src="yourimage.jpg">`)

### Key Sections in HTML:
- **Header** - Company name and tagline
- **Hero** - Big headline section
- **Services** - The three cards
- **About** - Description paragraph
- **Footer** - Copyright info

Have fun experimenting! The site is fully responsive (looks good on phones/tablets/desktop).

## What's Next?
Once you're comfortable with this, you can:
- Add more pages (create `about.html`, link to it)
- Add a contact form (requires some backend setup)
- Add images and videos
- Experiment with JavaScript for interactivity
