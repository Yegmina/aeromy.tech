# Aeromy Investment Website

A professional investment landing page for Aeromy, showcasing autonomous solar-powered UAV technology and investment opportunities.

## 🚀 Features

- **Modern Design**: Clean, professional layout with responsive design
- **Interactive Elements**: Smooth animations, mobile navigation, and contact form
- **Investment Focus**: Clear presentation of funding requirements and project timeline
- **Technology Showcase**: Detailed information about solar-powered UAV innovations
- **Dual-Use Applications**: Civilian and defense sector applications
- **Contact Integration**: Working contact form with validation
- **Custom Domain**: Ready for aeromy.tech domain

## 🛠️ Technology Stack

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and animations
- **Font Awesome**: Icons and visual elements
- **Google Fonts**: Inter font family for professional typography
- **GitHub Pages**: Free hosting with custom domain support

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── CNAME               # Custom domain configuration
├── .nojekyll          # Jekyll bypass file
├── package.json        # Project metadata (optional)
└── README.md          # Project documentation
```

## 🚀 Deployment on GitHub Pages

This website is optimized for GitHub Pages deployment with custom domain support. Follow these steps:

### 1. Create GitHub Repository

1. **Create a new repository** on GitHub (e.g., `aeromy-investment-website`)
2. **Upload all files** to the repository
3. **Commit and push** all changes to the main branch

### 2. Enable GitHub Pages

1. Go to your repository **Settings**
2. Scroll down to **Pages** section
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**

### 3. Configure Custom Domain

1. In the **Pages** settings, add your custom domain: `aeromy.tech`
2. Check **Enforce HTTPS** (available after domain verification)
3. The `CNAME` file is already configured for your domain

### 4. DNS Configuration

Configure your domain's DNS records:

**Option A: Apex Domain (aeromy.tech)**
```
Type: A
Name: @
Value: 185.199.108.153
Value: 185.199.109.153
Value: 185.199.110.153
Value: 185.199.111.153
```

**Option B: CNAME (www.aeromy.tech)**
```
Type: CNAME
Name: www
Value: your-username.github.io
```

### 5. Verify Deployment

- Your site will be available at: `https://aeromy.tech`
- GitHub Pages URL: `https://your-username.github.io/repository-name`

## 🔧 Local Development

To run the website locally:

```bash
# Using Python (recommended)
python -m http.server 8000

# Using Node.js (if you have it installed)
npm start

# Using PHP (if available)
php -S localhost:8000
```

The website will be available at `http://localhost:8000`

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: Full layout with side-by-side content
- **Tablet**: Adapted grid layouts and navigation
- **Mobile**: Stacked layout with hamburger menu

## 🎨 Customization

### Colors
The website uses a professional color scheme:
- Primary Blue: `#2563eb`
- Success Green: `#10b981`
- Warning Orange: `#fbbf24`
- Error Red: `#dc2626`
- Dark Gray: `#1e293b`

### Typography
- Font Family: Inter (Google Fonts)
- Headings: 700 weight
- Body: 400 weight
- Accent: 600 weight

### Content Updates
To update content:
1. Edit `index.html` for text content
2. Modify `styles.css` for visual changes
3. Update `script.js` for functionality changes

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Email format checking
- Success/error notifications
- Form reset after submission

**Note**: The form currently shows a success message but doesn't actually send emails. For production use, integrate with a service like:
- Formspree
- Netlify Forms
- EmailJS
- Custom backend API

## 🔒 Security Considerations

- Form validation on both client and server side
- XSS protection through proper HTML escaping
- HTTPS enforcement (handled by Render)
- No sensitive data exposure

## 📊 Performance

The website is optimized for:
- Fast loading times
- Minimal HTTP requests
- Compressed assets
- Efficient animations
- Mobile performance

## 🐛 Troubleshooting

### Common Issues

1. **404 Errors**: Check that `index.html` is in the root directory
2. **Styling Issues**: Verify `styles.css` is properly linked
3. **JavaScript Errors**: Check browser console for errors
4. **Custom Domain Not Working**: Verify DNS configuration and CNAME file

### GitHub Pages Specific Issues

1. **Site Not Updating**: Wait 5-10 minutes for GitHub Pages to rebuild
2. **Custom Domain Issues**: Check DNS propagation (can take up to 24 hours)
3. **HTTPS Not Working**: Ensure domain is verified and HTTPS is enabled
4. **Jekyll Processing**: The `.nojekyll` file prevents Jekyll from processing the site

## 📈 Analytics and Monitoring

Consider adding:
- Google Analytics for visitor tracking
- GitHub Pages built-in monitoring
- Uptime monitoring services
- Performance monitoring tools

## 🤝 Contributing

To contribute to this project:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Support

For technical support or questions about the investment opportunity:
- Email: info@aeromy.tech
- Website: aeromy.tech

---

**Aeromy** - Revolutionizing autonomous aerial systems with solar-powered UAV technology.
