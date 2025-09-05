# Franklin Elementary Color Walk 2025

A comprehensive Jekyll website for the Franklin Falcons' 10th Annual Color Walk fundraising event, featuring interactive games and sponsor acknowledgments.

## 🎨 Features

### 📱 **Interactive Coloring Game**
- Click-to-color Franklin Falcon and rainbow SVG
- 12-color palette with visual feedback
- Sparkle animations and hover effects
- Mobile-responsive design

### 🎯 **Color Walk Bingo**
- Interactive 5×5 bingo grid with school-themed activities
- Student registration form with prize selection
- Progress tracking and win detection
- Print-optimized for physical bingo cards

### 🏢 **Sponsor Showcase**
- 19 local business sponsors with logos
- Organized by category (Healthcare, Education, Food & Dining, etc.)
- Interactive cards with website links
- Professional presentation with hover effects

### 🏠 **Event Homepage**
- Event details and fundraising goals ($45,000)
- Participation instructions and incentives
- School spirit and community focus
- Clear calls-to-action

## 🚀 Quick Start

1. **Install Ruby** (version 2.7 or higher)
2. **Install Bundler**:
   ```bash
   gem install bundler
   ```

3. **Install dependencies**:
   ```bash
   bundle install
   ```

4. **Run the site locally**:
   ```bash
   bundle exec jekyll serve
   ```

5. **View the site**: Open http://localhost:4000 in your browser

## 📁 Project Structure

```
franklin-walkathon-2025/
├── 📄 index.html              # Event homepage
├── 🎨 coloring-game.html      # Interactive coloring game
├── 🎯 bingo.html              # Interactive bingo game
├── 🏢 sponsors.html           # Sponsor acknowledgments
├── ⚙️ _config.yml            # Site configuration
├── 📁 _layouts/
│   └── default.html          # Main layout template
├── 📁 assets/
│   ├── 🎨 css/style.css      # Main stylesheet (~1,700 lines)
│   └── 🖼️ images/           # All images (20+ sponsor logos)
├── 📁 .claude/
│   └── CLAUDE.md             # Detailed technical documentation
└── 📄 README.md              # This file
```

## 🎯 Event Details

- **Event**: 10th Annual Color Walk
- **Date**: October 3, 2025
- **School**: Franklin Elementary
- **Mascot**: Franklin Falcons
- **Goal**: $45,000 fundraising target
- **Colors**: Green (#066C2D) and Yellow (#FFE13B)

## 🛠️ Technology Stack

- **Framework**: Jekyll (GitHub Pages compatible)
- **Styling**: Custom CSS with CSS Variables
- **JavaScript**: Vanilla JS for interactive features
- **Images**: 19 sponsor logos + event branding
- **Responsive**: Mobile-first design approach

## 🎮 Interactive Features

### Coloring Game
- **Technology**: SVG + JavaScript
- **Elements**: Falcon, rainbow, stars, clouds
- **Interactions**: Click to color, hover effects, reset button
- **Feedback**: Sparkle animations on click

### Bingo Game
- **Grid**: 5×5 with school-themed activities
- **Features**: Student form, progress tracking, print support
- **Activities**: Color-coded by category
- **Persistence**: Local storage for game state

## 🏢 Sponsor Management

**19 Local Business Sponsors** across categories:
- Healthcare & Wellness (2)
- Education & Activities (3)
- Music & Arts (3)
- Entertainment (1)
- Food & Dining (5)
- Professional Services (3)
- Recreation & Fitness (2)
- Individual Supporters (1)

All logos are professionally displayed with consistent sizing and styling.

## 📱 Responsive Design

- **Desktop**: Full interactive experience
- **Tablet**: Optimized layouts and touch interactions
- **Mobile**: Streamlined interface, smaller logos
- **Print**: Special styles for bingo cards

## 🚀 Deployment

### GitHub Pages (Recommended)
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Site will be available at `https://username.github.io/repository-name`

### Manual Build
```bash
bundle exec jekyll build
```
Upload `_site/` directory contents to web server.

## 🎨 Design System

### Color Palette
```css
Primary Green:    #066C2D  (Franklin school color)
Secondary Yellow: #FFE13B  (Bright accent)
Light Green:      #4CAF50  (Success states)
Dark Green:       #004D1F  (Text and borders)
Accent Orange:    #FF6B35  (Call-to-action buttons)
```

### Typography
- **Headers**: Bold, uppercase styling for impact
- **Body**: Clean, readable sans-serif fonts
- **Interactive**: Clear button and link styling

## 📊 Analytics & Performance

- **Lighthouse Ready**: Optimized for performance scores
- **Accessibility**: WCAG-compliant color contrasts
- **SEO**: Meta tags and semantic HTML structure
- **Mobile Speed**: Optimized images and CSS

## 🤝 Community Impact

This website serves the Franklin Elementary community by:
- **Engaging Families**: Interactive games for children
- **Supporting Local Business**: Prominent sponsor showcase
- **Raising Funds**: Clear donation pathways and goals
- **Building School Spirit**: Franklin Falcon branding throughout

## 📞 Support

For technical questions about this website, see the detailed documentation in `.claude/CLAUDE.md`.

For event-related questions, contact Franklin Elementary School directly.

---

**🦅 Go Franklin Falcons! Let's make this the best Color Walk yet! 🌈**