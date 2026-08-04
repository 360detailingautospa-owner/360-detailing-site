360 Mobile Detailing website with secure admin login

FILES
- index.html — your website with an Admin link in the footer
- admin.html — login and dashboard page
- supabase-config.js — paste your Supabase project URL and anon key here
- supabase-setup.sql — run this inside the Supabase SQL Editor

IMPORTANT
GitHub Pages cannot safely protect a password by itself. This package uses Supabase Authentication.
Do not put your actual password in any HTML or JavaScript file.

SETUP
1. Create a free Supabase project.
2. In Authentication > Users, create your admin user with your email and password.
3. Open Project Settings > API.
4. Copy the Project URL and anon/public key into supabase-config.js.
5. Open the Supabase SQL Editor and run supabase-setup.sql.
6. Upload index.html, admin.html, supabase-config.js, and the existing assets folder to the same GitHub repository.
7. Visit https://your-domain.com/admin.html and sign in.

The dashboard is prepared to read quote requests from the quote_requests table.
Your current website contact form still opens the visitor's email app. Connecting that form directly to Supabase is a separate step.
