# DeluxeMC Server Files

## Customization

Use these files to set up your DeluxeMC anarchy server. For adjustments to the DeluxeMC tab and URL, please visit our AnarchyCore plugin repository: [DeluxeMC AnarchyCore](https://github.com/DeluxeMCDev/AnarchyCore).

## Server Details

Our server runs on Paper Folia for improved thread management. It's part of a BungeeCord network.

## Removing BungeeCord

If you decide BungeeCord isn't for you, it's simple to remove:

1. Edit the `spigot.yml` file:
   - Change `bungeecord: true` to `bungeecord: false`.
2. Remove the Fallback Server Addon from the plugins folder.

## Configuration

Feel free to change the server port in the `server.properties` file to suit your needs.

## Security

Make sure to secure your server using IP Tables or UFW. If you're using the Pterodactyl panel, you can set up a local allocation using the container’s local IP for security.
