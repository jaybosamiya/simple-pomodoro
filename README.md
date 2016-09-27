# Simple Pomodoro

> A simple "pomodoro" timer, to help focus work

It is quite easy to get too lost in work, and not realize where you are focussing. Hence, I find it useful to routinely (i.e., every half hour for me), just gather my thoughts and continue working. So, I wrote this simple small script.

## Usage

Copy the [pomodoro script](pomodoro) somewhere onto your path (maybe `/usr/local/games/`?), and execute `./pomodoro [duration]`.

The screen will briefly dim and reset to normal every `duration` (default = 1800 seconds = 30 minutes).

## Requirements

You might need to install `xbacklight` for it to work.

On Ubuntu 14.04, this is installed as simply as

```
sudo apt-get install xbacklight
```

## License

[MIT License](https://jay.mit-license.org/2016)