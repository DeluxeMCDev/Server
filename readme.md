# DeluxeMC Server Files

# Folia Server

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

# Bungeecord Server

## Server Details

We're using NullCordX software, which is based on Paper Waterfall. NullCordX is a paid antibot solution, so we can't share it here. Instead, you can use the default waterfall jar we provided. If you have NullCordX, there's a config file for it that you can rename to `config.yml` and use instead of the one I included.

# Security

Make sure to protect your server with IP Tables or UFW. If you're using the Pterodactyl panel, you should set up a local allocation with the container's local IP for extra security.

For the Folia server, use the local IP to block external access to your backend server. For the Waterfall/NullCordX server, use your public IP so that players can connect directly.

We use a proxy to ensure that we have a fallback service in case the server crashes.
