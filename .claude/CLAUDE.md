# Franklin Elementary Color Walk 2025 - Claude Code Project

## Project Overview
This is a Jekyll-based website for Franklin Elementary's 10th Annual Color Walk fundraising event. The site includes interactive features like a coloring game and bingo game, along with comprehensive sponsor acknowledgments.

## Technology Stack
- **Framework**: Jekyll (GitHub Pages compatible)
- **Styling**: Custom CSS with CSS Variables
- **JavaScript**: Vanilla JS for interactive features
- **Deployment**: Designed for GitHub Pages

## Site Structure
```
franklin-walkathon-2025/
├── _config.yml              # Jekyll configuration
├── _layouts/
│   └── default.html         # Main layout template
├── assets/
│   ├── css/
│   │   └── style.css        # Main stylesheet (~1,700 lines)
│   └── images/              # All images including sponsor logos
├── index.html               # Homepage
├── coloring-game.html       # Interactive coloring game
├── bingo.html              # Interactive bingo game
├── sponsors.html           # Sponsor acknowledgments with logos
└── README.md               # Project documentation
```

## Key Features Implemented

### 1. Homepage (`index.html`)
- Hero section with event branding
- Information about the Color Walk event
- Fundraising goal ($45,000) and fund allocation
- Incentives and rewards section
- How to participate guide
- Call-to-action buttons linking to other pages

### 2. Interactive Coloring Game (`coloring-game.html`)
- **Technology**: Vanilla JavaScript + SVG
- **Features**:
  - 12-color palette with click-to-select
  - Interactive SVG falcon, rainbow, and decorative elements
  - Visual feedback (hover effects, click animations, sparkle effects)
  - Reset functionality
  - Educational content about Franklin Falcon values
- **Responsive**: Mobile-friendly design

### 3. Interactive Bingo Game (`bingo.html`)
- **Technology**: Vanilla JavaScript
- **Features**:
  - Student registration form (name, grade, teacher, prize selection)
  - 5x5 bingo grid with color-coded activities
  - Click-to-mark squares with visual feedback
  - Progress tracking (squares completed, lines achieved)
  - Reset and print functionality
  - Print-optimized CSS for physical bingo cards
- **Accessibility**: High contrast, clear typography

### 4. Sponsors Page (`sponsors.html`)
- **20 sponsor logos** organized by category:
  - Healthcare & Wellness (2 sponsors)
  - Education & Activities (3 sponsors)
  - Music & Arts (3 sponsors)
  - Entertainment (1 sponsor)
  - Food & Dining (5 sponsors)
  - Professional Services (4 sponsors)
  - Recreation & Fitness (2 sponsors)
- **Features**: Hover effects, website links, appreciation section
- **Logo Management**: All logos in `assets/images/` with consistent sizing

## Event Details (from _config.yml)
- **School**: Franklin Elementary
- **Mascot**: Franklin Falcons
- **Event Date**: October 3, 2025
- **Fundraising Goal**: $45,000
- **Theme Colors**: Green (#066C2D) and Yellow (#FFE13B)

## CSS Architecture
The stylesheet (`assets/css/style.css`) is organized into sections:
1. **CSS Variables**: Color scheme and design tokens
2. **Base Styles**: Typography, layout foundations
3. **Component Styles**: Reusable UI components
4. **Page-Specific Styles**: Homepage, coloring game, bingo, sponsors
5. **Responsive Design**: Mobile-first approach
6. **Print Styles**: Optimized for bingo card printing

## Interactive JavaScript Features

### Coloring Game JavaScript
- Color palette management
- SVG element interaction
- Animation effects (scaling, sparkles)
- Dynamic color application
- Reset functionality

### Bingo Game JavaScript
- Form handling and validation
- Grid state management
- Win condition detection
- Progress tracking
- Local storage for persistence
- Print preparation

## Development Commands
Since this is a Jekyll site, use standard Jekyll commands:
```bash
# Local development
bundle exec jekyll serve

# Build for production
bundle exec jekyll build

# Install dependencies
bundle install
```

## Asset Management
- **Images**: All in `assets/images/` directory
- **Sponsor Logos**: 19 individual logo files (PNG/JPG)
- **Main Logo**: `color-walk-logo.jpg`
- **Favicon**: `favicon.ico` in root

## Browser Compatibility
- **Modern Browsers**: Full feature support
- **Mobile**: Responsive design with touch interactions
- **Print**: Optimized bingo card printing
- **Accessibility**: WCAG-compliant color contrasts

## Future Enhancement Opportunities
1. **Backend Integration**: Connect to donation platform APIs
2. **Real-time Updates**: Progress tracking for fundraising goals
3. **Social Sharing**: Add social media integration
4. **Email Integration**: Automated sponsor thank-you emails
5. **Analytics**: Track page engagement and conversions

## Sponsor Logo Management
Logos are automatically sized and styled:
- **Desktop**: Max 120px × 80px
- **Mobile**: Max 100px × 60px
- **Styling**: White background, rounded corners, shadow effects
- **Format**: PNG/JPG files with consistent naming convention

## Color Scheme
```css
--primary-green: #066C2D    /* Franklin school color */
--secondary-yellow: #FFE13B  /* Accent color */
--light-green: #4CAF50      /* Success states */
--dark-green: #004D1F       /* Dark variants */
--accent-orange: #FF6B35    /* Call-to-action */
```

This project successfully combines modern web development practices with school fundraising needs, creating an engaging and functional website for the Franklin Elementary community.