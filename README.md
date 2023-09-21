# probable-adventure

---

how to definitely logout the github in the local computer?

just run

```bash
git config --global user.name "Other name"
git config --global user.email "<Other email of account to login>"
```

It worked to me!


---

Testing GitHub CLI with `git` commands! It works.

<h1>It works!</h1>
<h1 style="font-size: 80px">Hoooray!</h1>

---

Another check-in. Does it work?

Yes, so I now have an checked way to commit from the right account:

 - First change the config (the `user.name` and `user.email` ones) to the right values (see the start of this file);
 - Then if you've lost or forgotten the Personal Access Token or you just don't have it, go to [Settings > Developer settings > Personal access tokens > Tokens (classic)](https://github.com/settings/tokens);
 - Press the "Generate new token" button and click "Generate new token (classic)";
 - Fill the "Note" input if you want;
 - Set Expiration. You can anyway regenerate the token everytime everywhere so if the token will expire at the date you need it you can regenerate it by going to the token's page, pressing the "Regenerate token" button and filling in all the values;
 - Select the necessary "Scopes". I usually select them all to not mess up too much;
 - Press the "Generate token" button in the bottom of the page;
 - Copy the token that you will see in the top of the page.

And you have to save your token somewhere if you plan to use it in further.

Then you can make some changes into the project, do necessary things. Then do `git push`, enter your email, press Enter and finally paste the token you copied.

**Bingo**, now you understand how to commit properly.
