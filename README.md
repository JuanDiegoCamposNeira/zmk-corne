# zmk-corne

This repository contains the configuration files for a Corne split keyboard (6x6) running ZMK firmware.

## Keyboard Layout

Below is the visual representation of the Corne keyboard layout, based on the `config/corne.keymap` file.
The keyboard has four layers: 
    1. Base
    2. Lower
    3. Rise 
    4. Adjust (Both Lower and Rise pressed at the same time)

### Base Layer
```
-------------------------------------     --------------------------------------
|  TAB |  Q  |  W  |  E  |  R  |  T  |   |  Y  |  U   |  I  |  O  |  P  | BSPC |
--------------------------------------   ---------------------------------------
| CTRL |  A  |  S  |  D  |  F  |  G  |   |  H  |  J   |  K  |  L  |  ;  |  '   |
--------------------------------------   ---------------------------------------
| SHFT |  Z  |  X  |  C  |  V  |  B  |   |  N  |  M   |  ,  |  .  |  /  | ESC  |
--------------------------------------   ---------------------------------------
                   | GUI | LWR | SPC |   | ENT | RSE  | ALT |
                   ------------------     -------------------
```

### Lower Layer
```
-------------------------------------     -------------------------------------
|  TAB |  1  |  2  |  3  |  4  |  5  |   |  6  |  7  |  8  |  9  |  0  | BSPC |
--------------------------------------   --------------------------------------
|      |CAPS |     |     |     |     |   | LFT | DWN |  UP | RGT |     |      |
--------------------------------------   --------------------------------------
| SHFT |     |     |     |     |     |   |     |     |     |     |     |      |
--------------------------------------   --------------------------------------
                   | GUI |     | SPC |   | ENT |     | ALT |
                   ------------------     -----------------
```

### Rise Layer
```
-------------------------------------     -------------------------------------
|  TAB |  !  |  @  |  #  |  $  |  %  |   |  ^  |  &  |  *  |  (  |  )  | BSPC |
--------------------------------------   --------------------------------------
| CTRL |     |     |     |     |     |   |  -  |  =  |  [  |  ]  |  \  |  `   |
--------------------------------------   --------------------------------------
| SHFT |     |     |     |     |     |   |  _  |  +  |  {  |  }  | "|" |  ~   |
--------------------------------------   --------------------------------------
                   | GUI |     | SPC |   | ENT |     | ALT |
                   ------------------     ------------------
```

### Adjust Layer
```
-----------------------------------------------------     -----------------------------------------
|      | F1        | F2         | F3    | F4   | F5  |   | F6   | F7   | F8    | F9  |     |      |
------------------------------------------------------   ------------------------------------------
|      | BTCLR_ALL | scrn_sht_s | BT1   | BT2  | BT3 |   | VOL_D| MUTE | VOL_U |     |     |      |
------------------------------------------------------   ------------------------------------------
|      |           | scrn_sht_c | BTCLR |      |     |   | PREV | Play | NEXT  |     |     |      |
------------------------------------------------------   ------------------------------------------
                                |       |      |     |   |      |      |       |
                                ---------------------     ----------------------
```

> _Note: The actual key assignments may vary depending on your configuration. Please refer to your `config/corne.keymap` file for precise details._

## Macros

This keyboard configuration includes the following macros as defined in `config/corne.keymap`:

- **scrn_sht_s**: Takes a simple screenshot.
- **scrn_sht_c**: Toggles dialog to take either a screenshot or record the scren.

---
