<p align="center"><img src="https://i.imgur.com/roReHY7.jpeg"></p>

# 🚀 Installation Steps:

### 1. [Download](https://github.com/BXZ1/cs2-config/zipball/master) the config files and extract them to the following locations:

| 📄 File(s) | 📁 Destination Folder |
|:---:|:--|
| `autoexec.cfg`, `binds.cfg`, `practice.cfg`, `pvp.cfg` | `Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg` |
| `radial_custom.txt` | `Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo` |

### 2. Launch **Counter-Strike 2** and type `apply` in the console

# 🎮 Keybinds:

|️ ⌨️ Key | 💡 Description |
|:---:| --- |
| **W / A / S / D** | Movement (Switch to AZERTY in [binds.cfg lines 5–10](https://github.com/BXZ1/cs2-config/blob/master/binds.cfg#L5-L10)) |
| **SPACE** | Jump + Duck combo (`+djump`) |
| **SHIFT** | Walk |
| **CTRL** | Duck (Switchable with ALT in [binds.cfg lines 12-15](https://github.com/BXZ1/cs2-config/blob/master/binds.cfg#L12-L15)) |
| **ALT** | Drop the bomb (C4) (Switchable with CTRL in [binds.cfg lines 12-15](https://github.com/BXZ1/cs2-config/blob/master/binds.cfg#L12-L15)) |
| **MOUSE1 / MOUSE2** | Fire / Secondary fire |
| **Q** | Switch to previously used weapon |
| **1 / 2 / 3 / 4** | Select Primary / Secondary / Knife / Grenades |
| **5** | C4 or Healthshot *(custom dual-slot combo)* |
| **6 / 7 / 8 / 9 / 0** | HE / Flashbang / Smoke / Decoy / Incendiary & Molotov |
| **R** | Reload weapon |
| **E** | Use / Interact |
| **G** | Drop weapon |
| **L** | Switch weapon hand |
| **B** | Open Buy Menu |
| **UPARROW** | Buy Kevlar + Helmet |
| **DOWNARROW** | Buy Kevlar |
| **LEFTARROW** | Buy Defuse Kit |
| **RIGHTARROW** | Buy Decoy Grenade |
| **DEL** | Sell back all purchases |
| **F3** | Buy 2nd rifle slot (M4A4/M4A1-S or AK-47 depending on team/loadout) |
| **F4** | Buy Smoke, Flash, HE, Molotov/Incendiary |
| **F** | Throwables radial menu (`+quickinv`)<br /><img src="https://i.imgur.com/qQqEESz.png"> |
| **T** | Spray graffiti + Inspect weapon (combined) |
| **TAB** | Show scoreboard |
| **M** | Open team selection menu |
| **ESC** | Cancel / Close menu |
| **F1** | Toggle radar zoom (`toggleradarscale`) *(also used for voting)* |
| **F2 / NUMPAD ENTER** | Toggle clutch mode *(mute voice chat for one round, also used for voting)* |
| **F5 / F6** | Open custom Radio Wheel 1 / 2 |
| **Z / X / C** | Default radio menus 1 / 2 / 3 |
| **H** | Radio command: "Cover Me" |
| **J** | Radio command: "The bomb is going to blow!" *(loud warning)* |
| **K** | Radio command: "Enemy Down" |
| **U / Y** | Team Chat / Global Chat |
| **V / MOUSE4** | Push-to-talk (Voice chat) |
| **MOUSE3** | Player ping |
| **F7** | Toggle enemy voice chat mute |
| **F8** | Call timeout |
| **F9** | Say `¯\\_(ツ)_/¯` in chat |
| **F10** | Say `( > ⩊ < )` in chat |
| **F11** | Say sleeping ASCII art in chat |
| **CAPSLOCK** | Toggle noclip *(requires cheats / server-only)* |
| **HOME** | Disconnect from server |
| **PAGEUP / NUMPAD +** | Increase voice chat volume by 5% |
| **PAGEDOWN / NUMPAD -** | Decrease voice chat volume by 5% |
| **NUMPAD 0** | End warmup & restart match *(server-only)* |
| **NUMPAD 1** | Rethrow last grenade *(server-only)* |
| **NUMPAD 2** | Toggle grenade preview (PIP) *(server-only)* |
| **NUMPAD 3** | Enable "Buy Anywhere" *(server-only)* |
| **NUMPAD . / DEL** | Enable "All Talk" *(server-only — everyone hears everyone)* |

# ⚙ Aliases:

| 🔤 Alias | 💡 Description |
|:---:| --- |
| `apply` | Apply full config (executes `binds`, `autoexec`, and saves with `host_writeconfig`) |
| `auto` | Re-executes your `autoexec.cfg` |
| `d` | Disconnect from current server |
| `q` | Quit CS2 |
| `c` | Clear the console |
| `pract` | Load `practice.cfg` *(server-only)* |
| `pvp` | Load `pvp.cfg` *(server-only)* |
| `hs` | Toggle Headshot-only mode *(server-only)* |
| `sv` | Toggle `sv_cheats` on/off *(server-only)* |
| `hud` | Toggle HUD visibility (`cl_drawhud`) *(server-only)* |
| `arms` | Toggle Viewmodel Visibility (`r_drawviewmodel`) *(server-only)* |
| `del` | Delete the entity you're aiming at *(server-only)* |
| `hostage` | Spawn a hostage *(server-only)* |
| `shot` | Give yourself a Healthshot *(server-only)* |
| `chick` | Spawn a chicken *(server-only)* |
| `c4` | Give yourself a C4 bomb *(server-only)* |
| `plant` | Toggle plant C4 anywhere *(server-only)* |
| `slow` | Toggle slow-motion (timescale 0.5 & 0.2) *(server-only)* |
| `fast` | Toggle fast-motion (timescale 1.5 & 2) *(server-only)* |
| `norm` | Reset timescale to normal speed *(server-only)* |
| `grav` | Toggle low gravity + accurate air shots ON/OFF *(server-only)* |
| `third` | Enable third-person view *(server-only)* |
| `first` | Return to first-person view *(server-only)* |
| `bun` | Toggle auto bunnyhopping *(server-only)* |
| `pip` | Toggle grenade preview PIP *(server-only)* |
| `allbuy` | Toggle buy-anywhere + infinite buy time *(server-only)* |
| `alltalk` | Toggle full all-talk (live, dead, spec) *(server-only)* |
| `knives` | Spawn all CS knives *(server-only)* |

### 🎯 Weapon Loadout Presets *(server-only)*

| 🔤 Alias | 💡 Description |
|:---:| --- |
| `armor`, `helmet`, `noarmor` | Set default armor for all players |
| `nosec`, `nopri` | Remove secondary/primary weapons for CTs and Ts |
| `usp`, `glock`, `dual`, `five`, `p250`, `tec9`, `cz`, `r8`, `deagle` | Set **secondary** pistol as default for CTs and Ts |
| `nova`, `xm`, `mag7`, `sawedoff`, `negev`, `m2` | Set **heavy weapon** as default for CTs and Ts |
| `mp5`, `mp7`, `mp9`, `mac10`, `ump`, `p90`, `bizon` | Set **SMG** as default for CTs and Ts |
| `famas`, `galil`, `m4`, `m4s`, `ak`, `aug`, `sg` | Set **rifle** as default for CTs and Ts |
| `scout`, `awp`, `g3`, `scar` | Set **sniper** as default for CTs and Ts  |

<hr>

<p align="center">
  <a href="https://steamcommunity.com/id/BXZ1">My Steam Profile</a> |
  <a href="https://github.com/BXZ1/cs2-config/tree/csgo">CS:GO Config</a> |
  <a href="https://gist.github.com/BXZ1/2c1bee8f4cda2b0bbef9dbcb4d5d503a">Counter-Strike 1.6 Config</a>
</p>

<p align="center">
  <a href="https://github.com/BXZ1/cs2-config/tree/csgo">
    <img src="https://i.imgur.com/NsN13SA.png" width="400">
  </a>
</p>
