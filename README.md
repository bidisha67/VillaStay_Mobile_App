# VillaStay

VillaStay is a cross platform Flutter mobile application for villa booking in Nepal. Guests can search villas, check live availability, book stays, make payments, and leave ratings and reviews. Villa owners can manage their properties, calendars, and booking requests from the same app.

Built for **ST6002CEM: Mobile Application Development** at Softwarica College of IT and E-Commerce, Coventry University.

## Why VillaStay?

Villa booking in Nepal is still mostly done through phone calls, social media messages, and brokers. That creates real problems for both sides:

| For guests | For owners |
|------------|------------|
| Hard to compare villas and prices | Overlapping enquiries from many guests |
| No clear live availability | Risk of double booking the same dates |
| Weak or missing reviews | Payments tracked by hand |
| Slow replies and last minute cancellations | No single record of confirmed stays |

**VillaStay exists to fix this.**

It brings villa search, availability calendars, booking with payment, and guest reviews into one mobile app, so guests can book with confidence and owners can manage stays without confusion.

### Why a mobile app?
Most people already search and book travel from their phone. A Flutter mobile app fits how guests and owners actually behave day to day.

### Why Flutter?
One codebase can target Android now, with iOS possible later, which suits a module timeframe without building two separate native apps.

### Why MVVM?
MVVM keeps screens (View), logic (ViewModel), and data (Model) separate. That makes booking, availability, and review flows easier to update, test, and maintain as the app grows.

### Why reviews and payments in the same app?
Search alone is not enough. Guests need trusted reviews before booking, and owners need confirmed payments after booking. Putting both in one place closes the gap left by informal messaging.

## Features

### Guest
- Register and log in securely
- Search and filter villas by location, dates, guests, and price
- View villa details, photos, amenities, ratings, and reviews
- Check availability on a calendar
- Book a stay and pay through a sandbox payment gateway
- Track bookings in My Bookings
- Submit ratings and reviews after a completed stay
- Manage profile and settings

### Owner
- Owner dashboard for bookings, earnings, and upcoming arrivals
- Add, edit, and manage villa listings
- Confirm or decline booking requests
- Block unavailable dates
- Monitor guest reviews

### Stretch goals
- Push notifications for booking updates
- Map view of nearby villas

## Architecture

VillaStay follows the **MVVM** pattern:

| Layer | Responsibility |
|-------|----------------|
| **Model** | Data and repositories for users, villas, bookings, payments, and reviews |
| **View** | Flutter screens and widgets for Guest and Owner flows |
| **ViewModel** | UI state and logic using Provider and ChangeNotifier |

## Tech stack

- Flutter / Dart
- Provider (state management)
- REST API / Firebase (as configured)
- Figma (UI prototypes)
- Git and GitHub (version control)

## Getting started

```bash
git clone https://github.com/YOUR_USERNAME/VillaStay.git
cd VillaStay
flutter pub get
flutter run
```

## Scope notes

**Included**
- Guest and Owner flows
- Sandbox payment gateway
- Sample / demo villa data

**Not included**
- In app chat
- Integration with Airbnb or Booking.com
- Full offline booking

## Author

**Dawa Dolmo Tamang**  
Student ID: 240687  
Softwarica College of IT and E-Commerce  
Coventry University
