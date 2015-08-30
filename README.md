# foo
sample code for a blog post


Idea: [callbacks, promises, generators, tasks].forEach(implementScraper).

implementScraper:
 - should run on client or server
 - given a URL, xhr it, scrape the main content, extract keywords.
 - optional: store output in a relational DB (client or server)
 - optional: also store output in a full-text index (client or server)

todos:
- [ ] figure out xhr, scrape, keyword extract as a node module using callbacks
- [ ] use browserify to get this running in the browser
- [ ] rewrite using promises
- [ ] rewrite using generators
- [ ] rewrite using tasks (task.js)
- [ ] optional: relational DB storage
- [ ] optional: full-text indexing
