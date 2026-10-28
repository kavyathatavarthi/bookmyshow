# BookMyShow Clone

A responsive movie ticket booking web interface exported from Figma and customized with clean HTML5 & CSS3.

## 🚀 Features

- **Home Page**: Movie banners, featured releases, and quick navigation.
- **Movie Selection & Schedules**: Browse current releases, cinema listings, showtimes, and dates.
- **Interactive Seat Selection**: Visual theater seating layout with categorized tiers and pricing.
- **Booking Summary & Checkout**: Order breakdown with convenience fees and tax calculations.
- **E-Tickets & QR Code**: Confirmation screens with digital pass and QR code display.
- **User Management & Policies**: Login, OTP verification, booking history, and cancellation policy pages.

## 📁 Project Structure

```text
├── home-page.html                 # Main landing page
├── newshowing.html                # Current movie showings
├── time-and-date-selection.html   # Showtime and date picker
├── seat-selection.html            # Theater seat selection
├── summary.html                   # Booking summary & checkout
├── proceed-booking.html           # Payment / proceed flow
├── sucessbooking.html             # Booking confirmation
├── qr.html                        # Digital ticket QR code
├── mybookings.html                # User's bookings history
├── cancellationpolicies.html      # Cancellation terms & conditions
├── cancelsucess.html              # Cancellation success screen
├── login-page.html                # User authentication
├── verification.html              # OTP verification
├── filterslanding.html            # Search & filters
├── desktop.css                    # Desktop navigation & layout styles
├── styles.css                     # Primary styles
└── images/                        # Movie posters, icons, and illustrations
```

## 💻 How to Run Locally

### Option 1: Python HTTP Server (Recommended)
```bash
python -m http.server 8000
```
Open [http://localhost:8000/home-page.html](http://localhost:8000/home-page.html) in your browser.

### Option 2: Direct Open
Double-click `home-page.html` or open it with any web browser.

### Option 3: Node.js (npx serve)
```bash
npx serve .
```
