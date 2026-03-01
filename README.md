# DevCampus

> A free, community-driven online platform for learning tech & programming — built for developers, by developers.

---

## About DevCampus

DevCampus is an open, free online learning platform focused exclusively on tech and programming. Unlike generic platforms like Udemy or Coursera, DevCampus is built around **structured learning roadmaps**, **hands-on project-based courses**, and a **strong developer community** — all completely free.

Whether you're a complete beginner starting your first "Hello World" or an experienced developer looking to pick up a new skill, DevCampus has a path for you.

---

## Key Features

- **Structured Roadmaps** — Guided learning paths (e.g., "Become a Full Stack Developer") so you always know what to learn next
- **Video Courses** — High quality, focused programming courses
- **In-Browser Code Editor** — Write and run code directly in the browser, no setup needed
- **Quizzes & Challenges** — Test your knowledge after every lesson
- **Certificates** — Earn completion certificates to showcase your skills
- **Community** — Discussion threads, Q&A, and peer code reviews per course
- **GitHub Integration** — Link your projects and show your work
- **100% Free** — No paywalls, no premium tiers, always free

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React + Tailwind CSS |
| Backend | Node.js + Express |
| Database | PostgreSQL + Prisma |
| Video Hosting | Cloudinary |
| Authentication | JWT / Clerk |
| Frontend Hosting | Vercel |
| Backend Hosting | Railway |

---

## Project Structure

```
devcampus/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── components/     # Reusable UI components
│       ├── pages/          # Page-level components
│       ├── hooks/          # Custom React hooks
│       ├── context/        # Global state
│       └── utils/          # Helper functions
│
├── server/                 # Node.js backend
│   ├── controllers/        # Route logic
│   ├── routes/             # API routes
│   ├── middleware/         # Auth, error handling
│   ├── models/             # Database models (Prisma)
│   └── utils/              # Helper functions
│
├── prisma/
│   └── schema.prisma       # Database schema
│
└── README.md
```

---

## Roadmap

### Phase 1 — Foundation
- [ ] User authentication (Student / Instructor / Admin roles)
- [ ] Course listings & detail pages
- [ ] Student enrollment system
- [ ] Basic student dashboard

### Phase 2 — Learning Experience
- [ ] Video upload & playback per lesson
- [ ] Progress tracking
- [ ] Quizzes per course
- [ ] Auto-generated completion certificates

### Phase 3 — Community
- [ ] Discussion threads per course
- [ ] Student profiles & achievements
- [ ] Rating & review system
- [ ] Peer code review feature

### Phase 4 — Developer Tools
- [ ] In-browser code editor
- [ ] Coding challenges
- [ ] GitHub integration
- [ ] Structured learning roadmaps

### Phase 5 — Polish & Scale
- [ ] Advanced search & filters
- [ ] Admin dashboard
- [ ] Mobile responsiveness
- [ ] Performance & security hardening

---

## Getting Started

### Prerequisites
- Node.js v18+
- PostgreSQL
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/devcampus.git
cd devcampus

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

### Environment Variables

Create a `.env` file in the `/server` directory:

```env
DATABASE_URL=your_postgresql_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
PORT=5000
```

Create a `.env` file in the `/client` directory:

```env
VITE_API_URL=http://localhost:5000
```

### Run the App

```bash
# Run backend (from /server)
npm run dev

# Run frontend (from /client)
npm run dev
```

---

## Contributing

DevCampus is a solo project for now, but contributions are welcome in the future! Stay tuned for contribution guidelines.

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

---

> *DevCampus — Learn to code. Build real things. Grow together.*