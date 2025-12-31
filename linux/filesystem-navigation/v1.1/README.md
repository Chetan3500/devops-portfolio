# Filesystem & Navigation — v1.1

## Focus

Efficiency and safety upgrade.

## What was added

- Jump between multiple directories using `pushd` and `popd`
- Return to the previous working directory using `cd -`
- View directory stack to keep context while switching locations using `dirs -v`
- Visualize deep directory structures using `tree` and `ls -R`
- Safely inspect unknown files before opening them using `file`, `less` and `head`
- Move between logs, configs, and app folders without losing context

## Demo Link

[YouTube v1.1 — Directory Stack (pushd, popd) — Linux Filesystem](https://youtu.be/dfw3tnPdwnY)

## What this enabled

- **`pushd` and `popd`** let you move across multiple directories while preserving navigation history, making backtracking easy and reliable.
- **`cd -`** is the fastest way to toggle between your current and previous directory.
- **`dirs -v`** shows the directory stack with index numbers, helping you keep context and jump precisely between locations.
- **`tree` and `ls -R`** help you understand deep or unfamiliar directory structures before diving into them.
- **`file`, `less`, and `head`** allow you to safely inspect unknown files without executing or modifying them.
- These tools together enable smooth movement between **logs, configuration files, and application directories** without losing your place.

👉 **Bottom line:**

Using directory stacks and safe inspection tools turns filesystem navigation from guesswork into a controlled, confident workflow—especially when troubleshooting complex systems.
