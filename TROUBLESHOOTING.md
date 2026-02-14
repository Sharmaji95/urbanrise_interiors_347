# Troubleshooting Vercel Deployment

If your changes are not showing up on Vercel, follow these steps to find the issue.

## 1. Check if Vercel Built the New Code
1.  Go to your [Vercel Dashboard](https://vercel.com/dashboard).
2.  Click on your **Urbanrise** project.
3.  Click on the **"Deployments"** tab at the top.
4.  Look at the top item in the list.
    *   **Does it say "Add FAQ section..."?** (This is the commit message I sent).
    *   **Status**: Does it say **"Ready"** (Green circle)?

### If you DO see the new commit and it says "Ready":
*   **The issue is likely your browser cache.**
*   Try opening your website in an **Incognito Window** (Private Mode).
*   Or do a **Hard Refresh**:
    *   **Mac**: Press `Command + Shift + R`
    *   **Windows**: Press `Ctrl + F5`

### If you DO NOT see the new commit:
*   Vercel might not be connected to the correct repository.
*   Go to **Settings** > **Git** in Vercel.
*   Check which repository is connected. Is it `urbanrise_interiors_347` or the `3471` version?
*   We updated **both**, so it should work, but ensure it says "Connected to GitHub".

## 2. Check Build Logs (If Status is Error)
If the deployment status is **"Error"** (Red circle):
1.  Click on that deployment.
2.  Look at the "Build Logs".
3.  Copy and paste any error messages here so I can fix them.
