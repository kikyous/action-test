<% context.payload.commits.forEach(function(c){ -%>
[✅ <%= c.message %>](<%= c.url %>)
<% }) -%>
> commiter: <%= context.payload.head_commit.author.name %>
> email: <%= context.payload.head_commit.author.email %>
