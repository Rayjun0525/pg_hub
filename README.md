# pg_hub
PostgreSQL all in one Hub


pghub install postgresql-14.7
    --location=/path/to/engine/location
    --data-location=/path/to/data/location
    --with-extension='pg_hint_plan,auto_explain'
    --encoding=UTF-8
    --locale=C
    --daemon=True

pghub localinstall postgresql-14.7

pghub remove 