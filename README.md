# skeleton-php-docker

# Setup

## Docker
Run `make setup` from `/dev` director.

## Phpstorm
### Xdebug

- Adjust `serverName` in `dev/.env`
- In PHPStorm, go to File -> Settings -> Languages and Frameworks -> PHP > Debug. Make sure you have the some port that you have configured previously in "XDEBUG_CONFIG" environment variable.
- Go to File -> Settings -> Languages and Frameworks -> PHP -> Servers
    - Add a server, the name should match the `serverName` specified in `.env`
    - Set host and port (e.g. `localhost:8100`)
    - Configure path mappings
    
# Test

Browse to http://skeleton.dev.local:8100/
