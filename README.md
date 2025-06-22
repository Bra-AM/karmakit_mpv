# KarmaKit - Functional & Beautiful MVP

**Design & Logic**:
- **Theme**: Soft gradients and accent colors, Poppins font, modern cards with animations.
- **Pages**:
  - `index.html`: Home deck with Pass/Like/Comment. Uses modal for comments.
  - `submit.html`: Add ideas (+5 karma).
  - `profile.html`: Set user & company; view karma & feedback stats.
- **Data**: Stored in `localStorage`.
  - `companies`: Array of idea objects with feedback counts.
  - `profile`: User info.
  - `karma`: Total karma points.
- **Interactions**:
  - Pass = +1, Like = +2, Comment = +3, Submit = +5.
  - Smooth fade-in card transitions.
  - Responsive design.

**Deployment**:
Host these files on any static server (GitHub Pages, Netlify).

## Files
- `index.html`
- `submit.html`
- `profile.html`
- `style.css`
- `karmakit-logo.png`
