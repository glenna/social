Being a part of the network
===========================

### Getting started

1. Fork the template repo at [RenderedMarkdownSocialNetwork/social](https://github.com/RenderedMarkdownSocialNetwork/social).
2. Update the README with your own details. Especially the **Friends**, **About me**, and maybe **Ads** sections are meant to set up by you. **Posts** are meant for your friends (see [Posting to a friends profile](#posting-to-a-friends-profile)).
3. There is no step 3.

You're now a part of the Rendered Markdown Social Network! :tada:


### Posting to a friends profile

Posting works by sending them a PR with your message as an edit to their profile.

```bash
# Add their account as a remote to your own existing repo
cd path/to/your/repo
git remote add my_friends_profile hgit@github.com:my_friends_github_username/social.git

# Checkout their master under a different branch name
git fetch
git checkout -b my_friends_master my_friends_profile/master
git pull my_friends_profile master

# [Make your post now]

# Push your changes to your own remote
git push origin my_friends_master

# [Go on GitHub and make your PR like normal :)]
```
