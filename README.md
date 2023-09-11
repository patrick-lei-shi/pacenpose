# PaceNPose 🛍️

A modern, responsive e-commerce website dedicated to offering curated selections of premium clothing and footwear.

## Features

- Curated selections of clothing and footwear
- User authentication (via email and Google account)
- Integrated payment gateway with Stripe
- Redux and Redux-saga for state management
- Responsive design
- Service workers for offline capabilities

## Tech Stack

- React
- Redux
- Redux-saga
- React-router
- Firebase for authentication and possibly database
- Stripe for payments
- Styled-components for styling
- Typescript
- Workbox for service worker-related functionality

## Getting Started

### Prerequisites

- Node.js v14+
- NPM v6+

### Installation

1. Clone the repository:

```bash
git clone https://github.com/patrick-lei-shi/pacenpose.git
```

2. Navigate to the project directory:

```bash
cd pacenpose
```

3. Install the dependencies:

```bash
npm install
```

4. Create a `.env` file in the root directory and fill in your environment variables (Firebase, Stripe keys, etc.)

5. Start the development server:

```bash
npm start
```

The app should be running on `http://localhost:3000`.

## Testing

Run the tests using:

```bash
npm test
```

## Building for Production

To create a production build, run:

```bash
npm run build
```

## Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

ISC
