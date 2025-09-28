# Rio Nido Lodge - Itinerary Planning App

A React-based itinerary planning application for Rio Nido Lodge guests, featuring personalized recommendations for restaurants, wineries, activities, and signature experiences in the Russian River Valley area.

## Features

- **Personalized Itinerary Generation**: Creates custom day-by-day itineraries based on guest preferences
- **Budget-Aware Recommendations**: Filters experiences by budget preference (Budget, Moderate, Luxury)
- **90+ Local Businesses**: Comprehensive database of restaurants, wineries, activities, spas, and cafes
- **Signature Experiences**: Premium curated experiences from meditation in redwood groves to private winery dinners
- **Real-Time Business Hours**: Shows which businesses are currently open
- **Interactive Alternatives**: Swap activities with one-click alternatives
- **Mobile-Responsive Design**: Works seamlessly on all devices

## Technology Stack

- **React 18** - Frontend framework
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Icon library
- **Vercel** - Deployment platform

## Quick Start

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/rio-nido-lodge-app.git
   cd rio-nido-lodge-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```

4. **Open browser**
   Navigate to `http://localhost:3000`

## Deployment

### Deploy to Vercel (Recommended)

1. **Install Vercel CLI** (if not already installed)
   ```bash
   npm i -g vercel
   ```

2. **Deploy**
   ```bash
   vercel
   ```

3. **Follow prompts** to link your project and deploy

### Alternative: GitHub Integration
1. Push code to GitHub repository
2. Connect repository to Vercel dashboard
3. Automatic deployments on every push

## Project Structure

```
rio-nido-lodge-app/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── App.js          # Main application component
│   ├── index.js        # React entry point
│   └── index.css       # Tailwind CSS imports
├── package.json        # Dependencies and scripts
├── tailwind.config.js  # Tailwind configuration
├── .gitignore         # Git ignore rules
├── vercel.json        # Vercel deployment config
└── README.md          # This file
```

## Data Structure

The app includes comprehensive databases for:

- **Restaurants** (8+ locations): From casual diners to Michelin-starred establishments
- **Wineries** (6+ locations): Small-production artisan wineries to legendary Pinot Noir producers
- **Activities** (4+ locations): Nature reserves, water recreation, coastal hiking
- **Wellness** (5+ locations): Full-service spas to holistic wellness centers
- **Signature Experiences** (12+ options): Premium curated experiences from $45-$495

## Usage

1. **Enter Guest Information**: Name, trip duration, budget preference, travel style
2. **Select Interests**: Choose from wine tasting, nature, food, adventure, wellness, culture
3. **Generate Itinerary**: Creates personalized daily schedules
4. **Customize**: Refresh individual activities or browse alternatives
5. **Add Signature Experiences**: Enhance itinerary with premium experiences

## Features in Detail

### Budget Categories
- **Budget Conscious ($-$$)**: Great value experiences under $25-50 per person
- **Moderate Spending ($$-$$$)**: Balanced experiences, $50-100 per person  
- **Luxury Experience ($$$-$$$$)**: Premium experiences, $100+ per person

### Travel Styles
- **Relaxed**: 2 activities per day
- **Moderate**: 3 activities per day
- **Fast-Paced**: 4 activities per day

### Smart Scheduling
- Morning activities: Nature, coffee, bakeries, early wine tastings
- Lunch: Restaurant focus with appropriate hours
- Afternoon: Wine tastings, wellness, recreation
- Dinner: Fine dining options (moderate/fast-paced only)

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## Business Data Updates

To add new businesses or experiences:

1. **Restaurants/Activities**: Add to respective arrays in `BUSINESSES` constant
2. **Signature Experiences**: Add to `SIGNATURE_EXPERIENCES` array
3. **Required fields**: name, type, description, rating, budget, hours, location, phone, category

## License

MIT License - see LICENSE file for details

## Support

For issues or questions:
- Create GitHub issue
- Contact: [your-email@domain.com]

## Roadmap

- [ ] User accounts and saved itineraries
- [ ] Real-time availability integration
- [ ] Photo gallery for businesses
- [ ] Weather integration
- [ ] Export to calendar functionality
- [ ] Multi-language support

---

Built with ❤️ for Rio Nido Lodge guests
