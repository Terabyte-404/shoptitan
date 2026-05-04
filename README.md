# TITANSPORTS - Premium Sports Store

A comprehensive e-commerce platform for sports jerseys, gear, and equipment featuring a modern, responsive design with advanced filtering and shopping cart functionality.

## 🏆 Features

### 📱 Responsive Design
- Mobile-first approach with optimized layouts for all devices
- Touch-friendly interface for mobile shopping
- Adaptive navigation and product grids

### 🛒 Shopping Experience
- **Hierarchical Navigation**: All Sports → Sport → League → Team → Products
- **Product Categories**: Jerseys, Balls, Gear, Accessories, Apparel
- **Advanced Filtering**: Multi-level sport and team filtering
- **Shopping Cart**: Full cart management with add/remove functionality
- **Product Modal**: Detailed product views with size/quantity selection

### 🏀 Sports Coverage
- **Football**: Premier League, La Liga, Serie A, Bundesliga, Ligue 1, National Teams
- **Basketball**: NBA, EuroLeague, International Teams
- **NFL**: All 32 NFL teams
- **MLB**: All 30 MLB teams  
- **NHL**: All 32 NHL teams
- **Cricket**: International teams
- **Rugby**: International teams

### 🎨 Design & Branding
- **TITANSPORTS Branding**: Custom logo with orange/black/white color scheme
- **Modern UI**: Clean, professional interface with smooth animations
- **Hexagonal Logo Elements**: Unique brand identity
- **Consistent Styling**: Cohesive design across all components

## 🛍️ Product Catalog

### Jerseys & Apparel
- Official team jerseys for all major sports
- Multiple sizes available (S, M, L, XL, XXL)
- Authentic designs and licensed products

### Sports Equipment
- **Balls**: Football, Basketball, Soccer, Tennis, Golf, Cricket, Rugby
- **Gear**: Helmets, Pads, Gloves, Training Equipment
- **Accessories**: Water Bottles, Sports Bags, Fitness Trackers
- **Apparel**: Training Shorts, Compression Wear, Athletic Shoes

## 🚀 Technologies Used

### Frontend
- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with CSS variables and animations
- **JavaScript (ES6+)**: Vanilla JS with no dependencies
- **Responsive Design**: Mobile-first approach

### Features
- **Local Storage**: Cart persistence and product management
- **Dynamic Content**: JavaScript-driven product filtering
- **Modal System**: Interactive product detail views
- **Event Handling**: Comprehensive user interaction management

## 📁 Project Structure

```
Jerseyshop/
├── index.html          # Main homepage
├── admin.html           # Admin panel
├── login.html           # Admin login
├── css/
│   ├── styles.css       # Main stylesheet
│   └── admin.css        # Admin panel styles
├── js/
│   └── main.js          # Main JavaScript functionality
└── images/
    └── USE_THIS-removebg-preview.png  # Logo assets
```

## 🛠️ Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation
1. Clone or download the repository
2. Open `index.html` in your web browser
3. Start shopping!

### Development
For local development with a web server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (if installed)
npx serve .

# Using Live Server in VS Code
Right-click index.html → Open with Live Server
```

## 🌐 Deployment

### GitHub Pages
1. Push repository to GitHub
2. Go to Settings → Pages
3. Select main branch as source
4. Site will be live at `https://username.github.io/Jerseyshop`

### Netlify/Vercel
1. Connect repository to platform
2. Set build directory to root
3. Deploy site

## 📊 Data Management

### Product Structure
```javascript
{
    id: unique_id,
    name: "Product Name",
    sport: "sport_category",
    league: "league_name",
    price: price_in_ksh,
    image: "image_url"
}
```

### Sports Hierarchy
```javascript
const sportLeagues = {
    "sport_name": {
        "league_name": {
            teams: ["Team1", "Team2", ...]
        }
    }
}
```

## 🎯 Key Functions

### Navigation
- `filterBySport()` - Main sport filtering
- `renderSportLeagues()` - League display
- `showTeamsInLeague()` - Team navigation
- `filterByTeam()` - Product filtering

### Shopping Cart
- `addToCart()` - Add products to cart
- `removeFromCart()` - Remove items
- `updateCart()` - Cart UI updates
- `checkout()` - Checkout process

### Product Display
- `renderProducts()` - Product grid rendering
- `openProductModal()` - Product detail view
- `filterByEquipmentCategory()` - Equipment filtering

## 🔧 Customization

### Adding New Sports
1. Add sport data to `sportLeagues` object
2. Update `filterBySport()` function
3. Add corresponding render functions

### Adding Products
1. Update `defaultProducts` array
2. Follow existing product structure
3. Include appropriate sport/league data

### Branding Changes
1. Update CSS variables in `styles.css`
2. Replace logo assets in `images/`
3. Update brand text in HTML

## 📱 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🤝 Contributing

1. Fork the repository
2. Create feature branch
3. Make changes
4. Test thoroughly
5. Submit pull request

## 📄 License

This project is open source and available under the MIT License.

## 📞 Support

For support or questions:
- Create an issue in the repository
- Contact the development team

---

**TITANSPORTS - NOWHERE ELSE**  
*Premium sports jerseys, gear & equipment for champions*
