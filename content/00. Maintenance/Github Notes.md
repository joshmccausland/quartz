
Here's the update workflow. Whenever you've made changes in Obsidian and want to push them to the site, run these three commands in Terminal:

```
cp -r ~/Library/Mobile\ Documents/iCloud~md~obsidian/Documents/The\ Encyclopedia\ of\ Nila-Sagara/. ~/Documents/quartz/content/
```

```
git add .
git commit -m "update content"
git push origin v5:main
```

That's it. GitHub will automatically rebuild and deploy the site within a couple of minutes after the push.