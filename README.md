SOFTWARE_ENGINEERING_GROUP6_BSEM1201
Career Guidance & Student Support Portal

A mobile application empowering African students to plan and navigate their career journeys through personalized career assessment, mentorship, learning resources, and scholarship discovery all in one accessible platform.

Built in alignment with UN Sustainable Development Goal 4: Quality Education (Targets 4.4 and 4.6).



 About the Project

Students in underserved and rural communities across Africa face a critical challenge: limited access to career counselors, mentors, and structured educational guidance. The Career Guidance & Student Support Portal addresses this gap with a free, mobile-first, offline-capable platform designed specifically for the African context.

 Key Features

- Career Assessment Personalized assessments grounded in Holland's RIASEC theory, generating tailored career roadmaps
- Mentor Connect Real-time chat with professional mentors and counselors
- Learning Resources Downloadable past papers, study guides, and video tutorials (offline-accessible)
- Scholarships & Opportunities Curated scholarships, internships, and training programs
- Progress Tracker Milestone-based progress tracking with achievement badges
- SDG Impact Dashboard Real-time statistics on platform reach and impact



Tech Stack

| Component | Technology |
|---|---|
| Mobile Frontend | React Native (cross-platform) |
| Backend Server | Node.js with Express.js |
| Database | Firebase Firestore (NoSQL) |
| Authentication | Firebase Authentication |
| File Storage | Firebase Storage |
| Push Notifications | Firebase Cloud Messaging (FCM) |
| UI/UX Design | Figma |
| Version Control | GitHub |
| API Communication | RESTful API over HTTPS |



 System Architecture

The system follows a Three-Tier Client-Server Architecture:

- Presentation Layer React Native mobile app (Android & iOS)
- Application Layer Node.js/Express backend handling business logic via RESTful API
- Data Layer Firebase Firestore, storing Users, Careers, Resources, Mentors, Opportunities, and Progress data

See `/docs` for full architecture diagrams, UML models (Use Case, Class, Activity diagrams), and detailed component descriptions.

---

 Methodology

This project was developed using the Agile Software Development Life Cycle, delivered across 7 sprints over an 11-week timeline:

1. Planning & Requirements Gathering
2. System Architecture Design & UML Diagrams
3. UI/UX Design — Onboarding & Career Assessment
4. UI/UX Design — Learning, Mentorship & Opportunities
5. UI/UX Design — Profile, Progress & SDG Impact
6. Testing, Review & Iteration
7. Documentation, Finalization & Submission



 Prototype

A high-fidelity, 15-screen prototype was designed in Figma, covering the full user journey from onboarding through career guidance and opportunity application.

🔗 Figma Prototype: _[add link here]_



 Repository Structure


├── README.md           Project overview, SDG alignment, setup instructions
├── /docs                Project report, system architecture diagram, UML diagrams
├── /prototype           Figma-exported screens and prototype link
├── /diagrams            Gantt chart and network diagram
└── /assets              Logo and design system files




SDG Alignment

This project directly supports SDG 4: Quality Education, specifically:

- Target 4.4 — Increasing the number of youth with relevant skills for employment
- Target 4.6 — Ensuring equal access to affordable, quality education

By democratizing access to career guidance, the portal contributes to closing the education and opportunity gap facing African youth.



 Getting Started

> ⚠️ This repository currently documents the software design phase (architecture, UML, prototype, and project plan). Implementation setup instructions will be added as development begins.

```bash
 Clone the repository
git clone https://github.com/<your-username>/career-guidance-portal.git
cd career-guidance-portal

 Install dependencies (once implementation begins)
npm install

 Run the app
npm start
```



 Project Management

- Total Duration: 11 weeks
- Critical Path: Planning → Requirements → Architecture → UML Diagrams → Prototype (Screens 1–8) → Prototype (Screens 9–15) → Testing → Report → Submission

See `/diagrams` for the full Gantt chart and Network Diagram.



 Contributing

Contributions are welcome. Please open an issue to discuss proposed changes before submitting a pull request.



License

This project is licensed under the MIT License see the [LICENSE](LICENSE) file for details. The MIT License was chosen for its compatibility with the Digital Public Goods Standard, enabling free use, modification, and distribution by schools, NGOs, and governments.



Acknowledgements

- Holland, J. L. (1959) Theory of Vocational Choice (RIASEC)
- Super, D. E. (1980)  Life-Span, Life-Space Theory
- United Nations  2030 Agenda for Sustainable Development
- Digital Public Goods Alliance — DPG Standard v1.1.5
