Screenshot evidence for hamedgitty/bloks#46.

before.png: Bloks 1.7.0 as shipped, react 19.3.0 with react-dom 19.2.8.
  React throws invariant #527 before first paint. #root has 0 children.

after.png: the same bundle rebuilt with both packages on 19.3.0.
  The app boots. #root has 2 children and 10,357 characters of markup.

Both captured in headless Chromium at 1280x800 against the built bundle.
This branch exists only to host the two images so they render in the pull
request body. It is not proposed for merge.
