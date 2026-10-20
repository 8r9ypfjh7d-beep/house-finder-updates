# House Finder updates

Automatic code updates for the House Finder Windows app. The installed app
reads `manifest.json` here, downloads the bundle it names, checks its
SHA-256, and switches to it (falling back to the last working version if the
new one does not start). Only the app's code is published here.
