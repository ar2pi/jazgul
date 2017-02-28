# jazgul

### Project overview

A simple web app project to upload, organize and share songs

### How to install

```bash
cd /path/to/working/directory
git clone https://github.com/decksterr/jazgul.git
cd ./jazgul
sudo composer self-update && composer install
php bin/console server:run
```

It might be needed to change permissions on your var/cache directory, in which case run ```sudo chown [user]:dev -R ./var/cache``` where user is your current user
