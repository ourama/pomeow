# pomeow

A cat that interrupts your terminal every Pomodoro break.

```
 /\_/\
( o.o )
 > ^ <
  Break  03:45
```

---

## Install

```sh
git clone https://github.com/yourusername/pomeow.git
cd pomeow
chmod +x pomeow
```

Put it on your PATH:

```sh
ln -s "$PWD/pomeow" /usr/local/bin/pomeow
```

## Usage

```sh
$ pomeow
```

No flags. No config. Press `Ctrl+C` to quit.

## How it works

| Phase | Duration | Display                    |
|-------|----------|----------------------------|
| Work  | 25 min   | Countdown timer            |
| Break | 4 min    | Cat + countdown            |

The cat changes expression every 2–6 seconds.

## Example

Work phase:

```
  Work  24:37
```

Break phase:

```
 /\_/\
( o.o )
 > ^ <
  Break  03:45
```

## License

MIT
