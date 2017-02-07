[![Circle CI](https://circleci.com/gh/gliderlabs/glidergun-rack.png?style=shield)](https://circleci.com/gh/gliderlabs/glidergun-rack)

This is a repo for declaring [glidergun binary dependencies](https://github.com/gliderlabs/glidergun/blob/master/src/deps.bash#L3).
Think about it as an overly simplified OS independent package manager.

## Custom repo

Gildergun by default uses the github.com/gliderlabs/glidergun-rack repo, see the [dep module](https://github.com/gliderlabs/glidergun/blob/master/src/deps.bash#L3).
In order to use this fork, set the `DEPS_REPO` in `Gunfile`.

```
export DEPS_REPO=https://raw.githubusercontent.com/lalyos/glidergun-rack/master/index
```
