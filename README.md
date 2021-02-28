

git checkout --Orphan assets
git reset --hard
cp /path/to/viaje.jpg .
git add .
git commit -m 'Added cat picture'
git Push -u Origin assets
git rev-parse HEAD  # Print the SHA, which is needed below.
