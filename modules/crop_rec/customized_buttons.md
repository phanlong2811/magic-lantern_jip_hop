# crop_rec: customized buttons (EOS M)

ML menu → Movie → **customized buttons**. These shortcuts change ISO and
aperture straight from LiveView, without going through the Canon menus. This
page covers the gain shortcuts and the buttons they take over. It is a
separate file because `README.rst` is compiled into `crop_rec.mo`.

## gain

| Setting | Up / Down | INFO | SET |
|---|---|---|---|
| OFF | Canon | Canon | Canon |
| ISO | ISO ± 1 stop | Canon | Canon |
| aperture | aperture ± 1 step | Canon | Canon |
| INFO_switch | ISO or aperture | switches between ISO and aperture | Canon |
| SET_switch | ISO or aperture | switches between ISO and aperture | switches between ISO and aperture (movie mode only) |

- With INFO_switch or SET_switch, the value that Up/Down will change is
  highlighted in orange on the ML bottom bar.
- ISO goes in full stops from 100 to 6400 in movie mode, and to 12800 in
  photo mode M. The ISO shortcuts do nothing while ISO is on Auto.
- INFO only switches on the ML overlay screen. On Canon's own display screens
  INFO works as usual.
- INFO_switch needs **INFO selectable** set to OFF. SET_switch needs
  **x3crop toggle** set to something other than SET.
- In movie mode, the main dial also changes the shutter speed when gain is not
  OFF (and exposure override is not active).

## photo mode

`OFF` / `M mode` (default: M mode).

When set to M mode, the gain shortcuts above also work in **photo mode M**:

- Up/Down replace Canon's drive mode (Up) and AF point reset (Down). Drive
  mode is still in the Q menu.
- INFO switches between ISO and aperture for both INFO_switch and SET_switch.
  SET is never taken over in photo mode, so it still opens Canon's Q menu.
- The main dial shutter shortcut is movie mode only.
- P, Av and Tv keep Canon's buttons.

Set it to OFF to get Canon's buttons back in M.

## Reaching Canon's screens: MENU

When INFO is taken over, the **MENU** button is the way to Canon's screens:

1. The first MENU press opens Canon's INFO display screen. INFO then cycles
   Canon's screens as usual.
2. The second MENU press opens Canon's main menu.

In movie mode this applies when gain is INFO_switch or SET_switch, or when
INFO selectable is on. In photo mode M it applies when gain is INFO_switch
or SET_switch and photo mode is on.
