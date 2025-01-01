# TypeScript Pelican Egg

This egg automatically sets up a TypeScript server, installs the required packages, and compiles TypeScript files.

### Installation
> 1. **Add the Egg**: Upload the egg to your Pterodactyl Panel.
> 2. **Create a Server**: Create a new server with this egg in the panel.
> 3. **Set Environment Variables**: Configure `ADDITIONAL_PACKAGES` (Optional), `UNINSTALL_PACKAGES` (Optional), and `MAIN_FILE` in the panel.
> 4. **Start the Server**: The server will automatically install, compile, and run TypeScript.

## Environment Variables

- `ADDITIONAL_PACKAGES`: Additional npm packages to install.
- `UNINSTALL_PACKAGES`: npm packages to uninstall.
- `MAIN_FILE`: The main TypeScript file to run (e.g., `index.ts`).
