# NPM JSON Egg

This egg is designed to run any JavaScript application using `npm`. It allows users to pull their own JavaScript source code from a GitHub repository and start the application directly by specifying the command name from `package.json` without needing to prepend `npm`.

There is also an option to upload custom files to run an application, such as a bot.

## Configuration

The server will remain in the `starting` state until the egg's startup configuration is adjusted. You need to modify the settings to match a specific text output that your application prints, allowing Pterodactyl Panel to detect that it has successfully started.

You can use arrays to handle multiple values when running different applications:

```json
{
  "done":[
    "change this text 1",
    "change this text 2"
  ]
}
```

With this setup, the egg automatically starts the application according to the `package.json` configuration, allowing users to specify a command from `package.json` without needing to prepend `npm`.
