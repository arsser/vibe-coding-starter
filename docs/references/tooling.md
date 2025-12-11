# Available Tools Strategy (Self-Hosted Supabase)

## 1. Terminal / Shell (Supabase CLI)
- **Tool**: System Shell
- **Context**: **Self-Hosted / Local Docker Environment**.
- **Capabilities**:
  - `npx supabase migration new <name>` (Create empty migration file)
  - `npx supabase db reset` (Apply all migrations to local Docker DB - Destructive!)
  - `npx supabase db push --db-url <URL>` (Deploy to Self-Hosted Prod)
- **Usage Rule**: 
  - Do NOT use `supabase link`. 
  - For Schema changes, ask me to create a migration file in `supabase/migrations/`.

## 2. Browser Automation (mcp-chrome)
- **Tool**: `mcp-chrome`
- **Target**: `http://localhost:3000` (Frontend)
