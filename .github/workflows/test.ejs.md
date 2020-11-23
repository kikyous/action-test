<% context.payload.commits.forEach(function(c){ -%>
[✅ <%= c.message %>](<%= c.url %>)
<% }) -%>
> diff: [view](<%= context.payload.compare %>)
> commiter: <%= context.payload.head_commit.author.name %>