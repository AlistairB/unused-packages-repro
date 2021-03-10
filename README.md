# unused-packages issue repro

```bash
cabal build
```

produces unused package warning for base-noprelude, when it is definitely used.
