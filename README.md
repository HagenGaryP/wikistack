# wikistack

This FSA workshop had some small bugs but actually is extremely important in understanding express and Sequelize.
I'd definitely recommend spending a fair amount of time on it to fully understand.

Follow it step by step and you shouldn't have any issues.  Be sure to test your code after everything you add :)

If you end up getting an error like (SequelizeDatabaseError: column "authorId" does not exist) -> 
You can use "{force: true}" inside the .sync method on your database (or individual models)
await db.sync({force: true}); 
save it once to remake the tables, then you can delete the force true.  
Or you can probably just delete your tables and rerun your server.
