# Varun's Movie Choice - Cloud Edition

## 1. Create the database
Open your Supabase project:
https://psjomezccarhxvfuijtx.supabase.co

Go to SQL Editor, paste the complete contents of `supabase_schema.sql`, and run it.

## 2. Configure the app
`supabase-config.js` is already configured for your project reference and publishable key.

## 3. What this architecture provides
- Supabase Auth
- Cloud PostgreSQL movie records
- Owner-only Row Level Security
- Movie watch history
- Collections
- Custom people/taxonomy
- Signature-photo storage
- Cross-device synchronization

## 4. Important security note
The publishable key is designed for browser use. Never put a Supabase secret/service_role key in this project.

## 5. Hosting
The frontend can be hosted free on Cloudflare Pages or GitHub Pages.
After deployment, add the deployed domain to Supabase Authentication URL configuration.
