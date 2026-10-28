# Ryanair Virtual

An independent virtual airline website for Microsoft Flight Simulator 2020 and 2024.

## Features
- Responsive landing page and destination cards
- Virtual route search, example timetable, flight details, and status lookup
- Supabase email/password authentication
- Pilot profile and flight-logbook read view
- Unofficial virtual airline disclosure

## Stack
- Static HTML, CSS and JavaScript
- Supabase Auth + Postgres
- Vercel static deployment

## Configuration
The Supabase project URL and **publishable** client key are set in `app.js`. The publishable key is safe to use in a browser; never expose a Supabase secret/service-role key in frontend code.

Database tables and row-level security policies are created in the connected Supabase project. In Supabase Authentication settings, configure the site URL and allowed redirect URLs after the Vercel deployment URL is available. If email confirmation is enabled, new users must confirm their email before signing in.

## Important
This is a fan-made virtual airline for flight simulation. It is not affiliated with or endorsed by Ryanair DAC. It does not sell real airline tickets. All displayed flight numbers, schedules, and route information are illustrative virtual operations. Brand logos, proprietary site layout, and official Ryanair images are not copied; replace the stock aviation imagery with assets you own or have permission to use.
