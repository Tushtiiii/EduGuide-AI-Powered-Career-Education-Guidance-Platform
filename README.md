# EduGuide - Digital Guidance Platform for Students
https://edu-guide-ai-powered-caree-git-b6b624-tushtee-kothares-projects.vercel.app/

A comprehensive one-stop personalized career and education advisor designed to help students make informed decisions about their educational journey and career paths.

## 🎯 Project Overview

EduGuide is a modern web application that provides personalized career guidance, college recommendations, and educational pathway mapping for students. Built with Next.js, TypeScript, and Tailwind CSS, it offers an intuitive and responsive user experience.

## ✨ Key Features

### 🧠 Aptitude & Interest-Based Course Suggestion
- Interactive personality and aptitude quizzes
- AI-driven analysis of student strengths and interests
- Personalized stream recommendations (Arts, Science, Commerce, Vocational)
- Career path comparison and visualization

### 🗺️ Course-to-Career Path Mapping
- Comprehensive visual charts showing career progression
- Detailed information about degree programs (B.A., B.Sc., B.Com., BBA, etc.)
- Industry sector mapping and job market insights
- Government exams, private job opportunities, and entrepreneurial options
- Higher education pathway guidance

### 🏫 Nearby Government Colleges Directory
- Location-based college search functionality
- Comprehensive college information including:
  - Available degree programs and specializations
  - Cut-off marks and eligibility criteria
  - Medium of instruction options
  - Campus facilities (hostel, labs, library, internet)
  - Fee structures for different categories
  - Contact information and website links

### 📅 Timeline Tracker
- Smart notification system for important dates
- Admission deadlines and application windows
- Scholarship application reminders
- College entrance test schedules
- Counseling session notifications

### 🤖 AI-Powered Personalization
- User profile creation and management
- Intelligent recommendation engine
- Personalized course suggestions based on user data
- Nearby college recommendations
- Career path alignment with aptitude results
- Customized study materials and resources

## 🛠️ Technology Stack

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS 4
- **Database**: SQLite with Prisma ORM
- **UI Components**: Radix UI primitives
- **Charts**: Recharts
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Forms**: React Hook Form with Zod validation

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd digital-guidance-platform
```

2. Install dependencies:
```bash
npm install
```

3. Set up the database:
```bash
npx prisma generate
npx prisma db push
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📱 Features Walkthrough

### Homepage
- Modern, responsive landing page
- Feature overview cards
- Quick access to main functionalities
- Statistics and success metrics

### Aptitude Quiz
- 8-question comprehensive assessment
- Multiple categories: logical, creative, analytical, social, practical
- Real-time progress tracking
- Detailed results with stream recommendations
- Career suggestions based on quiz results

### Colleges Directory
- Advanced search and filtering
- State-wise and type-wise filtering
- Comprehensive college information cards
- Rating and facility information
- Quick action buttons for saving and navigation

### Career Explorer
- Interactive career path visualization
- Salary progression charts
- Skills and industry mapping
- Educational pathway requirements
- Certification recommendations

## 🗂️ Project Structure

```
src/
├── app/                    # Next.js App Router pages
│   ├── careers/           # Career exploration page
│   ├── colleges/          # College directory page
│   ├── quiz/              # Aptitude quiz page
│   └── page.tsx           # Homepage
├── components/
│   ├── features/          # Feature-specific components
│   └── ui/                # Reusable UI components
├── lib/
│   ├── prisma.ts          # Database client
│   └── utils.ts           # Utility functions
├── types/
│   └── index.ts           # TypeScript type definitions
prisma/
├── schema.prisma          # Database schema
└── dev.db                 # SQLite database file
```

## 🎨 Database Schema

The application uses a comprehensive database schema with the following models:
- **Users**: Student profiles and preferences
- **QuizResults**: Aptitude test results and recommendations
- **Colleges**: Government college information
- **Careers**: Career path details
- **Timeline**: Important dates and notifications
- **Recommendations**: AI-generated suggestions
- **StudyMaterials**: Educational resources
- **Scholarships**: Financial aid opportunities
- **Exams**: Entrance and competitive exam information

## 🎯 Implementation Strategy

### Phase 1: Core Platform Development ✅
- ✅ Basic application structure
- ✅ Homepage with feature overview
- ✅ Aptitude quiz functionality
- ✅ College directory with search
- ✅ Career path visualization
- ✅ Database schema and models

### Phase 2: Advanced Features (Planned)
- User authentication and profiles
- AI recommendation engine
- Timeline tracking system
- Study materials integration
- Scholarship information
- Mobile app development

### Phase 3: Collaboration & Outreach (Planned)
- Government education department integration
- School and teacher collaboration tools
- NGO partnership features
- Analytics and reporting dashboard

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE] file for details.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- UI components from [Radix UI](https://radix-ui.com/)
- Icons from [Lucide](https://lucide.dev/)
- Charts powered by [Recharts](https://recharts.org/)
- Animations by [Framer Motion](https://framer.com/motion/)

## 📞 Support

For support, email tushteekothare@gmail.com or join our Slack channel.

---

Made with ❤️ for students seeking educational guidance
