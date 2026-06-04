MyNutriCoach - Frontend Application
MyNutriCoach is a nutrition consultation platform that goes beyond simple appointment booking. It provides a science-backed, fully personalized nutrition plan designed specifically around your body, your goals, and your lifestyle.

Our platform connects patients with expert nutritionists to ensure that every consultation is a step towards a healthier, tailored nutritional journey.

-) Key Features
User Authentication: Secure Login and Signup pages for patients.

Appointment Management: An intuitive admin interface (MeetTable.jsx) to confirm or decline patient bookings.

Real-time Notifications: Integrated notification system (Notificationbell.jsx) to keep patients updated on their appointment status and provide Google Meet links.

Dashboard Navigation: Separate views for Users and Admin to ensure a personalized experience.

Dynamic Booking: Easy-to-use form for patients to schedule their consultations.

-)Project Structure
The project is built with React.js and follows a component-based architecture:

/components: Reusable UI elements (Navbar, Footer, cards).

/pages: Main application views (Dashboard, MeetTable, Login, Signup, BookAppointment).

App.jsx: Main routing configuration using react-router-dom.

-)Tech Stack
Frontend: React.js (Vite)

Routing: React Router

State Management: React Hooks (useState, useEffect, useCallback)

API Communication: Fetch API (interacting with a Node.js backend)
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
