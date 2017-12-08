# Docker Craft CMS

[Craft CMS](https://craftcms.com/) running inside a [Docker](https://www.docker.com/) infrastructure.

## Usage

1. Copy and configure `/app/.env.example` to `/app/.env`
2. Run `composer install` to install dependencies such as Craft
3. Run `docker-compose up -d` to spin up the Docker infrastructure
4. Head to `/admin/install` to finish the install
5. Enjoy

## Notes

* Ensure your user mounting the volume and within the container have mutual permissions ie both in the www-data group