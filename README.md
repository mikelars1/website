# Michael Larson — Personal Website

A simple four-page website built with plain HTML and CSS. No special software needed:
any text editor works (VS Code is free and recommended — https://code.visualstudio.com).

## What's in the folder

| File | What it is |
|---|---|
| `index.html` | **Home** page (must keep this exact name — it's the page people see first) |
| `resume.html` | **Resume** page |
| `projects.html` | **Projects** page |
| `about.html` | **About Me** page (golf, travel, skiing) |
| `style.css` | Colors, fonts and layout for **all** pages |
| `images/` | Your photos |

## Before you submit — your to-do list

1. **Replace the 4 photos.** Put your own photos in the `images` folder using the *exact same names*:
   `profile.jpg` (a headshot), `golf.jpg`, `travel.jpg`, `ski.jpg`.
   The assignment requires at least three images **you created yourself**, so use your own photos.
2. **Fill in the yellow highlights.** Open each page in your browser — anything highlighted yellow
   needs your real info (school name, graduation date, job dates, business names, email, LinkedIn,
   photo captions, and one class project). After editing, delete `class="edit-me"` from that spot
   so the highlight goes away. Search each file for `edit-me` to make sure you got them all.
3. **Read every page out loud** and change anything that doesn't sound like you.
4. **Never add** your phone number, home address or date of birth.

## How to edit

- **Preview:** double-click any `.html` file to open it in your browser. After saving a change, refresh the browser.
- **Change text:** find the words in the `.html` file and type over them. Text sits between tags like
  `<p>this is a paragraph</p>` or `<h2>this is a heading</h2>`. Don't delete the `< >` tags.
- **Add a job to the resume:** copy an entire `<div class="job"> ... </div>` block and paste it below, then edit.
- **Add a skill:** copy a line like `<li>Teamwork</li>` and change the word.
- **Change colors:** open `style.css` and edit the color codes at the top (section 1).
- **Notes in gray** that look like `<!-- like this -->` are comments. They explain the code and never show on the site.

## How to put it online for free (GitHub Pages, about 10 minutes)

1. Go to https://github.com and create a free account.
2. Click the **+** in the top right → **New repository**.
   Name it `yourusername.github.io` (replace with your actual GitHub username), set it to **Public**, and click **Create repository**.
3. On the next page click **uploading an existing file**. Drag in **everything inside** this folder
   (the four `.html` files, `style.css`, and the `images` folder). Click **Commit changes**.
4. Go to the repository's **Settings** → **Pages**. Under "Branch," choose `main` and `/ (root)`, then **Save**.
5. Wait a minute or two, then visit `https://yourusername.github.io`. That's the link you submit.
6. **Test it:** open the link in a private/incognito window or send it to a friend to confirm anyone can see it.

**To update the site later:** open the repository on GitHub, click **Add file → Upload files**, drag in the
changed files (they replace the old ones), and click **Commit changes**. The live site updates within a minute or two.

*Easier alternative:* https://app.netlify.com/drop lets you drag the whole folder onto the page and get a link
instantly. Create a free account so the site stays up.
