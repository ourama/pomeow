# pomeow

The cat has arrived. Stop working.

```
 /\_/\
( o.o )
 > ^ <

  01:32
```

---

pomeow is not a Pomodoro timer.

It is a cat that visits your terminal every 25 minutes.
When it appears, you stop working. You look at it. You attend to it.
It is a cat. That is not optional.

---

## Install

```sh
git clone https://github.com/ourama/pomeow.git
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

| Phase | Duration    | What happens                        |
|-------|-------------|-------------------------------------|
| Work  | 25 min      | Countdown timer                     |
| Break | 3–5 min     | The cat arrives, elapsed time shown |

The cat stays for 3, 4, or 5 minutes — you won't know which.
It changes pose every 2–6 seconds, then says `meow` and leaves.

## License

MIT
