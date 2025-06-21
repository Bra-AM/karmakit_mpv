# KarmaKit Functional MVP

**Structure & Logic**:
- Data model stored in localStorage:  
  - `companies`: array of objects with `id`, `name`, `logo`, `idea`, `link`, `likes`, `comments`.  
  - `profile`: object with `user`, `company`.  
  - `karma`: integer total karma.
- **Pages**:  
  - `index.html`: main feedback deck with Pass/Like/Comment.  
  - `submit.html`: form to add new ideas (+5 karma).  
  - `profile.html`: set personal info; view total karma, and feedback counts on your idea.
- **Interactions**:  
  - Pass ("Maybe Later") = +1 karma.  
  - Like ("Love This!") = +2 karma and increments company likes.  
  - Comment = +3 karma and adds comment to company.  
- Each action persists updates and cycles through deck.

**How to run**:
1. Host these files on a static server (GitHub Pages, Netlify, Vercel).  
2. Visit `index.html` to start.

## Files
- `index.html`  
- `submit.html`  
- `profile.html`  
- `style.css`  
- `karmakit-logo.png`  

Built with ❤️ for SpurHacks 2025.
