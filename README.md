# Wesly John

I work on software that has to keep working when the network does not.

Most of my focus is **mobile and local-first systems**: Flutter on Android, SQLite as the source of truth, and product flows built around real warehouse and field constraints—not demos that only run on a happy path.

## Selected work

### [Dispatch](https://github.com/weslyjohn1307/Dispatch)
Offline warehouse dispatch for Android.

- Sealed cartons as atomic stock units (`SEALED → RESERVED → DISPATCHED`)
- Crash-safe draft sessions and recovery sweeps
- Immutable delivery history with PDF notes and local backups
- Riverpod + go_router + sqflite; CI builds release APKs on tags

Source, docs, and installable APK:  
https://github.com/weslyjohn1307/Dispatch/releases/latest

## What I care about in code

- **Correctness over novelty** — migrations, invariants, and idempotent commits matter more than flashy UI
- **Operator UX** — large targets, calm layouts, fast paths for repeat work
- **Boring reliability** — offline drafts, explicit failure modes, no hidden cloud dependency to ship a carton

## Stack I use most

`Dart` · `Flutter` · `Android` · `SQLite` · `Riverpod` · GitHub Actions

---

GitHub is where I keep public work. For anything private or production signing, reach out through GitHub.