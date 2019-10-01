Green dots!
===========

Write on your GitHub profile!

This takes a message, encodes it to a simple bitmap font, and generates a bunch of git commits in the past. To make your profile look like this:

![Example profile](example.png)

Use greendots.py to generate a shell script with your commits in.

```bash
$ mkdir ../my-repo
$ ./greendots.py "Yo yo!" > ../my-repo/make-my-repo.sh
```

You only have 6 characters that can be displayed. Make it count.

Then run that script to create a repo. This will generate lots of commits in your new repo.

```bash
$ cd ../my-repo
$ bash make-my-repo.sh
```

Now create your repo on github.com and push it. It'll take a minute or two, but you should now see your message in your profile at github.com/YOURUSERNAME.


Cleaning up
-----------

To remove this nonsense, just delete your repo from github.Yes,you heard it right


Disclaimer
----------

## Hactoberfest
By vishal kumar
