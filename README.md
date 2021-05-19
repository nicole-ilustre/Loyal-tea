This is our final group project in EDA.

I pitched the idea of loyalty card wallets and half of my cohort volunteered to work on it. I was the product owner and tech-lead of a team of 5. We worked on the project for a week and presented our MVP on graduation night.

This is currently still an MVP. I plan to keep working on it and keep adding features. Some features to be added:
-Ability to delete user and business
-More data statistics on the business side
-Move the QR code generator to the business side to allow for customers to scan the business's QR code instead of the other way around.
-Add QR Code scanner
-Wrap it in Cordova
-Play around with different authentications

We used React for front end and SQLite 3 for databases and Passport for authentication.

The client will be available on http://localhost:8080 and the server on http://localhost:3000. Note that you will still need to manage CORS between the two, as they are on different ports.

