# Chrona

Chrona is a full-stack scheduling and calendar management platform that streamlines meeting coordination through automated booking, availability management, recurring event scheduling, and calendar synchronization. Built with modern web technologies, Chrona enables individuals and teams to efficiently manage schedules while ensuring secure collaboration and seamless video conferencing integration.

---

## Features

- Conflict-aware meeting scheduling
- Multi-user availability management
- Timezone-aware booking workflows
- Recurring event scheduling
- Team and organizational scheduling
- Calendar synchronization
- Secure authentication and access control
- Audit logging and activity tracking
- Daily.co video conferencing integration
- Real-time scheduling management

---

## Built With

- Next.js
- React.js
- TypeScript
- tRPC
- Tailwind CSS
- Prisma ORM
- Daily.co

---

## Tech Stack

### Frontend
- Next.js
- React.js
- TypeScript
- Tailwind CSS

### Backend
- tRPC

### Database & ORM
- Prisma ORM

### Integrations
- Daily.co

### Development Tools
- Git
- GitHub
- VS Code

---

## System Architecture

Chrona follows a modern full-stack architecture:

- **Next.js** powers the frontend and scheduling workflows.
- **React.js** provides reusable UI components and state-driven interactions.
- **tRPC** enables end-to-end type-safe communication between frontend and backend.
- **Prisma ORM** manages database schema and data access.
- **Daily.co** provides integrated video conferencing capabilities.
- **Role-based access controls and audit logging** ensure secure and traceable scheduling operations.

---

## Technical Highlights

### Intelligent Scheduling
Implemented conflict-aware scheduling workflows supporting participant availability management, timezone-aware booking, and recurring event scheduling.

### Access Control
Designed secure scheduling workflows with role-based permissions to support team collaboration and organizational scheduling.

### Video Conferencing Integration
Integrated Daily.co to enable seamless meeting creation and video conferencing directly within scheduling workflows.

### Auditability
Implemented activity tracking and audit logging for event creation, updates, cancellations, and user actions.

### Scalable Data Management
Utilized Prisma ORM for efficient management of scheduling entities, user data, event metadata, and organizational workflows.

---

## Development Setup

### Prerequisites

- Node.js (v18 or above)
- npm or yarn

### Installation

Clone the repository:

```bash
git clone https://github.com/NIDHI-cy/CHRONA.git
cd CHRONA
```

Install dependencies:

```bash
npm install
```

or

```bash
yarn
```

Configure environment variables:

```env
DATABASE_URL=
NEXTAUTH_SECRET=
NEXTAUTH_URL=
```

Run database migrations:

```bash
npx prisma migrate dev
```

Start the development server:

```bash
npm run dev
```

or

```bash
yarn dev
```

Open your browser:

```text
http://localhost:3000
```

---

## Deployment

### Production Build

```bash
npm run build
```

or

```bash
yarn build
```

### Start Production Server

```bash
npm start
```

or

```bash
yarn start
```

### Deploy on Vercel

```bash
vercel deploy
```

### Docker Deployment

Build Docker image:

```bash
docker build -t chrona .
```

Run Docker container:

```bash
docker run -p 3000:3000 chrona
```

---

## Challenges Solved

- Multi-user scheduling conflict resolution
- Timezone normalization across distributed users
- Recurring event lifecycle management
- Team-based scheduling workflows
- Secure access management and activity tracking
- Video conferencing integration within scheduling workflows

---

## Future Enhancements

- AI-powered meeting recommendations
- Smart scheduling assistant
- Automated reminders and notifications
- Advanced scheduling analytics
- Team productivity insights

---

## Author

**Nidhi Rayankula**
