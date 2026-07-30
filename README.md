# 🛬 Abri Landing Pages

The **public delivery surface** for advertorials. Pages are written by Abri Brain /
ABRi-Qwe CMS and land here to get a real URL that ads can point at.

**Live:** https://adbitrush.github.io/landing-pages/

```
index.html          the little index page
lp/<slug>/          one advertorial per folder — the slug IS the ad's destination URL
```

Deploy = `git push`. GitHub Pages serves `main` and goes live in about a minute.
There is no build step: what's in the repo is what's served.

## Two rules

1. **Everything here is public and indexable.** That's the point — but it means no
   client names, no internal numbers, no throwaway test copy.
2. **Never rename or delete a live slug.** The campaign keeps spending into a 404
   and nothing here will tell you. Add new slugs; retire old ones only after the
   campaign is off.

Generate a new page from **ABRi-Qwe CMS → `/landing`** (`:8772`, one click from
ABRI ONE's card). See `HANDOFF.md` for the operational detail and `UPGRADES.md` for
the request inbox.
