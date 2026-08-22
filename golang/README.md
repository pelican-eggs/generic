# Go Language Generic

This egg is designed to run any generic Go application or bot, allowing users to pull their Go source code from a Git repository or upload their own files.

The startup configs and commands may need changing to match your application entrypoint.

`EXECUTABLE` is the name of the executable binary that is built (default: `app`).

## Configuration

The server will be stuck as `starting` until the egg Start Configuration is modified. You have to edit the text to match something your bot will print for Pterodactyl panel to detect it as running.
![image](https://user-images.githubusercontent.com/10975908/126516861-c5cb4630-9f25-405c-8199-97bf5ec15a7f.png)

You can use arrays to have multiple different values when different bots are being used

```json
{
  "done":[
    "change this text 1",
    "change this text 2"
  ]
}
