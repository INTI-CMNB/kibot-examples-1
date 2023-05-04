# KiBot Examples 1

This repo contains some [KiBot](https://github.com/INTI-CMNB/KiBot) examples.

If you find it useful, or you want to request a new example, please consider
[donating](https://www.paypal.com/donate/?hosted_button_id=K2T86GDTTMRPL) to
the [project](https://github.com/INTI-CMNB/KiBot).


## Separating information from the `Value` field

The `Value` field contains the value for the component. Some people likes to
add extra information to R, L and C components. Typical examples are the
resistors tolerance, capacitor voltage, etc. This isn't recommended by KiBot
project. Instead we encourage adding this information in separated fields.

This example shows how to convert a schematic that uses extra information in
the `Value` field to a schematic that uses separated fields.

[Example](value_split/README.md)
