# pomeow

The cat has arrived. Stop working.

```
 /\_/\
( o.o )
 > ^ <
  Break  03:45
```

---

pomeow is not a Pomodoro timer.

It is a cat that visits your terminal every 25 minutes.
When it appears, you stop working. You look at it. You attend to it.
It is a cat. That is not optional.

---

## Install

```sh
git clone https://github.com/yourusername/pomeow.git
cd pomeow
chmod +x pomeow
sudo ln -s "$PWD/pomeow" /usr/local/bin/pomeow
```

## Usage

```sh
$ pomeow
```

Run it in a visible tmux pane. No flags. No config. Press `Ctrl+C` to quit.

## How it works

| Phase | Duration | What happens        |
|-------|----------|---------------------|
| Work  | 25 min   | Countdown timer     |
| Break | 4 min    | The cat arrives     |

The cat changes pose every 2–6 seconds.

## License

MIT
