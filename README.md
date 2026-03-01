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

## Requirements

- bash
- macOS or Linux

## Install

```sh
sudo curl -fsSL https://raw.githubusercontent.com/ourama/pomeow/main/pomeow -o /usr/local/bin/pomeow
sudo chmod +x /usr/local/bin/pomeow
```

## Usage

```sh
$ pomeow
```

Run it in a visible terminal window or tmux pane. Press `Ctrl+C` to quit.

## Customization

| Variable           | Default | Description          |
|--------------------|---------|----------------------|
| `POMEOW_WORK_SECS` | `1500`  | Work phase (seconds) |
| `POMEOW_BREAK_SECS`| random  | Break duration (3–5 min, random each cycle) |

```sh
POMEOW_WORK_SECS=3600 pomeow   # 60-minute work sessions
```

## How it works

| Phase | Duration    | What happens                        |
|-------|-------------|-------------------------------------|
| Work  | 25 min      | Countdown timer                     |
| Break | 3–5 min     | The cat arrives, elapsed time shown |

The cat stays for 3, 4, or 5 minutes — you won't know which.
It changes pose every 2–6 seconds, then says `meow` and leaves.

## License

MIT
