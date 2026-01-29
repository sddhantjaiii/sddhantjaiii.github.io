# Siddhant Jaiswal - Full Stack Developer & AI Engineer

**Computer Science & Engineering Student**  
VIT Bhopal University | Expected Graduation: 2026  
📧 sddhantjaiii@gmail.com | 📱 +91 8979556941  
🔗 [LinkedIn](https://www.linkedin.com/in/sddhantjaiii) | [GitHub](https://github.com/sddhantjaiii) | [Portfolio](https://sddhantjaiii.github.io/)

---

## 👨‍💻 About Me

I am a final-year Computer Science & Engineering student at VIT Bhopal with a passion for building production-ready applications that solve real-world problems. With expertise spanning full-stack web development, mobile engineering, AI integration, and cloud infrastructure, I thrive on tackling complex technical challenges and delivering scalable solutions.

### Academic Excellence
- **CGPA:** 8.62/10.0
- **Key Coursework:** Data Structures & Algorithms, Operating Systems, Computer Networks, Computer Architecture, Embedded Systems, Design Analysis and Algorithms

### Achievements & Leadership
- 🏆 **First Place** - Cloud Computing Club Coding Competition (30+ teams)
- 👥 **Founder** - LC/NC Community at VIT Bhopal
- 💻 **500+ LeetCode Problems** - 1+ Year Streak | Medium-Hard algorithmic problem-solving
- 📚 **Sanskrit Club Founder** (High School) - Organized training sessions for 100+ students

---

## 🚀 Featured Projects

### 1. **HRMS Production System**
*Lead Architect & Full Stack Developer | Production System*

**Comprehensive Human Resource Management System (HRMS) designed to automate attendance via Face Detection, process payroll, and manage tenant subscriptions. Features a robust multi-platform architecture with Web Dashboard and Mobile App.**

#### Technical Architecture
- **Backend:** Python 3, Django, Gunicorn, Celery, Redis
- **Frontend:** React (Vite), TypeScript, Tailwind CSS
- **Mobile:** React Native, Expo, TypeScript (Face Detection)
- **Database:** PostgreSQL (Critical/Comprehensive Indexes)
- **Infrastructure:** Railway, Docker, Load Balancer

#### Key Technical Achievements
- **Face Detection Attendance:** Secure, foolproof presence tracking via mobile app.
- **Triple-Layer Credit System:** Custom subscription engine with Scheduler, Middleware, and Login layers for accurate credit management.
- **Automated Payroll Engine:** Unified calculator handling complex logic, variable pay, and ZeptoMail integration.
- **Custom Rule Engine:** Configurable weekly bonus/penalty logic per tenant.
- **System Resilience:** Architected for data integrity with optimized database schema and indexes.

#### Impact
- **Full Automation:** Replaced manual Excel tracking with automated workflows.
- **Zero Errors:** Automated TDS and payroll calculations eliminated manual errors.
- **Scalability:** Successfully handles production loads with robust architecture.

---

### 2. **The Club** - Mobile Marketplace for 1-to-1 Services
*Instagram meets Service Marketplace | Oct 2025 - Present*

**A revolutionary cross-platform mobile application enabling creators and service providers to showcase expertise through engaging reels and posts while connecting with buyers for personalized 1-to-1 services.**

#### Technical Architecture
- **Frontend:** React Native, Expo, TypeScript
- **Backend:** Supabase (PostgreSQL), Supabase Auth (JWT + OAuth)
- **Video Infrastructure:** Cloudflare R2, Railway FFmpeg Server (Node.js + FFmpeg 7.1)
- **Cloud Storage:** AWS S3 (backup), Supabase Storage
- **Native Modules:** Custom ExoPlayer Cache Module (Kotlin)
- **State Management:** React Context API

#### Key Technical Achievements
- **Custom Video Processing Pipeline:** 
  - Built FFmpeg server on Railway for automatic video compression (CRF 23)
  - Dual-quality output (1080p @ 8 Mbps, 480p @ 3 Mbps)
  - 40% file size reduction without quality loss
  - +faststart flag for instant streaming (no buffering)

- **Native ExoPlayer Cache Module (Android):**
  - Implemented TurboModule for React Native New Architecture
  - Kotlin-based asynchronous prefetch with coroutines
  - 1.5MB partial caching for smooth playback
  - 85%+ cache hit rate

- **AI-Powered Recommendation Engine:**
  - Collaborative filtering + content-based hybrid algorithm
  - Real-time weight adjustments based on user behavior
  - Cold-start problem solved with content-based fallback
  - 85% personalized, 15% discovery balance

- **Complex Technical Challenges Solved:**
  - Memory management with large videos (4K → optimized compression)
  - React Native New Architecture compatibility (TurboModules)
  - Cross-platform deployment (single codebase for iOS/Android)
  - Real-time messaging and activity feeds

#### Development Metrics
- **Codebase:** 50,000+ lines of code
- **Components:** 80+ React components
- **API Endpoints:** 30+ Supabase queries with Row Level Security
- **Build Time:** ~8 minutes (EAS Build + Gradle optimization)
- **App Size:** 65 MB (including FFmpeg and ExoPlayer libraries)
- **Development Time:** 4+ months intensive development

#### Links
- **Frontend Repo:** [github.com/ideatheclub1/TheclubFinalBuild](https://github.com/ideatheclub1/TheclubFinalBuild)
- **Backend Repo:** [github.com/shubham-droid/The-club](https://github.com/shubham-droid/The-club)
- **APK Download:** [Expo Build](https://expo.dev/accounts/siddhant.jaiswal/projects/my-expo-app/builds/895486b6-fe54-4254-8d95-1bc236ccbbb3)

---

### 3. **SniperThink AI CRM** - Enterprise AI Calling Platform
*Production SaaS Platform | Oct 2025 - Present*

**A comprehensive B2B SaaS platform enabling businesses to automate outbound/inbound calling campaigns using AI voice agents. Currently serving 5 paid clients with 100+ daily calls.**

#### Technical Architecture
- **Role:** Tech Lead / Lead Developer
- **Backend:** Node.js, TypeScript (80+ microservices)
- **Frontend:** React 18, shadcn/ui, TanStack Query
- **Database:** PostgreSQL (Neon Serverless DB)
- **Storage:** Cloudflare R2
- **AI Integrations:** OpenAI GPT-4, Bolna.ai (Voice AI), ElevenLabs
- **Additional Services:** WhatsApp Business API, Google Calendar Sync

#### Microservices Architecture
```
Core Services:
├── webhookService.ts (2000+ LOC) - Core webhook handler
├── QueueProcessorService.ts - Campaign queue management
├── bolnaService.ts - Bolna.ai API client
├── openaiExtractionService.ts - Lead analysis engine
├── ConcurrencyManager.ts - Call slot management
├── leadAnalyticsService.ts - Dual analysis pattern
├── chatAgentService.ts - WhatsApp proxy layer
└── 73+ additional services
```

#### Complex Technical Challenges Solved

1. **Voice AI Provider Migration (ElevenLabs → Bolna.ai)**
   - Migrated entire voice AI infrastructure without service disruption
   - Redesigned webhook processing for Bolna's 5-stage call lifecycle
   - Implemented backward compatibility during transition

2. **Bulletproof Concurrency Management**
   - Global locks and per-user slots for call management
   - Prevents system overload under high concurrent load
   - Queue-based campaign processing

3. **Dual Lead Analytics Pattern**
   - Individual call analysis for debugging
   - Aggregated contact profiles for CRM view
   - Real-time analytics dashboard

4. **Multi-Tenant Data Isolation**
   - Enforced user_id filtering on every database query
   - Prevents cross-tenant data leakage
   - Row-level security policies

#### Key Features
- **AI Voice Agents:** Natural conversation flow with OpenAI GPT-4
- **Real-time Analytics:** KPIs tracking (leads, conversions, success rate)
- **Campaign Management:** Queue-based outbound/inbound campaigns
- **Lead Intelligence:** Automated lead scoring and analysis
- **WhatsApp Integration:** Template messaging via Meta Business API
- **Calendar Sync:** Google Calendar integration for appointments

#### Production Metrics
- **Active Clients:** 5 paid businesses
- **Daily Call Volume:** 100+ automated calls
- **Success Rate:** 53.33%
- **Lead Quality Score:** 8.5/10 average
- **System Uptime:** 99%+ with webhook retry logic

#### Links
- **Backend Repo:** [github.com/sddhantjaiii/Calling-agent-with-bolna](https://github.com/sddhantjaiii/Calling-agent-with-bolna)
- **Chat Agent Repo:** [github.com/sddhantjaiii/Chat-agent-Sniperthink](https://github.com/sddhantjaiii/Chat-agent-Sniperthink)
- **Live Demo:** [agenttest.sniperthink.com](https://agenttest.sniperthink.com)

---

### 4. **E-Commerce Product Recommender with AI Explanations**
*Academic Project | Jan 2025*

**Intelligent product recommendation system using hybrid algorithms and OpenAI GPT-4o-mini for personalized AI-generated explanations.**

#### Technical Stack
- **Frontend:** Next.js 15 (App Router), TypeScript, Tailwind CSS, shadcn/ui
- **Backend:** Next.js API Routes (Serverless)
- **Database:** PostgreSQL (Neon), Prisma ORM
- **AI:** OpenAI GPT-4o-mini
- **Authentication:** Custom JWT with bcrypt, jose
- **External APIs:** Fake Store API (product data)

#### Recommendation Engine

**Three-Stage Algorithm:**
1. **Cold Start (0-2 views):** Trending products based on ratings
2. **Warm Start (3-9 views):** Rule-based recommendations (same category, similar price)
3. **Hot Start (10+ views):** Hybrid collaborative filtering + rule-based

#### AI-Powered Explanations
- Context-aware prompt engineering with user behavior analysis
- Personalized 2-3 sentence explanations for top 3 recommendations
- Cost optimization: Only for logged-in users
- Graceful error handling with fallback messages

#### Key Features
- **Behavior Tracking:** VIEW, ADD_TO_CART, REMOVE_FROM_CART, PURCHASE, SEARCH, TIME_SPENT
- **Guest Support:** Session-based tracking with 30-day retention
- **Admin Testing Panel:** Real-time simulation and demonstration
- **1-hour Caching:** Per-user recommendation caching for performance
- **Custom Authentication:** JWT-based with HttpOnly cookies (7-day expiry)

#### Technical Highlights
- Multi-tenant data isolation with Prisma RLS
- API route optimization with request caching
- Database indexing for 40% faster queries
- Asynchronous background processing
- Comprehensive error handling and logging

#### Links
- **GitHub:** [github.com/sddhantjaiii/Ecoomerce_recommendation_system](https://github.com/sddhantjaiii/Ecoomerce_recommendation_system)
- **Live Demo:** [recommendationsystem.siddhantjaiswal.tech](https://recommendationsystem.siddhantjaiswal.tech)
- **Video Demo:** [YouTube](https://youtu.be/yp9Fi1m3Fuw)

---

### 5. **File Sharing and Management System**
*Backend Engineering Project | Apr 2025*

**Secure file-sharing application with high-performance concurrent upload handling and intelligent caching.**

#### Technical Stack
- **Backend:** Go (Golang)
- **Database:** PostgreSQL
- **Caching:** Redis
- **Storage:** AWS S3
- **Authentication:** JWT

#### Key Technical Achievements
- **Concurrent Upload Handling:** Go routines for parallel file processing
- **Redis Caching Layer:** 40% reduction in metadata query latency
- **Optimized Database Indexing:** Improved query performance
- **Asynchronous Background Workers:**
  - File processing pipelines
  - Automated cleanup jobs
  - Prevents resource contention under high load
- **Security Features:**
  - JWT-based authentication
  - Secure file access controls
  - Encrypted file metadata

#### Performance Metrics
- 40% faster metadata retrieval with Redis
- Handles 100+ concurrent uploads
- Automated cleanup prevents storage bloat
- Sub-second file access times

#### Links
- **GitHub:** [github.com/sddhantjaiii/File_Sharing_and_Management_System](https://github.com/sddhantjaiii/File_Sharing_and_Management_System)
- **Video Demo:** [YouTube](https://www.youtube.com/watch?v=ezTB_TqruHA)

---

### 6. **AI-Powered MCQ Generator**
*Full-Stack Web Application | Jan 2025*

**Intelligent multiple-choice question generator using OpenAI GPT models with difficulty control and automated retry logic.**

#### Technical Stack
- **Frontend:** React, responsive design
- **Backend:** Node.js, Express
- **AI:** OpenAI API (GPT models)
- **Infrastructure:** REST API architecture

#### Key Features
- **Difficulty-Controlled Generation:** Easy, Medium, Hard, Expert levels
- **Intelligent Prompt Orchestration:** Context-aware question generation
- **Automated Retry Logic:** Handles API failures gracefully
- **Real-time Generation:** Instant MCQ creation from topics
- **Responsive UI:** Mobile-first design

#### Technical Highlights
- Handles hundreds of daily requests
- Smart prompt engineering for quality questions
- Error handling with exponential backoff
- Rate limiting and request queuing
- Caching for common topics

#### Links
- **GitHub:** [github.com/sddhantjaiii/MCQ_GENRATOR](https://github.com/sddhantjaiii/MCQ_GENRATOR)
- **Live Demo:** [mcq.siddhantjaiswal.tech](http://mcq.siddhantjaiswal.tech/)

---

### 7. **Time Travel Debugger**
*Python Library | Feb 2024*

**Python debugging library enabling backward code execution stepping, inspired by dry-run problem-solving on LeetCode.**

#### Technical Details
- **Language:** Python
- **Distribution:** PyPI (pip installable)
- **Installation:** `pip install time-travel-debugger`

#### Key Features
- Backward stepping through code execution
- Variable state tracking across execution steps
- Useful for algorithm debugging and learning
- Integration with Python debugging workflow

#### Links
- **PyPI Package:** [pypi.org/project/time-travel-debugger](https://pypi.org/project/time-travel-debugger/)
- **GitHub:** [github.com/sddhantjaiii/Time-Travel-debugger](https://github.com/sddhantjaiii/Time-Travel-debugger)

---

### 8. **QR Code Scanner**
*Flutter-based Web Application*

**Python-powered QR code scanning application deployed on Google Cloud with Docker for scalability.**

#### Technical Stack
- **Frontend:** Flutter
- **Backend:** Python Flask
- **QR Processing:** pyzbar, OpenCV
- **Deployment:** Google Cloud Run, Docker
- **Infrastructure:** Container orchestration

#### Key Features
- Real-time QR code scanning
- Mobile-responsive interface
- Cloud-native deployment
- Docker containerization for scalability
- Auto-scaling with Google Cloud Run

#### Links
- **GitHub:** [github.com/sddhantjaiii/Projects/tree/main/QR-Scanner-Flask](https://github.com/sddhantjaiii/Projects/tree/main/QR-Scanner-Flask)
- **Live Demo:** [Google Cloud Run](https://qr-app-617349892806.us-central1.run.app/)

---

## 💻 Technical Skills

### Programming Languages
- **Expert:** JavaScript/TypeScript, Python, Java
- **Proficient:** Go (Golang), Kotlin, SQL
- **Familiar:** C++, Swift

### Frontend Development
- **Frameworks:** React.js, Next.js 15, React Native, Expo
- **UI Libraries:** Tailwind CSS, shadcn/ui, Material-UI
- **State Management:** React Context API, TanStack Query, Redux
- **Mobile:** React Native (New Architecture), Expo EAS Build

### Backend Development
- **Frameworks:** Node.js, Express.js, Flask
- **APIs:** RESTful APIs, GraphQL, Webhooks
- **Microservices:** 80+ service architecture, message queuing
- **Real-time:** WebSockets, Server-Sent Events

### Databases & Storage
- **Relational:** PostgreSQL, MySQL, Neon Serverless DB
- **NoSQL:** Redis (caching)
- **ORMs:** Prisma, TypeORM
- **Cloud Storage:** AWS S3, Cloudflare R2, Supabase Storage

### Cloud & DevOps
- **Platforms:** AWS, Google Cloud, Railway, Vercel, Netlify
- **Services:** Cloud Run, EAS Build, Supabase
- **Containerization:** Docker, Docker Compose
- **CI/CD:** GitHub Actions, Expo OTA Updates
- **Monitoring:** Sentry (error tracking)

### AI & Machine Learning
- **LLMs:** OpenAI GPT-4, GPT-4o-mini
- **Voice AI:** Bolna.ai, ElevenLabs
- **Integration:** API orchestration, prompt engineering
- **Recommendation Systems:** Collaborative filtering, hybrid algorithms

### Native Development
- **Android:** Kotlin, ExoPlayer, TurboModules
- **iOS:** Swift (basic)
- **React Native Modules:** Custom native module development

### Video & Media Processing
- **Tools:** FFmpeg 7.1, ExoPlayer
- **Optimization:** Video compression (CRF), HLS streaming
- **Caching:** Partial content caching, prefetch strategies

### Tools & Technologies
- **Version Control:** Git, GitHub
- **IDEs:** VS Code, Android Studio
- **API Testing:** Postman, Thunder Client
- **Design:** Figma (basic)
- **Package Managers:** npm, pip, go mod

---

## 🎯 Core Competencies

### Software Engineering
- **Full-Stack Development:** End-to-end application development
- **System Architecture:** Microservices, scalable infrastructure design
- **Database Design:** Schema optimization, indexing, query performance
- **API Development:** RESTful services, webhook handling, rate limiting

### Mobile Engineering
- **Cross-Platform Development:** React Native for iOS/Android
- **Native Modules:** Custom Kotlin/Swift integration
- **Performance Optimization:** Memory management, lazy loading, caching
- **Build & Deployment:** EAS Build, App Store/Play Store releases

### Cloud & Infrastructure
- **Serverless Architecture:** Next.js API routes, Cloud Functions
- **Container Orchestration:** Docker deployment, auto-scaling
- **Video Processing:** FFmpeg pipelines, cloud storage optimization
- **Cost Optimization:** Efficient resource usage, caching strategies

### AI Integration
- **LLM Implementation:** OpenAI API integration, prompt engineering
- **Voice AI:** Real-time conversation flows, webhook processing
- **Recommendation Systems:** Hybrid algorithms, personalization
- **Data Analysis:** Lead scoring, behavior tracking, analytics

### Problem Solving
- **Algorithmic Thinking:** 500+ LeetCode problems (Medium-Hard level) | 1+ Year Streak
- **Debugging:** Complex issue resolution, performance profiling
- **Optimization:** Query optimization, caching, code refactoring
- **Innovation:** Creative solutions to technical challenges

---

## 📊 Impact Metrics

### Production Systems
- **HRMS Production System:** Automated face recognition attendance & payroll engine for enterprise clients
- **The Club:** 50,000+ lines of code, 80+ components, cross-platform mobile app
- **SniperThink AI CRM:** 5 paid clients, 100+ daily calls, 99%+ uptime
- **Time Travel Debugger:** Published Python package on PyPI
- **QR Scanner:** Cloud-deployed with auto-scaling

### Technical Achievements
- **40% Performance Improvement:** Video compression, caching optimization
- **85%+ Cache Hit Rate:** ExoPlayer prefetch strategy
- **Zero Downtime Migration:** Voice AI provider switch (ElevenLabs → Bolna.ai)
- **Multi-Tenant Security:** Row-level security, data isolation

### Open Source & Community
- **PyPI Package:** time-travel-debugger
- **GitHub Repositories:** 10+ public projects
- **Community Founder:** LC/NC at VIT Bhopal
- **Coding Competition Winner:** 30+ teams, Cloud Computing Club

---

## 🎓 Education

**Bachelor of Technology - Computer Science & Engineering**  
VIT Bhopal University | 2022 - 2026  
**CGPA:** 8.62/10.0

**Relevant Coursework:**
- Data Structures & Algorithms
- Operating Systems
- Computer Networks
- Computer Architecture
- Embedded Systems
- Design Analysis and Algorithms
- Database Management Systems
- Software Engineering

**12th Grade (ISC) - G.P.M College**  
**Score:** 85.5% | 2021  
**Subjects:** Physics, Chemistry, Mathematics, English, Computer Science

**10th Grade (ICSE) - G.P.M College**  
**Score:** 85% | 2019  
**Subjects:** Science, Mathematics, English, Computer Science, History & Civics, Hindi

---

## 🏆 Achievements & Extracurriculars

### Technical Achievements
- 🥇 **First Place** - Cloud Computing Club Coding Competition (30+ teams, VIT Bhopal)
- 💻 **500+ LeetCode Problems** - 1+ Year Streak | Medium-Hard level challenges
- 📦 **PyPI Package Author** - time-travel-debugger
- 🚀 **Production SaaS Developer** - 5 paid clients, 100+ daily automated calls

### Leadership & Community
- 👥 **Community Founder** - LC/NC (Low Code/No Code) at VIT Bhopal
- 🎓 **Sanskrit Club Founder** (High School) - Organized training for 100+ students
- 📚 **Technical Mentor** - Guiding peers in full-stack development

### Coding Profiles
- **LeetCode:** [sddhantjaiii](https://leetcode.com/sddhantjaiii/) - 500+ problems solved | 1+ Year Streak | Contest Participant
- **GeeksforGeeks:** [sddhantjaiii](https://www.geeksforgeeks.org/user/sddhantjaiii/) - Active Problem Solver
- **GitHub:** [sddhantjaiii](https://github.com/sddhantjaiii) - 10+ public repositories | 50,000+ lines of production code

---

## 📞 Contact & Links

**Email:** sddhantjaiii@gmail.com  
**Phone:** +91 8979556941  
**Location:** VIT Bhopal, Madhya Pradesh, India

**Professional Links:**
- 💼 **LinkedIn:** [linkedin.com/in/sddhantjaiii](https://www.linkedin.com/in/sddhantjaiii/)
- 🐙 **GitHub:** [github.com/sddhantjaiii](https://github.com/sddhantjaiii)
- 🌐 **Portfolio:** [sddhantjaiii.github.io](https://sddhantjaiii.github.io/)

**Coding Profiles:**
- 💻 **LeetCode:** [leetcode.com/sddhantjaiii](https://leetcode.com/sddhantjaiii/) - 500+ Problems | 1+ Year Streak
- 📝 **GeeksforGeeks:** [geeksforgeeks.org/user/sddhantjaiii](https://www.geeksforgeeks.org/user/sddhantjaiii/)

---

## 🎯 Career Interests

I'm passionate about:
- **Full-Stack Engineering:** Building scalable web and mobile applications
- **AI/ML Integration:** Leveraging LLMs and voice AI in production systems
- **Cloud Architecture:** Designing distributed systems and microservices
- **Mobile Development:** Cross-platform apps with native performance
- **Open Source:** Contributing to developer tools and libraries

**Currently seeking:**
- Full-time Software Engineering roles (July 2026)
- Internship opportunities in Full-Stack/Mobile/AI domains
- Collaborative projects involving cutting-edge technologies

---

## 💡 What Sets Me Apart

### 1. **Production-Ready Code**
I don't just build projects—I ship products. My SniperThink AI CRM serves 5 paid clients with 100+ daily calls, demonstrating my ability to handle real-world production challenges.

### 2. **End-to-End Ownership**
From architecture design to deployment, I take full ownership of projects. The Club (50,000+ LOC) showcases my ability to manage complex full-stack systems independently.

### 3. **Problem Solver**
Whether it's migrating voice AI providers without downtime, optimizing video streaming for mobile, or building custom native modules, I thrive on solving hard technical problems.

### 4. **Fast Learner**
In 4 months, I went from concept to a production-ready mobile app (The Club) with custom Kotlin modules, FFmpeg processing, and AI recommendations—demonstrating rapid learning and execution.

### 5. **Business-Minded Engineer**
I understand that great code serves business needs. My projects focus on user experience, cost optimization, and measurable impact (40% performance improvement, 85% cache hit rate).

---

## 📚 Currently Learning

- **Advanced Kubernetes** - Container orchestration at scale
- **System Design** - Distributed systems and scalability patterns
- **Mobile Optimization** - Advanced React Native performance techniques
- **AI Engineering** - Fine-tuning LLMs and retrieval-augmented generation (RAG)

---

*Last Updated: January 29, 2026*

---

> **"I believe great software engineering is about more than writing code—it's about architecting systems that scale, solving real problems, and creating products that users love."**  
> — Siddhant Jaiswal
