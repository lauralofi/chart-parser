# Astro-Seek Birth Chart Parser

This lightweight web tool helps users of the **Notion Astrology Template** copy their birth chart details directly from [Astro-Seek's free calculator](https://horoscopes.astro-seek.com/calculate-birth-chart-horoscope-online/) into a Notion-friendly format.

### ✨ What It Does
- Accepts the "AI-ChatGPT Export" section from Astro-Seek
- Parses planet positions, signs, degrees, house numbers, and motion
- Outputs a clean table for copy/paste into your Notion template

### 🧠 How to Use
1. Visit [Astro-Seek Birth Chart Calculator](https://horoscopes.astro-seek.com/calculate-birth-chart-horoscope-online/)
2. Scroll to the section titled **"AI-ChatGPT Astrology Data Export"**
3. Copy that section and paste it into the textarea on this tool
4. Click **Parse My Birth Chart**
5. Copy the table results into your Notion database `Birth Chart: Planetary Positions`

### 🪐 Notion Template Compatibility
This parser is designed to work with templates where the `Planet`, `Sign`, and `House` properties are:
- Relational (linked by name/title)
- Degree is stored as a text field (e.g., `27°44′`)
- Motion is stored as a select field (`direct` or `retro`)

### 💾 Hosting Instructions
1. Upload `astro_seek_parser.html` and `LICENSE` to a public GitHub repo
2. Go to **Settings > Pages**, choose `main` branch and `/root` folder
3. Your GitHub Pages link will be: `https://yourusername.github.io/your-repo-name`

### 📝 License
MIT © 2025 [Laura McGuinn](https://lauramcguinn.com)