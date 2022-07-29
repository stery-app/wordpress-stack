## Instructions

Copy `.env.example` to `.env`


Edit the `.env` file

Change the values for `APP_PORT`, `DB_ROOT_PASSWORD`, `DB_NAME`, `DB_PASSWORD`

```
APP_PORT=8000

DB_ROOT_PASSWORD=root_password
DB_NAME=wordpress
DB_USER=wordpress
DB_PASSWORD=some_random_words
```

Run `docker-compose up`


## Configuration

To change the `post_max_size` and `upload_max_filesize`:

Edit `config/upload.ini`