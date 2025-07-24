# YouTube Channel Insights

A simple and clean Streamlit web app that displays public insights of any YouTube channel using its handle (e.g., `@ErrorMakesClever`). This app uses the **YouTube Data API v3** to fetch and show:

- Channel title and description
- Channel thumbnail
- Subscriber count
- Total views
- Total videos
- Link to the channel
----
## Tech Stack

- Python
- Streamlit
- Google API Client
- YouTube Data API v3
----
## ⚙️ How to Run This App Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/youtube-channel-insights.git
cd youtube-channel-insights
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

If `requirements.txt` doesn't exist yet, you can use:

```bash
pip install streamlit google-api-python-client
```

### 3. Add Your API Key

Replace the line in `app.py`:

```python
API_KEY = "YOUR_API_KEY"
```

with your actual YouTube Data API v3 key.

### 4. Run the App

```bash
streamlit run app.py
```

---

## How to Get YouTube Data API Key

1. Go to [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project or use an existing one.
3. Enable the **YouTube Data API v3**.
4. Go to **APIs & Services > Credentials**.
5. Create an **API key** and paste it in the app.

---

## Folder Structure

```
youtube-channel-insights/
├── app.py
├── README.md
└── requirements.txt
```

---

## Author

**Poorna Devi**  
Feel free to connect or contribute!
