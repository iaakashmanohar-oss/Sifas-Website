# SIFAS Productions Website - Product Requirements Document

## Original Problem Statement
Build a website for SIFAS Productions, a performing arts production company. The website should have:
- Header with navigation: Events, About Us, Our Team, Our Collaborators
- Landing page with company information
- Vibrant and artistic design
- Black and maroon color scheme

## Company Overview
SIFAS Productions Limited (SPL) is the performing and production wing of SIFAS, dedicated to creating original, world-class productions across dance, music, and theatre. SPL serves as a platform to nurture and showcase artistic talent and presents cross-cultural and multi-ethnic art forms on national, regional, and international stages, with a strong focus on racial harmony and cultural exchange.

## User Personas
1. **Audience Members**: Individuals interested in attending performing arts events
2. **Artists/Performers**: Professionals seeking collaboration opportunities
3. **Partners/Sponsors**: Organizations interested in cultural partnerships
4. **Media/Press**: Journalists covering cultural events

## Core Requirements (Static)

### Design Requirements
- Vibrant and artistic design style
- Black background with maroon/red accent colors
- Responsive layout for all devices
- Smooth animations and transitions
- Professional typography (Inter font)
- High-quality imagery showcasing performing arts

### Functional Requirements
- Fixed header with smooth scroll navigation
- Responsive mobile menu
- Smooth scrolling to sections
- Interactive cards with hover effects
- Call-to-action buttons throughout
- Social media links in footer

## What's Been Implemented (December 7, 2025)

### Frontend Components (Mock Data)
1. **Header Component** (`/app/frontend/src/components/Header.jsx`)
   - Fixed navigation bar with transparency effect on scroll
   - Navigation links: Events, About Us, Our Team, Our Collaborators
   - "Get Tickets" CTA button
   - Mobile-responsive hamburger menu

2. **Hero Section** (`/app/frontend/src/components/Hero.jsx`)
   - Dramatic background with theatrical stage image
   - Gradient text headlines
   - Two CTA buttons (Explore Events, Learn More)
   - Statistics display (500+ performances, 50+ countries, 100k+ audience)
   - Animated scroll indicator

3. **About Us Section** (`/app/frontend/src/components/About.jsx`)
   - Company description with image
   - Mission, Vision, Values in grid layout
   - Additional imagery showcasing dance and cultural heritage
   - Gradient card designs with icons

4. **Events Section** (`/app/frontend/src/components/Events.jsx`)
   - Three upcoming events displayed
   - Event cards with images, dates, venues, descriptions
   - "Get Tickets" functionality (mock)
   - "View All Events" CTA

5. **Team Section** (`/app/frontend/src/components/Team.jsx`)
   - Four team members with professional photos
   - Hover effects revealing social links (LinkedIn, Email)
   - Role and bio information
   - "Join Our Creative Team" CTA section

6. **Collaborators Section** (`/app/frontend/src/components/Collaborators.jsx`)
   - Four partner organizations
   - Logo displays with grayscale-to-color hover effect
   - "Learn More" links for each collaborator
   - "Become a Partner" CTA section

7. **Footer Component** (`/app/frontend/src/components/Footer.jsx`)
   - Brand information
   - Quick links navigation
   - Contact information (email, phone, address)
   - Social media links (Facebook, Instagram, Twitter, YouTube)
   - Copyright and legal links

### Mock Data (`/app/frontend/src/mock.js`)
- 3 upcoming events with details
- 4 team members with roles and bios
- 4 collaborator organizations
- Company information and mission/vision statements

### Styling
- Updated `App.css` with custom animations and scrollbar styling
- Updated `index.css` with Inter font and dark theme
- All components use Tailwind CSS with custom color scheme
- Gradient colors: red-600, red-700, red-800, red-900, amber-400, amber-500

## Prioritized Backlog

### P0 Features (Essential - Not Yet Implemented)
- Backend API development
- Database integration for events, team, collaborators
- Contact form functionality
- Newsletter subscription
- Ticket booking system integration

### P1 Features (Important - Future Enhancement)
- Image gallery for past productions
- Video showcase section
- Event calendar with filtering
- Blog/news section
- Multi-language support
- Search functionality

### P2 Features (Nice to Have)
- User authentication for ticket holders
- Online payment integration
- Membership program
- Mobile app
- Live streaming integration
- Performance reviews and ratings

## Next Action Items
1. **Backend Development**: Create FastAPI endpoints for:
   - Events management (CRUD operations)
   - Team members management
   - Collaborators management
   - Contact form submissions
   - Newsletter subscriptions

2. **Database Schema**: Design MongoDB collections for:
   - Events
   - Team members
   - Collaborators
   - Contact submissions
   - Newsletter subscribers

3. **Frontend-Backend Integration**: 
   - Replace mock data with API calls
   - Implement proper error handling
   - Add loading states
   - Form validation

4. **Contact Form**: Add a contact section for inquiries

5. **Testing**: End-to-end testing of all features

## Technical Stack
- **Frontend**: React, Tailwind CSS, Shadcn UI components
- **Backend**: FastAPI, Python (ready for implementation)
- **Database**: MongoDB (ready for implementation)
- **Deployment**: Supervisor-managed services
