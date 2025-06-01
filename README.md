# amMentor — Project Hub
Welcome to the **amMentor** ecosystem!  
amMentor is an open-source, multi-platform mentorship management system built to streamline the entire learning journey between admins, mentors, and mentees. Designed originally by members of the amFOSS community, it enables structured learning, gamified tracking, and collaborative growth for college clubs, bootcamps, online cohorts, and mentorship programs.

### Problem It Solves

In most mentorship programs:
- Mentors and mentees struggle to track curriculum progress manually.
- There’s no centralized system to validate task submissions.
- Communications are scattered across platforms (email, Discord, spreadsheets, etc.).
- Admins find it hard to monitor engagement or performance.

amMentor solves this by providing a modular, role-based platform where:
- Admins define learning tracks and assign mentors.
- Mentors review, approve, and guide mentee submissions.
- Mentees complete tasks in sequence, earning points and badges.
- Everything is trackable, transparent, and gamified.

This repository serves as the **meta hub**, linking all four independently maintained components:

---

## 🔗 amMentor Repositories

| Component       | Built on                                            | Maintainer                                                                 |
|----------------|--------------------------------------------------------|----------------------------------------------------------------------------|
| [**Mobile App**](https://github.com/amfoss/ammentor)   | Flutter | [Gani Dande](https://github.com/ganidande905)               |
| [**Web App**](https://github.com/amfoss/amMentor-Web)   | Next.js | [Atharva Nair](https://github.com/atharvanair04)                     |
|[ **Backend API** ](https://github.com/amfoss/amMentor-Backend)  | FastAPI + PostgreSQL| [Gani Dande](https://github.com/ganidande905)             |
| [**Discord Bot**](https://github.com/amfoss/amMentor)   |  Python  | [Gani Dande](https://github.com/ganidande905)             |

---

## 🧩 System Architecture

```
    [ Mobile App ]           [ Web App ]      [Discord Bot]
           \                     /                 |
            \                   /                  |
               [ Backend API ]               [Google Sheets]
                      |
              [ PostgreSQL DB ]

```

---


## 🧠 Contributing

We welcome contributions across all modules!  
Please visit the relevant repo’s README for:
- Setup instructions
- Issue tracking
- Contribution guidelines

---

## 📄 License

All parts of amMentor are released under the **MIT License**.  
Feel free to use, fork, and contribute — with credit.

---

> Built with 💛 by amFOSS contributors
