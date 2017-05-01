
To setup postgres:

    sudo su postgres -c psql < setup_dbs.sql
    sudo su postgres -c "psql -d edge_modules" < moduledb.sql