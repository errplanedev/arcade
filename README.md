# arcade
a bare bones, simple multiplatform (no windows) package manager.

## recipe specification
arcade uses recipes, which are made with json heres an example
```json
{
    "name": "example recipe",
    "version": "v1.0",
    "install": {
        "linux": ["echo this is the first command to run", "echo this is the second"],
        "macos": ["echo hello soydev", "echo do you feel good now that you spent $1k on a laptop"]
    },
    "uninstall": {
        "linux": ["echo ok"],
        "macos": ["echo ok"]
    }
}
```