# Cheap Flight Search App

A modern React application for finding affordable flights across Europe, Georgia, and Turkey during the holiday period (December 22, 2025 - January 7, 2026).

## Features

- **Budget-focused search**: Find flights under €100 one way
- **Flexible trip duration**: Search for trips lasting 4-6 days
- **Multiple destinations**: Covers Europe, Georgia, and Turkey
- **Real-time filtering**: Results filtered by price and duration requirements
- **Modern UI**: Clean, responsive design with intuitive controls

## Search Criteria

The application is specifically designed for:
- **Travel period**: December 22, 2025 - January 7, 2026
- **Maximum price**: €100 one way
- **Trip duration**: 4-6 days
- **Destinations**: Europe, Georgia, and Turkey
- **Departure airports**: Major Polish airports (Warsaw, Krakow, Gdansk, Wroclaw)

## Destinations Covered

### Europe
- **Portugal**: Lisbon, Porto, Madeira
- **Spain**: Madrid, Barcelona
- **Italy**: Rome, Milan
- **Greece**: Athens, Thessaloniki
- **Central Europe**: Budapest, Prague, Vienna, Zurich
- **Western Europe**: Amsterdam, Brussels, Paris, London, Dublin
- **Scandinavia**: Stockholm, Oslo, Copenhagen, Helsinki
- **Baltic States**: Riga, Tallinn, Vilnius
- **Balkans**: Sofia, Bucharest, Belgrade, Zagreb, Ljubljana, Bratislava
- **Cyprus & Malta**: Larnaca, Malta

### Turkey
- Istanbul, Ankara, Antalya, Izmir, Dalaman, Bodrum

### Georgia
- Tbilisi, Kutaisi, Batumi

## Airlines Included

- Ryanair
- Wizz Air
- EasyJet
- LOT Polish Airlines
- Lufthansa
- Air France
- KLM
- Turkish Airlines
- Georgian Airways
- Pegasus Airlines
- Corendon Airlines

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd flight-search-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## How to Use

1. **Select departure airport**: Choose from major Polish airports
2. **Set travel dates**: Pick departure and return dates within the specified period
3. **Adjust passengers**: Set the number of travelers
4. **Set budget**: Maximum price per person (default: €100)
5. **Choose trip duration**: Select between 4-6 days
6. **Search**: Click "Search Cheap Flights" to find available options

## Features

### Smart Filtering
- Automatically filters results by your price limit
- Ensures trip duration matches your requirements
- Sorts results by price (cheapest first)

### Detailed Results
- Flight duration and trip duration
- Airline information
- Number of stops
- Available seats
- Region and country badges
- Total price calculation

### User-Friendly Interface
- Responsive design for all devices
- Clear visual indicators for regions
- Easy-to-read flight cards
- Summary statistics

## Technical Details

- **Frontend**: React 18 with functional components and hooks
- **Styling**: CSS with modern design patterns
- **Icons**: Lucide React for consistent iconography
- **Date handling**: date-fns for date formatting
- **Mock data**: Realistic flight data simulation

## Future Enhancements

- Integration with real flight APIs (Skyscanner, Kiwi.com)
- Price alerts and notifications
- Advanced filtering options
- Flight comparison tools
- Booking integration
- Mobile app version

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the MIT License.
