# KodNest Premium Build System
**Philosophy: Calm, Intentional, Coherent, Confident**

## Core Design Principles
- **No Animations**: Transitions [150-200ms] only. No bounce, no noise.
- **Color Discipline**: Maximum 4 colors across the entire system. 
  - Off-white background: `#F7F6F3`
  - Text: `#111111`
  - Accent: `#8B0000` (Deep Red)
  - Success: Muted Green
  - Warning: Muted Amber

- **Typography**:
  - Headings: Serif (`Fraunces` or `Playfair Display`), large, generous character spacing.
  - Body: Sans-serif (`Inter`), 17px, line-height 1.7. Max width 720px for text blocks.

- **Spacing**: 
  - 8px, 16px, 24px, 40px, 64px. 
  - **Whitespace is part of the design**.

## Global Layout Structure
Every page should follow the hierarchical flow:
1. **Top Bar**: Fixed header for project identity and progress.
2. **Context Header**: Direct, large serif headline and purpose subtext.
3. **Primary Workspace (70%)**: Main product interaction area.
4. **Secondary Panel (30%)**: Guidance, prompts, and auxiliary actions.
5. **Proof Footer**: Persistent bottom section with required checklist.

## Component Specifications
- **Cards**: Subtle border (`rgba(17, 17, 17, 0.1)`), no drop shadows.
- **Buttons**:
  - Primary: Deep Red solid.
  - Secondary: Deep Red outline.
- **Inputs**: Clean borders, no heavy shadows.

## Error & Empty States
- **Errors**: Explain the issue + provide the fix. Never blame the user.
- **Empty States**: Provide the next action. Never feel like a dead end.
