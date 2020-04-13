# email-generator
Markdown to HTML Email for Open-Source at Illinois

Instructions:
1. Clone the repository and `cd` into the repo.
2. Run `bundle install`.
3. Add new emails to `_posts/` with the proper content and filename `YYYY-MM-DD.md`. The proper Markdown content is this:  
```
---
layout: email
subject: Your Subject Here
---
Your Content Here...
```  
 See `2020-04-12.md` to example formatting.

4. Run `bundle exec jekyll build`. You may run `jekyll build` after the first conversion.
5. Done. Email is located in `_site/YYYY-MM-DD/`.
