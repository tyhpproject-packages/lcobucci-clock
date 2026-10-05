<!-- tyhp-readme:start -->
# tyhpdef/lcobucci-clock

Tyhp type definitions for `lcobucci/clock` `3.6.0`.

```bash
composer require --dev tyhpdef/lcobucci-clock:3.6.0
```

This is a metapackage. Composer also installs `tyhpdef/lcobucci-clock-impl` (type files).
Require **this** name, not `tyhpdef/lcobucci-clock-impl`.

See https://tyhplang.com.

## Maintain `lcobucci/clock`? Ship the types yourself

If you are a Packagist maintainer of `lcobucci/clock`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/lcobucci-clock-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `lcobucci/clock` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/lcobucci-clock": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `lcobucci/clock` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `lcobucci/clock` with a real constraint,
   `"replace": { "tyhpdef/lcobucci-clock": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `lcobucci/clock` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/lcobucci-clock` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
