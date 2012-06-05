# The SQL wars: MongoDB versus PostgreSQL

Is MongoDB killing good old SQL? Or is it just a fad that good old Postgres will barely remember in another decade? Let's find out!

Here's how to deploy Mongo and Postgres in a test sandbox, and start playing with them, in less than 30 seconds.

1. Install the dotCloud client

    $ sudo easy_install pip && pip install dotcloud

2. Move to this repository

    $ cd sqlwars

3. Deploy the sandbox

    $ dotcloud push sqlwars


4. Open a mongo shell

    $ dotcloud run sqlwars.mongo mongo

5. Open a postgres shell

    $ dotcloud run sqlwars.postgres psql

6. Start querying!

    Postgres reference doc: http://www.postgresql.org/docs/9.1/static/tutorial-createdb.html
    MongoDB reference doc: http://www.mongodb.org/display/DOCS/Manual


Happy hacking!


