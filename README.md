# Custom Incus USI

A custom Unified System Image (USI) of Incus designed to be as lightweight as
possible. Throw the `.efi` into your `esp` directory and it'll run on its own
without any additional setup!

## Quick Build

Simply install `mkosi`, `cd` into the project base directory, and run:

```bash
mkosi build
```

An `epsilon.efi` should be produced in the base directory after a successful
build.
