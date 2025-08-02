# Ecron Technologies Website

This project is a modern website for Ecron Technologies, a software training institute in Tamil Nadu, India.

## 🚀 Features

- **Modern Website Features**
  - Responsive design for all devices
  - Course catalog and detailed course pages
  - Contact forms and demo scheduling
  - Newsletter subscription
  - Event registration system
  - Professional UI/UX design

- **Technical Features**
  - React with TypeScript
  - Express.js backend
  - Form validation and error handling
  - Modern CSS with Tailwind
  - Component-based architecture

## 📋 Prerequisites

- **Node.js**: Version 16 or higher
- **Database**: Configure your preferred database service
- **Environment Variables**: Set up your environment configuration

## 🔧 Setup Instructions

### 1. Install Dependencies

```bash
npm install
```

### 2. Environment Configuration

Create a `.env` file in your project root:

```env
# Database Configuration (replace with your preferred database)
DATABASE_URL=postgresql://localhost:5432/your_database

# Add your preferred authentication and database service variables here
# TODO: Configure new data source
```

### 3. Start Development Server

```bash
npm run dev
```

### 4. Build for Production

```bash
npm run build
npm start
```

## 🔧 Data Integration

This project currently uses placeholder functions for data operations. You'll need to integrate with your preferred database and authentication service:

### Files to Update:
- `client/src/lib/supabaseClient.ts` - Replace with your data service API calls
- `client/src/lib/auth.ts` - Replace with your authentication service
- `server/routes.ts` - Connect to your database
- `client/src/components/AuthProvider.tsx` - Update authentication logic

### Forms That Need Data Integration:
1. Contact form (`/api/contact`)
2. Course applications (`/api/course-applications`)
3. Demo scheduling (`/api/demo-applications`)
4. Newsletter subscription (`/api/newsletter/subscribe`)
5. Event registration (`/api/event-registrations`)

## 🎨 Features

- **Responsive Design**: Works on all devices
- **Course Catalog**: Detailed course information and applications
- **Contact Forms**: Multiple ways for users to get in touch
- **Event Registration**: Campus to Cloud event registration
- **Newsletter**: Email subscription system
- **Modern UI**: Clean, professional design with animations

## 🚀 Deployment

The application can be deployed to any platform that supports Node.js applications. Make sure to:

1. Set up your environment variables
2. Configure your database connection
3. Set up your authentication service
4. Build the application for production

## 📞 Support

For questions about Ecron Technologies courses:
- Phone: +91 8438829844
- Email: ecrontechnologies@gmail.com
- Address: Door No: 55, Railway Station Road, Alandur, Chennai - 600 016