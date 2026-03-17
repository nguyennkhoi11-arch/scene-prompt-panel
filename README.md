# 🎬 Scene Prompt — AI Video Prompt Manager

A Chrome extension for AI video creators. Manage all your act/scene prompts in one clean side panel — works alongside Google Flow, Kling, Runway, Midjourney, and more.

---

## 📥 Installation

1. Download `scene-prompt.zip` from the link above
2. Unzip the file
3. Open Chrome → go to `chrome://extensions`
4. Enable **Developer mode** (top right toggle)
5. Click **"Load unpacked"**
6. Select the unzipped `scene-prompt` folder
7. Click the extension icon in Chrome toolbar → **Scene Prompt** appears as a side panel

---

## 📄 Tab 1: Scenes

### Supported File Formats

**Format 1 — Markdown (recommended):**
```
# ACT 17

## SCENE 1 — TITLE | 0s-7s

### IMAGE START FRAME
your prompt here...

### IMAGE END FRAME
your prompt here...

### VIDEO PROMPT
Video start: ...
Motion development: ...
Video end: ...
```

**Format 2 — Plain text:**
```
PHAN A - TOPIC SNAPSHOT
Topic: Do You Really Understand Income? — Act 17

PHAN C - SCENE PACKAGES

SCENE 1 - TITLE | 0s-7s

IMAGE START FRAME
your prompt here...

VIDEO PROMPT
your prompt here...
```

**Format 3 — Scenes only (no ACT header needed):**
```
## SCENE 1 — TITLE | 0s-7s

### IMAGE START FRAME
your prompt here...

### VIDEO PROMPT
your prompt here...
```

### How to Load Your File

**Option A — Open File:**
1. Click **"📂 Open File"** tab
2. Click the file zone
3. Select your `.txt` or `.md` file
4. Extension loads automatically

**Option B — Paste Text:**
1. Click **"📋 Paste"** tab
2. Paste your script content
3. Click **"▶ Load Data"**

### Using Scenes

- **Sidebar** — click any act to expand, click any scene to view
- **← →** buttons or arrow keys to navigate scenes
- **▶ header** — click to expand/collapse each prompt section
- **COPY** button — copies that section's prompt
- **COPY ALL** — copies all sections at once
- **⊞ Expand All** — expand or collapse all sections
- **Edit** — click inside any prompt box to edit directly

### 📁 Filename Helper

After rendering images in Flow, use the filename bar to quickly name your files:

1. Select the scene you just rendered
2. Click **START**, **END**, **VIDEO**, or any section button
3. Extension copies the filename: `ACT17-SC01-IMAGE-START-FRAME`
4. Press **F2** on your downloaded file → **Ctrl+V** → **Enter**

---

## ✅ Tab 2: Tracker

Track render progress across all your scenes.

- **✓ (green)** — mark scene as done
- **↺ (amber)** — mark scene as redo
- Click again to reset to pending
- Progress bar shows % complete
- **Reset All** — clears all tracker data
- Data is saved automatically — stays after closing Chrome

---

## 📚 Tab 3: Library

Save and reuse your best prompts.

1. Enter a **name/tag** for the prompt
2. Paste the **prompt content**
3. Click **"💾 Save to Library"**
4. Use **Search** to find saved prompts
5. Click **COPY** to copy any saved prompt
6. Click **✕** to delete

Library data is saved automatically in Chrome storage.

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `← →` or `↑ ↓` | Navigate between scenes |
| `A` | Copy all prompts |

---

## 🎯 Supported Platforms

Works with any AI video/image platform:

- Google Flow
- Kling AI
- Runway
- Midjourney
- Stable Diffusion
- ComfyUI
- Pika
- Hailuo

---

## ❓ FAQ

**Q: My file doesn't load — what's wrong?**
A: Make sure your file uses one of the supported formats above. The key requirements are `## SCENE` for scene headers and `###` for section headers (or ALL CAPS for plain text format).

**Q: Will my tracker/library data be lost if I update the extension?**
A: No — data is stored in Chrome's local storage and persists across updates.

**Q: Can I edit prompts directly in the panel?**
A: Yes! Click inside any prompt box and edit freely. Changes are temporary (not saved back to your file).

**Q: The timing `| 0s-7s` — is it required?**
A: No, timing is optional. `## SCENE 1 — TITLE` works fine without timing.

---

## 📬 Support

Have questions or suggestions? Reach out via Gumroad.
