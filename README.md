# qmk-keychron-q2-pro-ansi-charlotte

Firmware keymap for a Keychron Q2 Pro ANSI with rotary encoder

## Setup

1. You want the `wireless_playground` branch of Keychron's QMK fork.
2. `qmk/ $ git clone https://github.com/char/qmk-keychron-q2-pro-ansi-charlotte.git keyboards/keychron/q2_pro/ansi_encoder/keymaps/char`
3. Ensure `ENABLE_FACTORY_TEST` is not defined in `keyboards/…/q2_pro/rules.mk`
4. `make keychron/q2_pro/ansi_encoder:char` and flash
