# CoreS3 DMX Android Controller

This folder is ready for GitHub Pages.

## Deploy

1. Create a GitHub repository.
2. Push this project to the repository.
3. Open the repository on GitHub.
4. Go to `Settings` -> `Pages`.
5. Set `Source` to `Deploy from a branch`.
6. Select your branch, usually `main`.
7. Set the folder to `/docs`.
8. Save.

Your phone controller will be available at:

```text
https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/
```

## Update

When `outputs/android-controller.html` changes, copy it to:

```text
docs/index.html
```

Then commit and push. Refresh the page on the Android phone.

## BLE Target

The page connects to:

```text
CoreS3-DMX
```

It writes controller packets to the BLE UART RX characteristic:

```text
X=128,Y=128,D=255,R=255,G=80,B=0,W=0
```
