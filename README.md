# EnviroLink - Waste Management Platform

A comprehensive full-stack waste management application connecting users, companies, drivers, and admins for efficient waste recycling and management.

## Project Overview

EnviroLink is a platform that facilitates:
- **Users**: Can sell or list waste materials
- **Companies**: Can purchase waste materials
- **Drivers**: Can manage waste collection and delivery
- **Admins**: Can monitor and manage the entire platform

## Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Backend
- Node.js
- Express.js
- CORS enabled

### Database
- Oracle Database
- Connection pooling for efficient queries

## Project Structure

```
envirolonkFinal/
├── backend/                 # Express server & API routes
│   ├── database/           # Database connection management
│   └── index.js            # Main server file
├── user/                   # User authentication & features
│   ├── html/              # User pages
│   ├── css/               # User styles
│   └── script/            # User logic
├── company/               # Company authentication & features
│   ├── html/
│   ├── css/
│   └── script/
├── driver/                # Driver authentication & features
│   ├── html/
│   ├── css/
│   └── script/
├── admin/                 # Admin panel
│   ├── html/
│   ├── css/
│   └── script/
└── global/               # Shared assets & styles
    └── Interface/        # Landing page
```

## Key Features

- ✅ Multi-role authentication (User, Company, Driver, Admin)
- ✅ Waste listing and purchase system
- ✅ Real-time notifications
- ✅ Waste history tracking
- ✅ Admin dashboard
- ✅ CORS enabled for cross-origin requests

## Getting Started

### Prerequisites
- Node.js and npm
- Oracle Database
- Modern web browser

### Installation

1. Clone the repository
```bash
git clone https://github.com/KawsarArafat/EnviroLinkFinal.git
cd EnviroLinkFinal
```

2. Install backend dependencies
```bash
cd backend
npm install
```

3. Set up environment variables
- Create `.env` file in backend directory
- Configure database connection details

4. Start the server
```bash
npm start
```

## API Routes

### Admin Routes
- `POST /api/admin-login` - Admin login

### User Routes
- `POST /api/user-login` - User login
- `GET /api/user/:id` - Get user profile
- `POST /api/sell-waste` - List waste for sale

### Company Routes
- `POST /api/company-login` - Company login
- `GET /api/available-waste` - View available waste

### Driver Routes
- `POST /api/driver-login` - Driver login
- `GET /api/deliveries` - Get assigned deliveries

## Contributing

Feel free to fork and submit pull requests for any improvements.

## License

This project is open source and available under the MIT License.

## Contact

For more information, visit the [GitHub repository](https://github.com/KawsarArafat/EnviroLinkFinal)
