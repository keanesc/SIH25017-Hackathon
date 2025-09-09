# Alumni Management System

## Overview

Many educational institutions lack a reliable and centralized system to manage their alumni data. After graduation, important information such as contact details, academic records, and career updates are often scattered or lost. Communication typically happens through informal WhatsApp groups or outdated mailing lists, limiting long-term engagement and collaboration.

This project aims to build a comprehensive Alumni Management System to bridge this gap and enhance the connection between institutions and their alumni.

## Features

- **Centralized Database:** Store and update all alumni data in one secure platform.
- **Communication Tools:** Facilitate messaging and networking among alumni and administrators.
- **Event Management:** Organize and manage alumni events with ease.
- **Career Tracking:** Monitor career progress and provide mentorship opportunities.
- **Donation Management:** Securely track and manage alumni donations.
- **User-Friendly Interface:** Intuitive design for both administrators and alumni users.

## Features

- supabase-ssr. A package to configure Supabase Auth to use cookies
- Password-based authentication block
- Styling with [Tailwind CSS](https://tailwindcss.com)
- Components with [shadcn/ui](https://ui.shadcn.com/)
- Optional deployment with [Supabase Vercel Integration and Vercel deploy](#deploy-your-own)
  - Environment variables automatically assigned to Vercel project

## Expected Benefits

- Strengthened alumni relationships.
- Enhanced opportunities for mentoring, internships, and fundraising.
- Improved outreach and engagement using digital tools.

## Getting Started


3. Use `cd` to change into the app's directory

   ```bash
   cd with-supabase-app
   ```

4. Update the following at `.env.local`:

   ```
   NEXT_PUBLIC_SUPABASE_URL=[INSERT SUPABASE PROJECT URL]
   NEXT_PUBLIC_SUPABASE_ANON_KEY=[INSERT SUPABASE PROJECT API ANON KEY]
   ```

   Both `NEXT_PUBLIC_SUPABASE_URL` and `NEXT_PUBLIC_SUPABASE_ANON_KEY` can be found in [your Supabase project's API settings](https://supabase.com/dashboard/project/_?showConnect=true)

5. You can now run the Next.js local development server:

   ```bash
   npm run dev
   ```

   The starter kit should now be running on [localhost:3000](http://localhost:3000/).

6. This template comes with the default shadcn/ui style initialized. If you instead want other ui.shadcn styles, delete `components.json` and [re-install shadcn/ui](https://ui.shadcn.com/docs/installation/next)

## License

*(Specify the license, if applicable)*

---

Feel free to contribute or suggest new features!


