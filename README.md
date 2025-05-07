# Sentiment-Analysis-Using-Reddit-API
## _Note: Google Colab is used in this project_
### 1. Reddit API Setup
To create an app in the Reddit Developer Portal and obtain your API key (client ID and client secret), follow these steps:
1. Go to [https://www.reddit.com/prefs/apps](https://www.reddit.com/prefs/apps)
2. Scroll to the bottom and click **"Create App"** or **"Create Another App"**
3. Choose **Script** as app type (for personal use)
4. Fill in:
   - **Name**: Your app name
   - **Redirect URI**: `http://localhost:`
5. Click **Create app**

Save:
- **Client ID**: *(found under your app name)*
- **Client Secret**: *(found in app details)*

### 2. Clone This Repository
```bash
git clone https://github.com/Varun-3000/Sentiment-Analysis-Using-Reddit-API.git
cd Sentiment-Analysis-Using-Reddit-API.git
```
### 3. Set Up config.py

Create a config.py file in the root directory:

```python
client_id = "your_client_id"
client_secret = "your_client_secret"
user_agent = "your_app_user_agent"
```
### 4. Install Dependencies

```
pip install -r requirements.txt
```
