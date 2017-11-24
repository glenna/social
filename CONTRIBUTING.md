Being a part of the network
===========================

### Getting started

1. Fork the template repo at [RenderedMarkdownSocialNetwork/social](https://github.com/RenderedMarkdownSocialNetwork/social).
2. Update the README with your own details. Especially the **Friends**, **About me**, and maybe **Ads** sections are meant to set up by you. **Posts** are meant for your friends (see [Posting](#posting)).
3. There is no step 3.

You're now a part of the Rendered Markdown Social Network! :tada:


### Posting

```bash
git remote add my_friend https://github.com/my_friends_github_username/social
git fetch
git checkout -b my_friend my_friend/master
git pull my_friend master
# make your post now
git push origin my_friend
# then go on github and make your PR like normal :)
```
