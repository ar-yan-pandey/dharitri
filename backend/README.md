# Dharitri Backend

This directory contains the Supabase backend configuration and database migrations for Project Dharitri.

## Structure

- `migrations/` - Database migration files
- `functions/` - Supabase Edge Functions
- `types/` - TypeScript type definitions for the database schema
- `seed/` - Database seed data
- `config/` - Backend configuration files

## Setup

1. Install Supabase CLI:
   ```bash
   npm install -g supabase-cli
   ```

2. Start local Supabase:
   ```bash
   supabase start
   ```

3. Run migrations:
   ```bash
   supabase db reset
   ```

4. Deploy:
   ```bash
   supabase db push
   ```
