# Student Hustle 🎓

A platform designed to help students showcase their skills, services, and small businesses in one place.

## 🚀 Features

- **Student Profiles**: Create and manage your student entrepreneur profile
- **Service Listings**: Showcase your services with descriptions, pricing, and images
- **Search & Filter**: Easy discovery of services by category and location
- **Ratings & Reviews**: Build trust with verified reviews from other students
- **Authentication**: Secure sign-up with Google OAuth and email/password
- **Admin Dashboard**: Manage your business, services, and reviews
- **Featured Listings**: Get featured to increase visibility

## 📋 Supported Categories

- 🎓 Tutoring
- 🎨 Graphic Design  
- 📸 Photography
- 💇 Hair & Beauty
- 💅 Nail Services
- 🍰 Baking
- 👗 Fashion
- 💻 Tech Services
- 🎉 Event Services
- ➕ Other

## 🛠 Tech Stack

### Frontend
- **React 18** - UI library
- **Next.js 14** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling

### Backend
- **Node.js** - Runtime
- **Next.js API Routes** - Backend
- **Next-Auth** - Authentication

### Database
- **PostgreSQL** - Database
- **Prisma ORM** - ORM

## 📁 Project Structure

```
app/              # Next.js app directory
components/       # UI and layout components
lib/              # Utilities and configuration
hooks/            # Custom React hooks
services/         # API services
types/            # TypeScript types
prisma/           # Database schema
public/           # Static assets
```

## 🚀 Quick Start

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment: `cp .env.example .env`
4. Set up database: `npx prisma db push`
5. Start dev server: `npm run dev`

Visit `http://localhost:3000`

## 🔐 Environment Variables

```env
DATABASE_URL="postgresql://..."
NEXTAUTH_SECRET="..."
NEXTAUTH_URL="http://localhost:3000"
GOOGLE_CLIENT_ID="..."
GOOGLE_CLIENT_SECRET="..."
```

## 📚 API Documentation

### Businesses
- `GET /api/businesses` - Get all businesses
- `POST /api/businesses` - Create business (auth required)
- `GET /api/businesses/:id` - Get specific business

### Services
- `GET /api/services` - Get all services
- `POST /api/services` - Create service (auth required)
- `GET /api/services?businessId=:id` - Get services for business

### Reviews
- `POST /api/reviews` - Create review (auth required)
- `GET /api/reviews?serviceId=:id` - Get reviews for service

## 🎯 Roadmap

- ✅ Project setup
- ✅ Database schema
- ✅ Authentication
- ✅ Landing page
- ⏳ Business management
- ⏳ Service listings
- ⏳ Search & filter
- ⏳ Admin dashboard

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

See CONTRIBUTING.md for details.

## 📝 License

MIT License - see LICENSE file

## 📧 Contact

For questions, please open an issue.

Built with ❤️ for student entrepreneurs.
