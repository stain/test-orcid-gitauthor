Experiment: Is it possible to use [ORCID](https://orcid.org/) in the git commit author log, rather than a fluctuating and emantically unresolvable email address?


# Recommended


```
git config --global user.name http://orcid.org/0000-0001-9842-9718
git config --global user.email stian@soiland-reyes.com
```

If the email address is recognized, GitHub will show it like 'your' user, but will replace your ORCID with your user name: 

https://github.com/stain/test-orcid-gitauthor/commit/862b6a724ee2e10fc2a02bfb179392ee6ed11387

> @stain committed 9 minutes ago

If the email address is not recognized, then the author field from the commit (aka your ORCID) will show, but won't be clickable:

https://github.com/stain/test-orcid-gitauthor/commit/84d1dbde9fcbf4dbfd855ea546f4a6e62d5eeb32

> http://orcid.org/0000-0001-9842-9718  committed 5 minutes ago Unified Split

# Use ORCID as your "homepage"

You should set your ORCID (with `http://` prefix) as the **URL** in the
GitHub [Public Profile](https://github.com/settings/profile)


