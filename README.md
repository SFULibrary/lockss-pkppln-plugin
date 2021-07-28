# lockss-pkppln-plugin
LOCKSS Plugin for the PKP PLN staging server

## Usage

1. Copy local.properties to USERNAME.properties and fill out the properties in the
file. Do not add this file to git.

2. Generate signing keys with `ant -Dalias=USERNAME doKeys`.

3. Build the plugin with `ant -Dalias=USERNAME`.

4. Add the plugin and public key to LOCKSSOMatic.
