[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue.svg)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-18.3.1-blue.svg)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.4.2-purple.svg)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC.svg)](https://tailwindcss.com/)

# Jobify - Professional Job Portal

Jobify is a modern, feature-rich job portal built with React and TypeScript. It connects talented professionals with top companies worldwide, offering a seamless job search and application experience.

![Jobify Homepage](https://images.pexels.com/photos/3183150/pexels-photo-3183150.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

## ✨ Features

- 🔐 **Secure Authentication** - User registration and login with JWT
- 🔍 **Advanced Job Search** - Filter by location, job type, experience level, and salary range
- 📱 **Responsive Design** - Optimized for all devices and screen sizes
- 💼 **Job Management** - Save favorite jobs and track applications
- 📊 **User Dashboard** - View application history and job recommendations
- 🎯 **Smart Filtering** - Find the perfect job with powerful search filters
- 📝 **Rich Job Listings** - Detailed job descriptions with company information
- 🌐 **SEO Optimized** - Better visibility in search engines

## 🛠️ Tech Stack

- **Frontend Framework:** React 18.3
- **Language:** TypeScript 5.5
- **Build Tool:** Vite 5.4
- **Styling:** Tailwind CSS 3.4
- **Form Handling:** React Hook Form
- **Routing:** React Router 6
- **Icons:** Lucide React
- **Date Handling:** date-fns
- **Utility Libraries:** clsx, tailwind-merge

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0 or higher
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/amitkumarraikwar/jobify.git
cd jobify
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

## 🔧 Configuration

The project uses environment variables for configuration. Create a `.env` file in the root directory:

```env
VITE_API_URL=your_api_url
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 📖 Usage Examples

### Job Search with Filters

```typescript
const JobSearch: React.FC = () => {
  const handleFilter = (filters: any) => {
    // Filter implementation
  };

  return (
    <JobFilters onFilter={handleFilter} />
  );
};
```

### Authentication

```typescript
const login = async (email: string, password: string) => {
  // Authentication logic
};
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Code Style

- Follow the existing code style
- Use TypeScript for type safety
- Write meaningful commit messages
- Add tests for new features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com) for the utility-first CSS framework
- [Lucide Icons](https://lucide.dev) for the beautiful icons
- [React Hook Form](https://react-hook-form.com) for form handling
- [Vite](https://vitejs.dev) for the build tooling

## 📞 Contact

Project Link: [https://github.com/amitkumarraikwar/jobify](https://github.com/amitkumarraikwar/jobify)

## 📸 Screenshots

### Homepage
![Homepage](https://images.pexels.com/photos/3183183/pexels-photo-3183183.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

### Job Listings
![Job Listings](https://images.pexels.com/photos/3183190/pexels-photo-3183190.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

### User Dashboard
![User Dashboard](https://images.pexels.com/photos/3183153/pexels-photo-3183153.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)