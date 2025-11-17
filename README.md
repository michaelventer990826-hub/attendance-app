# Attendance App (Vite + React + Tailwind)

This project is pre-configured for Vite + React + Tailwind.  
Follow the instructions below to deploy without using a terminal.

## Option: Deploy via Vercel (no terminal)
1. Download the ZIP and extract the folder `attendance-app`.
2. Create a new GitHub repository (via github.com → New repository).
3. In your new repo, click **Add file → Upload files**, then drag the entire contents of the `attendance-app` folder (all files and folders) into the upload area. Commit the upload.
4. Go to https://vercel.com and log in.
5. Click **New Project → Import Git Repository**, choose the GitHub repo you just uploaded.
6. Vercel will auto-detect Vite. Use defaults:
   - Build command: `npm run build`
   - Output directory: `dist`
7. Click **Deploy**. When it's finished you'll get a public URL to share.

## Notes
- Data is stored in the browser's `localStorage` (so it's local to each device/browser).
- If you want shared data (so all teachers see the same attendance), I can add Firebase integration next.
