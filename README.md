Official SDK used by [wako](https://wako.app) and wako's add-ons

If you want to create your own add-on, take a look at the example of the [add-on starter kit](https://github.com/wako-app/addon-starter-kit)

## Migration to v11

Version v11 is now based on Angular v20 and will only work on wako v11+.

**Add-ons must upgrade to version v11 to be compatible with the latest version of wako v11+ or they'll be removed.**

## Entry Points by Version

To maintain compatibility across different versions of wako, different entry points are used:

- `entryPointV2`: for wako < 6
- `entryPointV3`: for wako 6 to 10
- `entryPointV4`: for wako > 10

For add-ons supporting multiple wako versions, you can specify multiple entry points in your manifest.
Wako will automatically select the appropriate entry point based on its version.

For recent add-ons compatible only with the latest version of wako, you only need to specify the corresponding entry point.

## Migration to v7

Version v7 is now based on Angular v14 and will only work on wako v6+.

**Add-ons must upgrade to version v7 to be compatible with the latest version of wako v6+ or they'll be removed.**

**You have until the `2020-07-01` to do the migration, before wako 6 will be out.**
