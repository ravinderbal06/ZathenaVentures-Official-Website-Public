# ZathenaVentures-Official-Website **Public Version**

The official agency website for ZATHENA VENTURES; we provide digital solutions such as applications, websites, software, video editing, and many other assets for businesses and brands in a digital age

Website: https://zathenaventures.xyz

# Zathena Ventures

## Project Info

This is a React application built with Vite, TypeScript, shadcn-ui, and Tailwind CSS. It serves as the official website for Zathena Ventures, a digital innovation agency specializing in Web2 and Web3 solutions.

## Key Features & Services

Zathena Ventures offers a comprehensive suite of digital services and features a robust online presence:

*   **Dynamic Homepage**: Showcasing our mission, featured projects, team, client testimonials, and contact information.
*   **About Us**: Detailed history and vision of Zathena Ventures.
*   **Services Overview**:
    *   **Web Design & Hosting**: Custom, responsive websites with reliable hosting.
    *   **CRM Solutions**: Streamlined customer relationship management systems.
    *   **Full-Stack Development**: Custom-coded frontend and backend solutions.
    *   **Advanced Development**: Expertise in Web3, blockchain, AI, and mobile app development.
    *   **Video Production**: Professional video content creation for various needs.
    *   **Digital Strategy**: Comprehensive consulting for digital transformation and growth.
*   **Media Hub**: Explore our creative works including:
    *   **Videography**: Professional video production and editing.
    *   **Photography**: High-quality photography for brands and events.
    *   **Music**: Original music production and artist branding.
    *   **Literature**: Original graphic novels and short stories.
    *   **Podcasts**: Insightful conversations and audio storytelling.
*   **Portfolio Showcase**: A detailed display of our latest projects with filtering capabilities.
*   **Careers Portal**: Browse open job positions, view details, and apply online.
    *   **Job Applications**: Users can submit applications for open positions, with resume uploads.
    *   **Saved Jobs**: Authenticated users can save job positions for later.
*   **Community Forums**: Engage with other innovators, discuss trending topics, and connect with the Zathena Ventures community.
    *   **User Authentication**: Secure login and signup powered by Supabase, with `AuthSheet` and `AuthPrompt` components.
    *   **User Profiles**: Personalized profiles for community members, including posts, following, followers, and saved posts. Users can edit their own profiles.
    *   **Community Profiles**: Dedicated pages for each community with rules, topics, and member listings. Users can join/leave and favorite communities.
    *   **Interactive Posts**: Create new posts with media, like, comment, share, and save posts (requires login).
    *   **Following/Followers**: Users can follow other users and view their following/followers lists.
*   **Client Reviews**: Testimonials from satisfied clients across various platforms.
    *   **Google My Business Integration**: Live fetching and display of Google reviews (admin authorization required).
*   **Contact & Get Started Forms**: Easy ways to reach out for inquiries or project initiation.
    *   **HubSpot Integration**: All contact, project discovery, and portfolio submission forms are integrated with HubSpot for CRM management.
    *   **Project Discovery Dialog**: A dedicated dialog for new project inquiries.
    *   **Portfolio Submission Dialog**: For submitting portfolios for unlisted roles.
*   **Investment Opportunities**:
    *   **Direct Investments**: Securely invest directly via Stripe, with HubSpot deal creation and lifecycle management.
    *   **Custom Opportunities**: Submit inquiries for tailored investment deals, also integrated with HubSpot.
    *   **Stripe Integration**: Secure payment processing for direct investments.
*   **Our Digital Ecosystem Page (`/assets`)**: A central hub to explore all Zathena Ventures digital assets and connected brands, with single login functionality.
*   **Email Confirmation Page (`/confirm`)**: A dedicated page for users to land on after email confirmation, guiding them into the ecosystem.
*   **Team Member Profiles**: Dedicated pages for each team member with detailed bios and social links.
*   **Pricing Page**: Explore flexible bundles, pricing tools, and package plans.
*   **Responsive Design**: Optimized for seamless experience across all devices.
*   **Dark/Light Mode**: User-selectable theme preference.
*   **SEO Optimized**: Each page includes dynamic SEO metadata for better search engine visibility using `react-helmet-async`.
*   **Supabase Integration**: Backend for user authentication, profiles, job applications, projects, communities, and investment data.
*   **Edge Functions**: Utilizes Supabase Edge Functions for secure server-side logic, including HubSpot and Stripe integrations, Google OAuth, and user data archiving.
*   **Toasts**: Uses `sonner` for clean and simple toast notifications.
*   **Need Help Button**: A floating button providing quick access to a contact form.

## How can I edit this code?

If you want to work locally using your own IDE, you can clone this repo and push changes.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

This project can be deployed using standard web hosting services. The `.github/workflows/cPaneldeploy.yml` file contains a GitHub Actions workflow for deploying to HostGator via FTP, which can be adapted for other services.

For the live site to function correctly, you **must** set the following environment variables as **GitHub Repository Secrets** in your repository's settings (`Settings > Secrets and variables > Actions`):

*   `SUPABASE_URL`: Your Supabase Project URL (e.g., `https://ibzowkqabtshljttdjdw.supabase.co`)
*   `SUPABASE_ANON_KEY`: Your Supabase `anon public` key (starts with `eyJ...`)
*   `STRIPE_PUBLISHABLE_KEY`: Your Stripe publishable key (starts with `pk_live_...`)
*   `HUBSPOT_PORTAL_ID`: Your HubSpot Portal ID
*   `HUBSPOT_CONTACT_FORM_ID`: Your HubSpot Contact Form ID
*   `HUBSPOT_PROJECT_FORM_ID`: Your HubSpot Project Form ID
*   `GOOGLE_CLIENT_ID`: Your Google OAuth Client ID for GMB integration.
*   `GOOGLE_CLIENT_SECRET`: Your Google OAuth Client Secret for GMB integration.
*   `HUBSPOT_INVOICE_PIPELINE_ID`: **NEW** The ID of the HubSpot pipeline for invoices.
*   `HUBSPOT_INVOICE_SENT_STAGE_ID`: **NEW** The ID of the deal stage for invoices that have been sent.

These secrets are used during the build process to correctly configure your frontend application.

## Can I connect a custom domain to this project?

Yes, you can connect a custom domain through your hosting provider's settings.
