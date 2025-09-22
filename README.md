<p align="center">
  <img src="https://zathenaventures.xyz/Horizontal.png" alt="Zathena Ventures Logo" width="300"/>
</p>

<h1 align="center">Zathena Ventures - Digital Innovation Hub</h1>

<p align="center">
  <strong>Empowering brands and creators with cutting-edge Web2 & Web3 solutions, bespoke development, and transformative digital strategies.</strong>
</p>

<p align="center">
  <em>Innovation. Creativity. Strategy. Execution.</em>
</p>

<p align="center">
  <a href="https://zathenaventures.xyz/home" target="_blank" rel="noopener noreferrer">🌐 Visit Our Website</a>
  •
  <a href="https://zathenaventures.xyz/portfolio" target="_blank" rel="noopener noreferrer">📁 Explore Our Portfolio</a>
  •
  <a href="https://zathenaventures.xyz/contact" target="_blank" rel="noopener noreferrer">📞 Get In Touch</a>
</p>

---

## 🚀 About Us

At ZATHENA VENTURES, we thrive on innovation, creativity, and problem-solving. Our mission is to transform ideas into digital realities, empowering brands, businesses, and creators with the tools they need to succeed.

We don't just build products — we craft strategies, ecosystems, and experiences that inspire growth and deliver measurable results. Our expertise spans cutting-edge Web2 and Web3 solutions, custom software development, immersive video games, and compelling digital media. We are committed to pushing boundaries and setting new standards in the digital landscape.

## Project Overview

This is the official React application for Zathena Ventures, meticulously crafted with Vite, TypeScript, `shadcn/ui`, and Tailwind CSS. It serves as a dynamic digital innovation hub, showcasing our expertise in delivering high-impact solutions across various digital domains. From immersive user experiences to robust backend systems and advanced Web3 integrations, Zathena Ventures is dedicated to building the future, today.

Our platform is designed not just to inform, but to engage, connect, and empower our community and clients. It's a testament to our commitment to innovation, authenticity, and raising the standard of internet quality.

## Key Features & Services

Zathena Ventures offers a comprehensive and interconnected digital ecosystem, designed to meet the diverse needs of modern businesses and creators:

### 🌐 **Core Web Platform & User Experience**
*   **Dynamic Homepage**: A captivating entry point showcasing our mission, featured projects, visionary team, glowing client testimonials, and clear calls to action.
*   **About Us**: Dive deep into the history, values, and forward-thinking vision that drives Zathena Ventures.
*   **Services Overview**: A detailed exploration of our specialized offerings:
    *   **Web Design & Hosting**: Crafting custom, responsive, and high-performance websites with reliable, secure hosting.
    *   **CRM Solutions**: Implementing streamlined customer relationship management systems for enhanced efficiency and engagement.
    *   **Full-Stack Development**: Delivering bespoke frontend and backend solutions tailored to unique business logic and scalability needs.
    *   **Advanced Development**: Pioneering solutions in Web3, blockchain, AI, mobile app development, and immersive video games.
    *   **Video Production**: Professional end-to-end video content creation for impactful storytelling and brand narratives.
    *   **Digital Strategy**: Providing comprehensive consulting for digital transformation, market positioning, and sustainable growth.
*   **Media Hub**: A creative showcase of our artistic and content production capabilities:
    *   **Videography**: Our portfolio of professional video production and editing.
    *   **Photography**: High-quality photography for brands, events, and creative projects.
    *   **Music**: Featuring original music production and artist branding from Zathena Ventures Productions.
    *   **Literature**: Exploring original graphic novels and compelling short stories.
    *   **Podcasts**: Insightful conversations and audio storytelling with industry leaders and innovators.
*   **Portfolio Showcase**: An interactive display of our latest projects, complete with detailed case studies and filtering capabilities.
*   **Careers Portal**: Discover open job positions, view detailed descriptions, and apply online to join our growing team.
*   **Team Page**: Meet the brilliant minds and dedicated professionals who make Zathena Ventures a leader in digital innovation.
*   **Client Reviews**: Authentic testimonials from satisfied clients, including live integration with Google My Business.
*   **Contact & Get Started Forms**: Seamless pathways for inquiries, project initiation, and scheduling consultations.
*   **Investment Opportunities**: Explore direct investment options via Stripe and custom opportunities, all integrated with our CRM.
*   **Our Digital Ecosystem Page (`/assets`)**: A central hub to navigate all Zathena Ventures digital assets and connected brands, offering a unified login experience.
*   **Email Confirmation Page (`/confirm`)**: A dedicated landing page for users post-email confirmation, guiding them into our ecosystem.
*   **Pricing Page**: (Coming Soon) Explore flexible bundles, pricing tools, and custom package plans.
*   **Legal Pages**: Comprehensive Privacy Policy, Terms of Service, and Cookie Policy for transparency and compliance.

### 🤝 **User & Community Engagement**
*   **Robust User Authentication**: Secure login and signup powered by Supabase, featuring `AuthSheet` and `AuthPrompt` components, and a custom login form with ban status checks.
*   **Personalized User Profiles**: Authenticated users can manage their profiles, including personal details, avatar, professional information, and view their posts, saved content, applications, and receipts.
*   **Dynamic Community Forums**: Engage in vibrant discussions, create new posts with rich media, and interact with a thriving community of innovators.
*   **Following & Followers**: Users can follow other members, view their following/followers lists, and favorite key connections.
*   **Interactive Posts**: Like, comment, share, and save posts within the community (requires login).
*   **Community Profiles**: Dedicated pages for each community, detailing rules, topics, and member listings, with options to join/leave and favorite communities.
*   **Hooks for Interaction**: Leverages `useUserProfile`, `useCommunityInteraction`, `useUserFollowInteraction`, `useUserSavedPosts`, and `useTrendingTopics` for seamless data management.

### 📊 **Business & CRM Integrations**
*   **HubSpot Integration**: All contact, project discovery, and portfolio submission forms are deeply integrated with HubSpot for comprehensive CRM management, deal creation, and ticket tracking.
*   **Stripe Integration**: Secure payment processing for direct investments, with automated HubSpot deal lifecycle management.
*   **Google My Business Integration**: Live fetching and display of Google reviews (admin authorization required).
*   **Supabase Edge Functions**: Utilizes serverless functions for secure, efficient backend logic, including:
    *   `create-contact-ticket`: Generates HubSpot tickets from contact form submissions.
    *   `create-hubspot-ticket`: Creates HubSpot tickets from project discovery forms.
    *   `create-pending-hubspot-deal`: Initiates HubSpot deals for direct investments.
    *   `create-custom-opportunity-deal`: Manages HubSpot deals for custom investment inquiries.
    *   `create-payment-intent-edge`: Securely creates Stripe Payment Intents.
    *   `stripe-webhook-handler`: Processes Stripe payment success events, updating investments and HubSpot deals.
    *   `google-oauth-init` & `exchange-gmb-code`: Manages Google My Business OAuth flow.

### 🛠️ **Admin & Management Tools**
*   **Admin Tools Button & Dialog**: A floating, accessible button for administrators to quickly access management tools.
*   **User Management**: Comprehensive interface for viewing, creating, editing, banning, and deleting user accounts, including sending password resets and magic links.
*   **Portfolio Management**: Tools for administrators to create, edit, and delete portfolio projects, ensuring your showcase is always up-to-date.
*   **Reviews Management**: Manage client reviews, including Google My Business entries and manually added testimonials, with options for visibility control.
*   **CRM Tools Dialog**: Centralized access for admins to create HubSpot deals, tickets, tasks, and manage invoices directly.
*   **Edge Functions for Admin**: `admin-user-actions`, `create-hubspot-deal-admin`, `create-hubspot-task-admin`, `create-hubspot-invoice-admin`, `fetch-hubspot-pipelines-admin`, `fetch-hubspot-deal-stages-admin`, `fetch-hubspot-ticket-stages-admin`.

### ✨ **Design & Performance**
*   **Responsive Design**: Optimized for a flawless experience across all devices, from mobile to desktop.
*   **Dark/Light Mode**: User-selectable theme preference for personalized browsing.
*   **SEO Optimized**: Each page includes dynamic SEO metadata using `react-helmet-async` for superior search engine visibility.
*   **Toasts**: Utilizes `sonner` for clean, non-intrusive, and informative notifications.
*   **Smooth Transitions**: Enhanced user experience with elegant UI animations and transitions.

---

## Tech Stack Deep Dive

Our application is built on a modern and robust tech stack, ensuring performance, scalability, and maintainability:

*   **Framework**: **React 18** with **Vite** for blazing-fast development and optimized builds.
*   **Language**: **TypeScript** for enhanced type safety and developer productivity.
*   **UI Components**: **`shadcn/ui`** built on **Radix UI primitives**, providing a consistent, accessible, and highly customizable component library.
*   **Styling**: **Tailwind CSS** for utility-first styling, enabling rapid and responsive UI development.
*   **Routing**: **React Router (`react-router-dom`)** for efficient client-side navigation.
*   **Data Fetching & State Management**: **TanStack Query** for managing server state (API data caching, synchronization, and updates) and **React Hooks (`useState`, `useEffect`, `useContext`)** for local component state.
*   **Forms**: **React Hook Form** with **Zod** for robust, type-safe form handling and validation.
*   **Icons**: **`lucide-react`** for a comprehensive and consistent set of vector icons.
*   **Notifications**: **`sonner`** for elegant and simple toast notifications.
*   **SEO**: **`react-helmet-async`** for managing document head metadata, crucial for search engine optimization.
*   **Backend & Authentication**: **Supabase** provides a powerful backend-as-a-service, handling user authentication, real-time database operations, and serverless Edge Functions.
*   **Payments**: **Stripe** for secure and seamless payment processing.
*   **CRM**: **HubSpot** integration for comprehensive customer relationship management, deal tracking, and marketing automation.
*   **Utilities**: `clsx` and `tailwind-merge` for intelligently combining Tailwind classes, `date-fns` for date manipulation, `uuid` for unique ID generation, and custom `scrollUtils` for enhanced navigation.

---
---
ℹ️ This is the **public version** of the private repository [ZATHENA-VENTURES/ZathenaVentures-Official-Website](https://github.com/ZATHENA-VENTURES/ZathenaVentures-Official-Website).
It contains the official README, project description, and homepage link but omits sensitive deployment details.
