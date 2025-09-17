# Vrukshavalli - Premium Plant Nursery Website

A complete, production-ready plant nursery website built for Netlify deployment with AI-powered plant care assistance.

## 🌱 Features

### Customer Features
- **Product Catalog**: Browse premium plants by category (Indoor, Outdoor, Fruit, Flower)
- **AI Plant Doctor**: Upload plant photos or describe symptoms for instant diagnosis
- **Smart Search & Filters**: Find plants by name, category, or price range
- **Shopping Cart**: Add/remove items with quantity management
- **Secure Checkout**: Cash on Delivery and mock payment integration
- **Order Tracking**: Real-time order status and delivery tracking
- **User Authentication**: Register/login with secure JWT tokens
- **Responsive Design**: Perfect experience on all devices

### Admin Features
- **Admin Dashboard**: Complete business overview with stats
- **Product Management**: Add, edit, delete products with image management
- **Order Management**: Track and update order statuses
- **Customer Management**: View user data and order history

### Technical Features
- **Static Site Generation**: Fast-loading, SEO-optimized pages
- **Serverless Backend**: Netlify Functions for all API endpoints
- **AI Integration**: OpenAI GPT for plant diagnosis and care advice
- **Local Storage**: Persistent shopping cart and user sessions
- **Image Optimization**: Automatic image resizing and optimization

## 🚀 Quick Deploy to Netlify

### One-Click Deploy
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/your-username/vrukshavalli)

### Manual Deploy

1. **Fork/Download** this repository
2. **Connect to Netlify**:
   - Go to [Netlify](https://netlify.com)
   - Click "New site from Git"
   - Connect your repository
   - Deploy settings are automatically configured via `netlify.toml`

3. **Set Environment Variables** in Netlify Dashboard:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. **Deploy**: Netlify will automatically build and deploy your site!

## 🛠️ Local Development

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Setup
```bash
# Clone the repository
git clone <repository-url>
cd vrukshavalli

# Install dependencies
npm install
# or
yarn install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your OpenAI API key

# Start development server
npm run dev
# or
yarn dev
```

Visit `http://localhost:3000` to see your site.

## 📁 Project Structure

```
vrukshavalli/
├── pages/                  # Next.js pages
│   ├── index.js           # Homepage
│   ├── products.js        # Product catalog
│   ├── plant-doctor.js    # AI plant diagnosis
│   ├── cart.js            # Shopping cart
│   ├── admin.js           # Admin panel
│   └── auth.js            # Authentication
├── components/            # Reusable components
│   ├── Navigation.js      # Site navigation
│   └── ProductCard.js     # Product display
├── netlify/functions/     # Serverless API functions
│   ├── products.js        # Product management
│   ├── plant-diagnosis.js # AI plant doctor
│   ├── orders.js          # Order management
│   └── auth.js            # User authentication
├── styles/               # Global styles
├── netlify.toml          # Netlify configuration
└── package.json          # Dependencies
```

## 🔧 Configuration

### Environment Variables

Set these in your Netlify dashboard under Site Settings > Environment Variables:

| Variable | Description | Required |
|----------|-------------|----------|
| `OPENAI_API_KEY` | OpenAI API key for plant diagnosis | Yes |

### Netlify Configuration

The `netlify.toml` file automatically configures:
- Build settings
- Function deployment
- Redirect rules for API routes
- Security headers

## 🎨 Customization

### Branding
- Update colors in `tailwind.config.js`
- Replace logo and favicon in `/public`
- Modify business information in components

### Products
- Add/edit products via the admin panel
- Or modify the sample data in `netlify/functions/products.js`

### AI Plant Doctor
- Customize the system prompt in `netlify/functions/plant-diagnosis.js`
- Add specific plant knowledge for your region

## 📱 Demo Credentials

### Admin Access
- **Email**: admin@vrukshavalli.com
- **Password**: admin123

### Demo Order Tracking
- **Order Numbers**: VRK1703000001, VRK1703000002

## 🔒 Security Features

- JWT-based authentication
- Input validation and sanitization
- CORS protection
- XSS protection headers
- Secure API endpoints

## 📈 Performance

- **100/100 Lighthouse Score** potential
- Static site generation for optimal loading
- Image optimization
- Serverless functions for scalability
- CDN delivery via Netlify

## 🛒 E-commerce Features

- Product catalog with categories
- Advanced search and filtering
- Shopping cart with persistence
- Order management system
- Payment integration ready
- Order tracking system

## 🤖 AI Integration

- OpenAI GPT-4 for plant diagnosis
- Image analysis capabilities
- Context-aware responses
- Regional plant knowledge (India-specific)

## 📞 Support

For technical support or customization:
1. Check the documentation
2. Review the code comments
3. Test with demo data first
4. Ensure environment variables are set correctly

## 🌟 Features in Detail

### Plant Doctor AI
- Upload plant images for visual diagnosis
- Text-based symptom description
- Regional climate considerations
- Treatment recommendations
- Organic solution preferences

### Admin Dashboard
- Sales analytics and reporting
- Inventory management
- Order processing workflow
- Customer management
- Product catalog management

### Customer Experience
- Intuitive navigation
- Mobile-first design
- Fast page loading
- Secure checkout process
- Order tracking system

## 📦 Deployment Checklist

- [ ] Environment variables configured
- [ ] OpenAI API key added
- [ ] Custom domain configured (optional)
- [ ] SSL certificate enabled (automatic)
- [ ] Analytics configured (optional)
- [ ] Error monitoring setup (optional)

## 🔄 Updates & Maintenance

The site is designed for easy maintenance:
- Products managed via admin panel
- Orders tracked in real-time
- Static site rebuilds automatically
- Serverless functions scale automatically

## 📊 Analytics Ready

Ready for integration with:
- Google Analytics
- Netlify Analytics
- Custom tracking solutions

Your Vrukshavalli plant nursery website is now ready for production! 🌱