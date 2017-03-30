# jazgul

### Project overview

A simple web app project to upload, organize and share songs

### How to install

```bash
cd /path/to/working/directory
git clone https://github.com/decksterr/jazgul.git
cd ./jazgul
sudo composer self-update && composer install
```

When asked for parameters configuration, just set database_name to 'sf_jazgul' for now.

It might be needed to change permissions in your var/cache directory, in which case run ```sudo chown [user]:dev -R ./var/cache``` where user is your current user

### How to launch

```bash
php bin/console server:run
```

And head to http://localhost:8000 :)
