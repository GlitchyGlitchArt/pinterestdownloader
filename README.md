Pinterest Image & Video Downloader (Python Script)
==================================================

This is a Python script that allows you to **download high-resolution images and videos from Pinterest**. It's perfect for developers or power users who want to fetch Pinterest media directly using a script.

🔥 Live Tool Available
----------------------

Prefer a web-based tool? Use our online Pinterest downloader at:

👉 [**PinterestDownloader.onl**](https://pinterestdownloader.onl)  

No setup required – works instantly in your browser!

* * *

📜 Features
-----------

*   Supports both **Pinterest video and image downloads**.
*   Handles both standard and `pin.it` short URLs.
*   Fetches the **highest available resolution** automatically.
*   Built for both **CLI usage and web integration**.

⚙️ Requirements
---------------

*   Python 3.6+
*   `requests` – for HTTP requests
*   `beautifulsoup4` – for HTML parsing

pip install requests beautifulsoup4

🚀 How to Use
-------------

1.  Clone or download this repository.
2.  Install the required dependencies if you haven't already.
3.  Run the script from your terminal:

    python main.py <Pinterest URL>

Example:

    python main.py https://www.pinterest.com/pin/123456789/

### ✔ Supported URL Types

*   `https://www.pinterest.com/pin/...`
*   `https://pin.it/...` (automatically expands to original pin)

🧠 How It Works
---------------

*   Parses the Pinterest page HTML using BeautifulSoup.
*   Detects embedded video or image tags and fetches the source link.
*   Rewrites video links to directly downloadable .mp4 URLs when possible.
*   If the pin contains an image, extracts the original highest-res image.

🔐 Legal Notice
---------------

This tool is intended for educational and personal use only. Download media responsibly. All rights belong to the original content creators and Pinterest.

* * *

🌐 Visit Our Site
-----------------

Want a smoother, no-code experience? Use our fast and free downloader:

👉 [**https://pinterestdownloader.onl**](https://pinterestdownloader.onl)

No installation needed. Paste your link and download instantly!

📩 Feedback
-----------

Found a bug or want a new feature? Feel free to open an issue or contribute via pull requests.
