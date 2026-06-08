# Personal QR Contact Pages

This repo is set up for four separate GitHub Pages links, so you can create four different QR codes from one repo.

## Pages

After GitHub Pages is enabled, use one URL per QR code:

```text
https://YOUR-USERNAME.github.io/YOUR-REPO/ahmad/
https://YOUR-USERNAME.github.io/YOUR-REPO/friend-1/
https://YOUR-USERNAME.github.io/YOUR-REPO/friend-2/
https://YOUR-USERNAME.github.io/YOUR-REPO/friend-3/
```

Each folder has its own `index.html`, so each QR code opens a different contact page.

## Edit Details

Update the matching file for each person:

```text
ahmad/index.html
friend-1/index.html
friend-2/index.html
friend-3/index.html
```

Replace the name, phone number, email, and LinkedIn values inside that person's `index.html`.

## Add Photos

Each folder can have its own photo named:

```text
photo.jpg
```

Use this photo structure:

```text
ahmad/photo.jpg
friend-1/photo.jpg
friend-2/photo.jpg
friend-3/photo.jpg
```

Ahmad's photo has already been added. Add the other friend photos later using the same filename inside each friend folder.

## Publish on GitHub Pages

1. Push this repo to GitHub.
2. Open the repo on GitHub.
3. Go to `Settings`.
4. Open `Pages`.
5. Set the source to the main branch and root folder.
6. Generate four QR codes, one for each folder URL.
