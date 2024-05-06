# slot-machine-cli

Play a slot machine in your terminal with fake money.

## Spin the machine!

```shell
$ slot 100
💎|💎|💎 You win 1000.00
```

## Usage

```shell
$ slot -h
Usage: slot [options] <bet amount>

Minimum bet amount: 1
Maximum bet amount: 1,000,000

Prizes:

  One cherry (🍒) wins 1.5x bet amount
  Two watermelons (🍉🍉) wins 3x bet amount
  A cat and a fish (🐱🐟) wins 4x bet amount
  A combination of 3 fruits and vegetables (🍒🍋🍊🍇🍉) wins 5x bet amount
  Three bells (🔔🔔🔔) wins 10x bet amount
  Three diamonds (💎💎💎) wins 30x bet amount
  Three cat (🐱🐱🐱) wins 100x bet amount

Options:

  -h    Display the help message
  -n int
        Number of times the slot matchine spins (default 1)
```
