Solution:
As you initialized your repository using git init, git does not know which server to contact when you use git push.

Therefore, we’ll have to add a server (called remote in git terminology) to the repository:

solve-git-fatal-no-configured-push-destination.txt📋 Copy to clipboard⇓ Download
git remote add origin git@github.com:yourusername/yourrepository.git
Remember to replace git@github.com:yourusername/yourrepository.git with the correct URL for your repository. Valid example URLs include:

https://github.com/ulikoehler/UliEngineering.git
git@github.com:ulikoehler/UliEngineering.git
This adds a server (remote add) named origin with the URL git@github.com:yourusername/yourrepository.git.

The URL (last argument) depends on the server you use, for GitHub, you can get the URL (HTTPS or SSH, both will work) by clicking the green Clone or Download button.
