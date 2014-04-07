lashford.info
=============

# Static profile-site hosted on Github.
For a project site like this, the files must live on a branch called `gh-pages`

You can make the `gh-pages` the main branch and delete master if needed witth the following command,

```
> git push origin :master
```

# Custom domain

Add the following `A Record`'s to your DNS Manager

@	 192.30.252.153	
@	 192.30.252.154

Then add a CNAME entry for the `www` redirect.

www lashford.github.io

# CNAME file in repo
Create a file called `CNAME` case *does* matter and add you domain name to it:
```
lashford.info
```

