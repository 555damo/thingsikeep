# Partner Guide — The Kept List

Two ways to make changes to the site:

---

## 1. Editing posts (add, change text, delete)

Go to: **thekeptlist.com/admin.html**

You'll need a GitHub token to save changes. Damiano will give you this — it's a password that lets the admin page write to the site.

**Paste it in once**, click Save, and you're connected. It stays saved in your browser.

### Adding a new post

1. Click **+ Add post**
2. Fill in the form:
   - **Date** — when you're adding it
   - **Category** — Music, Travel, Books, Object, Style, or Food
   - **Card type**:
     - *Text only* — just words, no image (most common)
     - *Colour swatch + text* — decorative coloured block above the text
     - *Photo + text* — a real photo above the text
     - *Pull quote* — a single quote in italic, good for a line from a book
   - **Background tone** — Default is fine; Deep is slightly darker
   - **Title line 1** — the main title
   - **Title line 2** — a subtitle, artist name, or place (shown in italic)
   - **Body text** — 2–4 sentences about why this is on the list
   - **External link** — if there's a shop or website to link to (optional)
3. Click **Save & publish**

The site updates in about **1 minute** after saving.

### Editing an existing post

Click **Edit** next to any post. Change whatever you like, click **Save & publish**.

### Deleting a post

Click **Edit**, then the red **Delete post** button at the bottom.

### Adding a photo

To use a real photo (instead of a coloured swatch):
1. Go to **github.com/555damo/thingsIkeep**
2. Navigate to the `img/` folder
3. Click **Add file → Upload files**
4. Upload your photo
5. Back in the admin, choose **Photo + text** as the card type
6. In the **Image path** field, type: `img/your-filename.jpg`

---

## 2. Design changes through Claude

For changing how the site *looks* — colours, fonts, layout, spacing — use Claude.

### One-time setup (Claude.ai Project)

1. Go to **claude.ai** and sign in
2. Click **Projects** in the left sidebar → **New project**
3. Name it: *The Kept List*
4. Click **Project instructions** and paste this:

---

*You are helping manage The Kept List (thekeptlist.com), a personal curation site. The site is a single HTML file called `index.html`, plus `detail.html` for long-form posts and `contact.html`.*

*When asked to make a design change:*
*1. Identify the exact CSS or HTML section to change*
*2. Show only the changed lines or block — not the whole file — unless the change is small enough to show in full*
*3. Explain in plain English what to do with the code*
*4. After showing the code, remind me to go to github.com/555damo/thingsIkeep, navigate to the file, click the pencil icon to edit, paste in the changes, and click Commit changes*

*Keep the existing design — terracotta accent, Cormorant Garamond serif for headings, DM Sans for body, parchment/cream backgrounds. Do not suggest new sections or features unless asked.*

---

5. Upload the files: click **Add content → Files** and upload `index.html`, `detail.html`, and `contact.html` (Damiano can give you these, or download them from github.com/555damo/thingsIkeep)

### Making a design change

Just describe what you want in plain English. Examples:

- *"Make the site title slightly smaller"*
- *"Change the terracotta colour to a dusty rose"*
- *"Make the card note text a bit bigger and easier to read"*
- *"Add more space between the cards"*

Claude will show you the code to change. Then:

1. Go to **github.com/555damo/thingsIkeep**
2. Find the file (usually `index.html`)
3. Click the **pencil icon** (Edit)
4. Find the section and paste in Claude's change
5. Click **Commit changes** (green button)
6. The site updates in about 1 minute

### Tips

- If Claude's response is confusing, just say: *"Can you explain that more simply?"* or *"Show me exactly what to copy and paste"*
- If a change doesn't look right, take a screenshot and paste it into the Claude chat: *"This doesn't look right — can you fix it?"*
- You don't need to understand the code. Just copy and paste what Claude gives you.

---

## Quick reference

| Task | Where |
|---|---|
| Add / edit / delete posts | thekeptlist.com/admin.html |
| Change the design | claude.ai → The Kept List project |
| Upload photos | github.com/555damo/thingsIkeep → img/ folder |
| View the live site | thekeptlist.com |
