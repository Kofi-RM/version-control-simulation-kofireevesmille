To do this project I initial created a blank index.html file and commited that to main. I then checked out to feature/header and created a header in index.html. I then commited that change.

I then checked out to main and created a new branch called feature/footer. I created a header and footer in this branch and commited the change.

I then switched back to feature/header and added a footer, hoping to simulate a merge conflict. When I merged this back to main I did encounter a conflict.

To fix this conflict I click merge editor or something similar. It showed both commmits separately and had a blank space to write in. I copied the header I wanted from feature/header and the footer I wanted from feature/footer and then clicked merge.

Branches where created with "git checkout -b [branch-name]"

And after being created checked out to with "git checkout [branch-name]