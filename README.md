# 🧨 TIFU Tales

Welcome to **TIFU Tales** — a project that brings the internet’s most hilarious and awkward "Today I F*cked Up" stories to life. Whether you're building a YouTube narration channel, a Reddit story bot, or an archive of epic fails, this repo has everything you need to get started.

## 📚 About

**TIFU Tales** scrapes, organizes, and formats the best user-submitted TIFU stories (primarily from Reddit) for use in video content, podcasts, or other storytelling mediums.

## 🔧 Features

- 🔍 Reddit story scraping (with PRAW or Pushshift)
- 📝 Auto-formatting for narration scripts
- 📊 Metadata tagging (NSFW, length, tags)
- 🎙️ Optional text-to-speech integration
- 📦 Export to .txt, .srt, or video overlays

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tifu-tales.git
   cd tifu-tales
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure your Reddit API keys in `.env`

4. Run the script:
   ```bash
   python main.py
   ```

## 📂 Directory Structure

```
tifu-tales/
│
├── data/                # Raw and formatted stories
├── scripts/             # Scrapers, processors, and utilities
├── assets/              # Images, logos, branding
├── README.md
└── requirements.txt
```

## 🧠 Credits

Inspired by the TIFU subreddit and the art of storytelling. Made with regret (and laughter).
   - https://medium.com/@tifutales
   - https://x.com/TIFUTales
   - https://www.youtube.com/@TIFUTales

## 📜 License

MIT License. Use it, remix it, just don’t upload your own TIFU here 😉.
