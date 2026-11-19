# Local copy of this site. It runs the same code with the same
# ./scripts/build.sh and ./scripts/start.sh that dPanel runs in production.
FROM dunglas/frankenphp:1.12.1-php8.5-bookworm

# WordPress needs mysqli to talk to MariaDB.
RUN install-php-extensions mysqli
