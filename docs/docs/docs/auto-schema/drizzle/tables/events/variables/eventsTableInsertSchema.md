[Admin Docs](/)

***

# Variable: eventsTableInsertSchema

> `const` **eventsTableInsertSchema**: `BuildSchema`\<`"insert"`, \{ `createdAt`: `PgColumn`\<\{\}, \{\}\>; `creatorId`: `PgColumn`\<\{\}, \{\}\>; `description`: `PgColumn`\<\{\}, \{\}\>; `endAt`: `PgColumn`\<\{\}, \{\}\>; `id`: `PgColumn`\<\{\}, \{\}\>; `name`: `PgColumn`\<\{\}, \{\}\>; `organizationId`: `PgColumn`\<\{\}, \{\}\>; `startAt`: `PgColumn`\<\{\}, \{\}\>; `updatedAt`: `PgColumn`\<\{\}, \{\}\>; `updaterId`: `PgColumn`\<\{\}, \{\}\>; \}, \{ `endAt`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `name`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `organizationId`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; `startAt`: `ZodTypeAny` \| (`schema`) => `ZodTypeAny`; \}\>

Defined in: [src/drizzle/tables/events.ts:151](https://github.com/Suyash878/talawa-api/blob/3474b77f72280ba1995cde9b1c779f1cd4f38e39/src/drizzle/tables/events.ts#L151)
