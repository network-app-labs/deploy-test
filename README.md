# Deployment test

A tiny, public static webpage for practicing the shared edit → commit → push → deploy workflow. It contains no app implementation or personal contact data.

## Edit in Cursor

1. Clone this repository onto your computer.
2. In Cursor, choose **File → Open Folder** and open the cloned folder.
3. Edit the headline in `index.html` and save. Open the file in a browser to preview it locally.
4. In Cursor's Source Control panel, inspect the diff, stage the file, enter a commit message, and commit.
5. Push or sync the commit to GitHub. If prompted, sign in to GitHub in the browser.

GitHub Pages is configured to publish the root of `main`. Each push to `main` starts a new deployment. Watch the **Actions** tab and refresh the live URL after the deployment succeeds.

For changes you want a teammate to review, create a branch, push it, and open a pull request into `main`. Merging the pull request triggers the deployment.

## What this proves

This tests publishing a static webpage from GitHub. Cursor is an editor; it does not host the page. This workflow does not build, sign, or distribute a phone app. Flutter or another mobile framework can be added to the separate app repository later, with its own mobile build and release process.
