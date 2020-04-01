# Karabiner Elements Custom Complex Modifications
List of modifications for the standard Dvorak Keyboard Layout. **Software keyboards** are applicable to Macs using the "Dvorak Keyboard Layout" ![](README_files/dv_icon.png), the "Remapped Input"s would re-remap into Dvorak on the system level. **Hardware keyboards** are applicable to Macs using the standard QWERTY layout, but the keyboard remaps keystrokes to Dvorak on the hardware level.


## Get Started

1. Make sure you have the following:
* macOS Catalina ```10.15.3``` (anything lower is not tested)
* Karabiner-Elements ```11.6.0``` or higher

2. Find or create the following folder:
```
/Users/{username}/.config/karabiner/assets/complex_modifications
```

3. ```git clone``` into this folder or simply copy the json files into this folder.

4. Start Karabiner-Elements and navigate to "Complex Modifications", click "Add Rule" and enable the rules you want to add.
![](README_files/screenshot.png)

## Undo/Cut/Copy/Paste for Software Dvorak Keyboards
* `dvorak_cmd_zxcv_software_keyboard.json`

| Apparent Input | Remapped Input | Resulting Input |
|----------------|----------------|-----------------|
| ⌘ J            | ⌘ I            | ⌘ C             |
| ⌘ K            | ⌘ . (Period)   | ⌘ V             |
| ⌘ Q            | ⌘ B            | ⌘ X             |
| ⌘ ; (Semicolon)| ⌘ / (Slash)    | ⌘ Z             |
| ⌘ ' (Quote)    | ⌘ X            | ⌘ Q             |

## Undo/Cut/Copy/Paste for Hardware Dvorak Keyboards
* `dvorak_cmd_zxcv_hardware_keyboard.json`


| Apparent Input | Remapped and Resulting Input |
|----------------|------------------------------|
| ⌘ J            | ⌘ C                           |
| ⌘ K            | ⌘ V                           |
| ⌘ Q            | ⌘ X                           |
| ⌘ ; (Semicolon)| ⌘ Z                           |
| ⌘ ' (Quote)    | ⌘ Q                           |

## Directional Navigation for Hardware Dvorak Keyboards
* `control_keys_hardware_keyboard.json`

Ignores remaps when using Terminal.

| Apparent Input | Remapped and Resulting Input | Function          |
|----------------|------------------------------|-------------------|
| ^ E            | ⌘ Right Arrow                | End of Line       |
| ^ A            | ⌘ Left Arrow                 | Beginning of Line |
| ^ P            | Up Arrow                     | Previous Line     |
| ^ N            | Down Arrow                   | Next Line         |
| ^ F            | Right Arrow                  | Next Character    |
| ^ B            | Left Arrow                   | Previous Character|
| ⌥ F            | ⌥ Right Arrow                | Next Word         |
| ⌥ B            | ⌥ Left Arrow                 | Previous Word     |

## Home/End for Hardware and Software Dvorak Keyboards
* `home_end.json`

Ignores remaps when using Terminal.

| Apparent Input | Remapped and Resulting Input | Function          |
|----------------|------------------------------|-------------------|
| Home           | ⌘ Left Arrow                 | Beginning of Line |
| End            | ⌘ Right Arrow                | End of Line       |

## New Directional Navigation for Hardware and Software Dvorak Keyboards
* `new_control_keys_hardware_keyboard.json` or `new_control_keys_software_keyboard.json`

Ignores remaps when using Terminal.

| Apparent Input | Remapped and Resulting Input | Function          |
|----------------|------------------------------|-------------------|
| ^ H            | Up Arrow                     | Previous Line     |
| ^ T            | Down Arrow                   | Next Line         |
| ^ N            | Left Arrow                   | Previous Character|
| ^ S            | Right Arrow                  | Next Character    |
| ⌥ N            | ⌥ Left Arrow                 | Previous Word     |
| ⌥ S            | ⌥ Right Arrow                | Next Word         |
| ^ Enter        | ⌘ Right Arrow                | End of Line       |
| ⌥ Enter        | ⌘ Left Arrow                 | Beginning of Line |
