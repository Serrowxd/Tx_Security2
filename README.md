# Texas Level II Security Officer Quiz

A comprehensive web application designed to help individuals prepare for the Texas Noncommissioned Security Officer (Unarmed) certification exam. Built with Next.js, React, and TypeScript, this application provides both exam simulation and practice modes with detailed feedback and performance tracking.

## Features

- **Exam Mode**: Simulate the real Texas Level II exam with 40 questions, 30-minute time limit, and 75% passing requirement
- **Practice Mode**: Learn with immediate feedback, detailed explanations, and no time pressure
- **Comprehensive Question Bank**: 100+ questions covering all exam categories
- **Performance Analytics**: Detailed breakdown of performance by category
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Certificate Generation**: Downloadable certificates for passing exam scores
- **Category Tracking**: Monitor performance across different security topics

## Exam Categories Covered

- **Roles and Responsibilities**: Understanding the duties and limitations of security officers
- **Texas Laws and Regulations**: Knowledge of Texas Occupations Code Chapter 1702
- **Security Communications**: Effective reporting and communication techniques
- **Emergency Response**: Proper procedures for medical, fire, and security emergencies
- **Ethical Standards**: Professional conduct and confidentiality requirements

## Getting Started

### Prerequisites

- Node.js 18+
- npm, yarn, or pnpm

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd Tx_Security2
```

2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
Tx_Security2/
├── app/                    # Next.js app directory
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx          # Main page component
├── components/            # React components
│   ├── ui/               # UI components (buttons, cards, etc.)
│   ├── quiz.tsx          # Main quiz component
│   └── quiz-results.tsx  # Results display component
├── data/                 # Application data
│   └── questions.json    # Question bank
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
└── public/               # Static assets
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## Technologies Used

- **Next.js 15** - React framework with App Router
- **React 19** - UI library
- **TypeScript** - Type safety and development experience
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Accessible UI primitives
- **Lucide React** - Beautiful icons
- **Recharts** - Data visualization for performance analytics

## Quiz Modes

### Exam Mode

- 40 randomly selected questions
- 30-minute time limit
- 75% passing score required (30/40 correct)
- Certificate generation for passing scores
- Simulates real exam conditions

### Practice Mode

- 40 randomly selected questions
- No time limit
- Immediate feedback after each question
- Detailed explanations for all answers
- Performance tracking by category

## Features Overview

### Interactive Quiz Interface

- Progress tracking with visual indicators
- Timer display for exam mode
- Question navigation with previous/next buttons
- Category labels for each question
- Responsive design for all screen sizes

### Results and Analytics

- Overall score and percentage
- Pass/fail determination
- Category-by-category performance breakdown
- Time analysis for exam mode
- Detailed answer review with explanations

### User Experience

- Clean, professional interface
- Intuitive navigation
- Mobile-friendly responsive design
- Accessibility features
- Smooth transitions and animations

## Customization

### Adding Questions

Questions can be added or modified in `data/questions.json`. Each question should follow this format:

```json
{
  "id": 1,
  "category": "Category Name",
  "question": "Question text?",
  "options": ["Option A", "Option B", "Option C", "Option D"],
  "correct": 1,
  "explanation": "Detailed explanation of the correct answer"
}
```

### Styling

The application uses Tailwind CSS for styling. Custom styles can be added to:

- `app/globals.css` for global styles
- Component-specific CSS modules
- Tailwind configuration in `tailwind.config.ts`

### Configuration

- Timer duration can be modified in the quiz component
- Passing score threshold can be adjusted
- Question count can be changed for different exam formats

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically on every push

### Other Platforms

The application can be deployed to any platform that supports Next.js:

- Netlify
- Railway
- DigitalOcean App Platform
- AWS Amplify

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the MIT License.

## Disclaimer

This application is designed to help prepare for the Texas Level II Security Officer certification exam. While the content is based on Texas Department of Public Safety requirements, it is not officially endorsed by the DPS. Users should verify all information with official sources and consult the latest Texas Occupations Code Chapter 1702 for current requirements.

## Support

For questions or support, please open an issue on the GitHub repository or contact the development team.
