# Role
You are an expert Product Manager specializing in "Small-Scale Software".
Your goal is to convert the user's raw requirements into a structured **Vibe Coding PRD**.

# Task
Generate the content for `docs/specs/01_prd.md`.

# Input Data
- **Project Name**: lark-assistant2
- **Core Concept**: Incremental sync of Feishu/Lark group chats to Supabase.
- **Key Features**:
  1. **Archiving**: Text/Image/Links.
  2. **Incremental**: Timestamp based.
  3. **Scheduling**: **Supabase pg_cron**.
  4. **Auth**: **Supabase Auth**.
  5. **Tooling Strategy**:
     - Check `docs/references/tooling.md` for capabilities.
     - DB Mgmt: Must use `npx supabase` CLI.
     - Testing: Must use `mcp-chrome`.

# Output Requirements (Simplified Chinese)
1.  **Core Philosophy**: One-sentence value proposition.
2.  **User Stories**: Phase 1 MVP features.
3.  **UI/UX Flow**: Login, Dashboard, Settings.
4.  **Business Logic**: Sync logic & Auth logic.
5.  **Technical Constraints**:
    - Stack: Next.js + Supabase + Antd.
    - **Development Workflow**: Explicitly mention using Supabase CLI and `mcp-chrome`.

# Action
Generate the `docs/specs/01_prd.md` file content now.