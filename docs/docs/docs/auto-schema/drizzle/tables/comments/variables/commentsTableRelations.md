[Admin Docs](/)

***

# Variable: commentsTableRelations

> `const` **commentsTableRelations**: `Relations`\<`"comments"`, \{ `creator`: `One`\<`"users"`, `false`\>; `post`: `One`\<`"posts"`, `true`\>; `votesWhereComment`: `Many`\<`"comment_votes"`\>; \}\>

Defined in: [src/drizzle/tables/comments.ts:67](https://github.com/Suyash878/talawa-api/blob/3474b77f72280ba1995cde9b1c779f1cd4f38e39/src/drizzle/tables/comments.ts#L67)
