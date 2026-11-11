# A Little World for Durga 🤍✨

An extraordinary, premium, aesthetic, deeply emotional birthday surprise website created especially for **Durga**. Built with React, TypeScript, Tailwind CSS, Framer Motion, Canvas Confetti, and bespoke Bubu & Dudu vector animations.

---

## 🌟 Highlights & Features

- **Magical Loading Screen**: Waving Bubu & Dudu, glowing progress bar, and personalized greeting introducing Durga to her world.
- **Hero Section**: Dreamy pastel skies, floating clouds, starlight, and an "Open Your Little World" heart transition.
- **Birthday Celebration**: Layered birthday cake with interactive candles (tap to blow out!), dancing Bubu & Dudu, and pastel confetti showers.
- **Bubu & Dudu Animation World**: All 10 dedicated storybook scenes:
  1. *A Little Blossom For You* (Bubu giving Dudu a flower)
  2. *Warm Affectionate Embrace* (Hugging tightly)
  3. *Walking Hand In Hand* (Holding hands on a stroll)
  4. *Resting on My Shoulder* (Dudu peacefully asleep)
  5. *The Birthday Surprise Gift* (Bubu presenting a wrapped gift)
  6. *Quiet Moments Under The Moon* (Sitting side by side on a hill)
  7. *Counting Starlight Wishes* (Gazing at the constellations)
  8. *Safe from the Rain* (Bubu tilting an umbrella over Dudu)
  9. *Holding Our Little White Heart* (Together holding a glowing 🤍)
  10. *The Forever Hug* (Warm comforting embrace)
- **Interactive Love Letter**: 3D envelope with a white ribbon and heart seal, featuring a rhythmic typewriter reveal of your personal letter.
- **Polaroid Memory Gallery**: 5 aesthetic floating polaroid cards with captions, lightboxes, and an in-browser photo uploader.
- **Surprise Gift Box**: 3D center gift box that bursts open with sparkles, confetti, and popping Bubu & Dudu characters.
- **Dreamy Night Sky**: Midnight sky with a glowing crater moon, starlight field, and interactive click-to-summon shooting stars.
- **Final Emotional Hug**: Warm message, "Send Me A Hug 🧸" button triggering full-screen floating 🤍 hearts and sparkles.
- **Background Music & Sound Engine**: Soothing romantic music-box melody with play/pause, volume slider, and sound effects.

---

## 🚀 1. Running the Website Locally

From the project root:

```bash
# 1. Navigate to the project directory
cd durga-birthday-world

# 2. Start the local development server
npm run dev
```

Open your browser at `http://localhost:5173` to explore Durga's universe!

---

## 📸 2. Replacing Personal Photographs

You have two easy options:

### Option A: Directly from the Website (Instant)
1. Run the website locally or open the deployed link.
2. Scroll to the **"Special Photo Memories ✨"** section.
3. Click the small **Camera / Upload icon** on any Polaroid card.
4. Select any photo from your phone or computer. The card will instantly display your real photo!

### Option B: Permanently in Code
1. Place your photos (e.g. `durga1.jpg`, `durga2.jpg`, etc.) into the `public/` directory.
2. Open [`src/components/MemoryGallery.tsx`](file:///C:/Users/navee/.gemini/antigravity/scratch/durga-birthday-world/src/components/MemoryGallery.tsx).
3. Update `defaultMemories` to reference `/durga1.jpg`, `/durga2.jpg`, etc.

---

## ✍️ 3. Editing Birthday Messages

All text is organized in clear, accessible components:
- **Hero Greeting**: [`src/components/HeroSection.tsx`](file:///C:/Users/navee/.gemini/antigravity/scratch/durga-birthday-world/src/components/HeroSection.tsx)
- **Birthday Wish**: [`src/components/BirthdaySection.tsx`](file:///C:/Users/navee/.gemini/antigravity/scratch/durga-birthday-world/src/components/BirthdaySection.tsx)
- **Love Letter Content**: Edit `LETTER_TEXT` in [`src/components/LoveLetter.tsx`](file:///C:/Users/navee/.gemini/antigravity/scratch/durga-birthday-world/src/components/LoveLetter.tsx)
- **Surprise Box Message**: [`src/components/GiftSurprise.tsx`](file:///C:/Users/navee/.gemini/antigravity/scratch/durga-birthday-world/src/components/GiftSurprise.tsx)
- **Night Sky Quotes**: [`src/components/NightSky.tsx`](file:///C:/Users/navee/.gemini/antigravity/scratch/durga-birthday-world/src/components/NightSky.tsx)
- **Final Hug Message**: [`src/components/FinalMessage.tsx`](file:///C:/Users/navee/.gemini/antigravity/scratch/durga-birthday-world/src/components/FinalMessage.tsx)

---

## 🎵 4. Adding or Customizing Background Music

The website comes with a **built-in procedural Web Audio music-box engine** playing gentle chords (Fmaj7 -> Cmaj7 -> Am7 -> G) so it plays reliably on every device with zero network lag or missing file errors.

To use your own MP3 file:
1. Place your audio file as `public/bg-music.mp3`.
2. In [`src/components/MusicPlayer.tsx`](file:///C:/Users/navee/.gemini/antigravity/scratch/durga-birthday-world/src/components/MusicPlayer.tsx), attach an `<audio src="/bg-music.mp3" loop />` element or let the built-in music engine play.

---

## ☁️ 5. Deploying on Vercel (Free & Fast)

Deploying to Vercel gives you a fast, permanent HTTPS link to share with Durga:

### Method 1: Using Vercel CLI (Quickest)
```bash
# 1. Install Vercel CLI globally (if not already installed)
npm install -g vercel

# 2. Inside the project folder, run:
vercel
```
Follow the 3 prompts (hit Enter to accept defaults). Vercel will build and deploy your site in ~30 seconds and output your live URL.

### Method 2: Via GitHub + Vercel Dashboard
1. Push this folder to a GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "A Little World for Durga 🤍"
   git branch -M main
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```
2. Go to [vercel.com](https://vercel.com) and log in.
3. Click **"Add New Project"** -> **"Import Git Repository"**.
4. Select the repository and click **Deploy**.

---

## 🔗 6. Getting a Shareable Public Link

Once deployed on Vercel:
1. You will receive a clean public URL like `https://durga-birthday-world.vercel.app`.
2. Test the link on your mobile phone to experience the smooth touch gestures.
3. Send the link to Durga with a sweet message:
   > *"Open this whenever you're ready... A little world made just for you 🤍✨"*
