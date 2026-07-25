# FoodHub - Food Ordering Application

A premium food ordering web application built using React, Redux Toolkit, and Tailwind CSS, integrating real-time data from the Swiggy API.

## Live Demo

Check out the live demo of the application [here](https://food-hub-hazel-ten.vercel.app/).

## Author

- **Aashish**
  - **GitHub:** [DevEnPassant](https://github.com/DevEnPassant)
  - **LinkedIn:** [Aashish Kumar](https://www.linkedin.com/in/aashish-kumar-125071326/)

## Getting Started

Follow these steps to set up and run FoodHub locally:

### 1. Clone the repository
```bash
git clone https://github.com/DevEnPassant/FoodHub.git
cd FoodHub
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the development server
```bash
npm start
# or
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser to view the application.

### 4. Build for production
```bash
npm run build
```

### 5. Other Scripts
- **Lint the code:** `npm run lint`
- **Preview the production build:** `npm run preview`

## Key Features

- **Live Data Fetching:** Real-time updates and data fetching from Swiggy API to display restaurants, current menu items, and prices.
- **Custom Hook:** Created a custom hook to check if the user is online or offline, enhancing reliability.
- **Cart Functionality:** Seamless addition and removal of items for a smooth ordering experience.
- **Infinite Scrolling:** Continuous loading of restaurant listings as the user scrolls through the app.
- **Promoted Labels:** Highlighted recommended restaurants using Higher Order Components.
- **Shimmer Effect:** Enhanced user experience with loading placeholders during data fetching.
- **Performance Optimization:** Achieved high performance with a Google Lighthouse rating of 99, leveraging Vite as a bundler and optimizing code.
- **Responsive Design:** Fully responsive design ensuring a seamless experience across devices.
- **Light Mode/Dark Mode:** User-friendly interface that adapts to user preferences.

## Usage

- Browse through restaurants and their menus.
- Add items to the cart and proceed to checkout.
- Explore recommended restaurants and new arrivals.

## Technologies Used

- **React**
- **Redux Toolkit**
- **Tailwind CSS**
- **Swiggy API**
