# How To Capture Emails For Free With FaunaDB

> For new startups, you might be thinking about capturing interest early with an email capture form. Your options for this include MailChimp, HubSpot, OptinMonster, SumoMe, Sleeknote the list goes on. What stays the same is they all cost money, all of these services have add-ons like email campaigns and tracking that we're not interested in yet.
> We just need a form that captures and email address and stores it somewhere.

https://medium.com/@nedknowles/how-to-capture-emails-for-free-with-faunadb-954ee10efce5

---

# Setup

1. Create an admin key from your new database on fauna.com
2. Save the key to an env file `echo "FAUNADB_SECRET=xxx" > .env`
3. Upload the schema, functions and role with `yarn fauna`
4. Create a key from the frontend role.
5. Update the `index.html` with the `API_KEY`.
