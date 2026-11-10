# DrHawarKhoshnaw

Native iOS and Android starter app built with Expo + React Native, with Supabase client prepared.

## Current screens
- Home
- About Me
- Clinic
- Ask Doctor
- Activities

## Important security
- Never put a Supabase `sb_secret_...` key in this app, GitHub, or an `EXPO_PUBLIC_` variable.
- The secret key previously shared in chat should be rotated/revoked in Supabase.
- Use only the Supabase project URL and a publishable key in the mobile app.
- Enable Row Level Security (RLS) before storing patient or personal information. Do not collect identifiable patient health information until privacy, consent, retention and access controls are designed and reviewed.

## Cloud-first next steps (no local Node.js or VS Code required)
1. Upload the contents of this project folder to the GitHub repository `HawarKhoshnaw/DrHawarKhoshnaw` using GitHub's web interface.
2. Create/sign in to an Expo account at https://expo.dev/.
3. Use Expo's cloud build service (EAS Build) to build Android and iOS binaries.
4. Add the Supabase project URL and publishable key as EAS environment variables when database features are ready.
5. Configure Apple Developer and Google Play Console accounts for store submission.

This is a starter UI, not yet connected to live appointment or question submission. Those features require database schema, RLS policies, consent text and tested server-side workflows.
