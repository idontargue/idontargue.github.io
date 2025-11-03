# I Don't Argue - Website Files

Ready for GitHub Pages deployment.

## Files:
- `index.html` - Main website
- `tracker.html` - Free tracker landing page
- `book-cover.jpg` - Book cover image
- `argument-tracker.pdf` - Printable tracker
- `CNAME` - Custom domain configuration

## Deploy:
1. Create GitHub repo named `idontargue`
2. Upload all these files to the repo
3. Enable GitHub Pages in Settings → Pages
4. Add DNS records in Porkbun (see instructions)

## URLs once live:
- Main site: idontargue.com
- Tracker: idontargue.com/tracker.html
- PDF download: idontargue.com/argument-tracker.pdf

## Porkbun DNS Setup:
Add these A records:
- Type: A, Host: @, Answer: 185.199.108.153
- Type: A, Host: @, Answer: 185.199.109.153
- Type: A, Host: @, Answer: 185.199.110.153
- Type: A, Host: @, Answer: 185.199.111.153

Add CNAME for www:
- Type: CNAME, Host: www, Answer: YOUR-USERNAME.github.io
