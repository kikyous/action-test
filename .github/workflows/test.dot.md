{{~it.context.payload.commits :commit}}
[✅ {{=commit.message}}]({{=commit.url}})
{{~}}
> commiter: {{=it.context.payload.head_commit.author.name}}
> email: {{=it.context.payload.head_commit.author.email}}
> test1: chen