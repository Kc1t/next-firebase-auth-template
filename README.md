
# Next.js + Firebase Auth Template

This template integrates Next.js with Firebase Authentication, providing a robust foundation for web applications requiring secure user authentication.

## Features

- **Next.js 13**: Utilizes the latest features of Next.js for optimal performance.
- **Firebase Authentication**: Implements secure user authentication using Firebase.
- **TypeScript**: Ensures type safety and improved developer experience.
- **Tailwind CSS**: Provides utility-first CSS for rapid UI development.
- **ESLint & Prettier**: Maintains code quality and consistency.

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- Firebase Project

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Kc1t/next-firebase-auth-template.git
   cd next-firebase-auth-template
   ```

2. **Install dependencies**:

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables**:

   Create a `.env.local` file in the root directory and add your Firebase configuration:

   ```env
   NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
   ```

4. **Run the development server**:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the application.

## Project Structure

```
├── pages/                 # Next.js pages
│   └── api/               # API routes
│       └── auth/          # Authentication endpoints
├── public/                # Public assets
├── src/
│   └── app/               # Application components and logic
├── .env.local             # Environment variables
├── next.config.mjs        # Next.js configuration
├── tailwind.config.ts     # Tailwind CSS configuration
├── tsconfig.json          # TypeScript configuration
```

## License

This project is licensed under the MIT License.
