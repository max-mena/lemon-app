# Little Lemon — Table Reservation Feature

A React application implementing the table booking feature for Little Lemon, a fictional Mediterranean restaurant. Built as the capstone project for the **Meta Front-End Developer Certificate**.

## Features

- Table reservation form with date, time, party size, and occasion fields
- Client-side form validation with accessible error states
- Booking confirmation modal
- Responsive layout with dedicated pages: Home, Menu, About, and Reservations
- Unit tests for the booking form component

## Tech Stack

- React 18 (JSX)
- Create React App
- CSS Modules
- Jest + React Testing Library

## Getting Started

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Running Tests

```bash
npm test
```

## Project Structure

```
src/
├── components/
│   ├── BookingForm.jsx      # Reservation form with validation
│   ├── BookingForm.test.jsx # Unit tests
│   ├── Modal.jsx            # Confirmation modal
│   ├── Nav.jsx              # Navigation bar
│   ├── Header.jsx
│   ├── Footer.jsx
│   ├── Main.jsx             # Home page
│   ├── MenuMain.jsx
│   ├── AboutMain.jsx
│   ├── ReserveMain.jsx
│   └── TestimonialMain.jsx
└── App.jsx
```
