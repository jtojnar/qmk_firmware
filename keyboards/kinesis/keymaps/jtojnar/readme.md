# jtojnar’s keymap for Kinesis Advantage2

## Setting up

Run

```
qmk config user.keyboard=kinesis/kint41
qmk config user.keymap=jtojnar
```

## Flashing keyboard

Run

```
nix-shell -I 'nixpkgs=channel:nixos-unstable' -p qmk --run 'qmk flash'
```

Then, after being asked, press <kbd>progm</kbd>+<kbd>F9</kbd> (RESET).
