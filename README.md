# MIAN X NIAZI Downloader

Mobile-first, single-page GitHub Pages site for public TikTok, Instagram and YouTube links.

## Files
- `index.html` — complete website and client-side API calls.
- `assets/niazi-banner.svg` — local fallback banner if the external image host is unavailable.

## Upload to GitHub Pages (PC or mobile browser)
1. Open https://github.com and sign in.
2. Click **+** → **New repository**.
3. Repository name: `niazi-video-downloader` (or any name you prefer).
4. Select **Public**, then click **Create repository**.
5. Click **Add file** → **Upload files**.
6. Upload `index.html`, the `assets` folder (including `niazi-banner.svg`), and `README.md`. Keep `index.html` at the repository root, not inside another folder.
7. Click **Commit changes**.
8. Open repository **Settings** → **Pages**.
9. Under **Build and deployment**, choose **Deploy from a branch**.
10. Choose branch **main** and folder **/(root)**, then click **Save**.
11. Wait a minute or two and refresh the Pages screen. Open the URL GitHub displays.

## Important download limitations
This is a static GitHub Pages website. It cannot proxy/stream video files through a server. The site first tries a browser Blob download; if a provider blocks cross-origin requests (CORS), it opens the provider's direct media URL instead. Some providers may show/play the video rather than automatically save it. For reliable forced downloads, a server-side download endpoint is required and GitHub Pages alone cannot host that backend.

The third-party APIs used by this demo can change, rate-limit, or stop working. The website does not bypass private videos, logins, DRM, or access controls. Download only content you own or have permission to save, and follow the platforms' terms.
