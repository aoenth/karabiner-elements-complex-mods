# Karabiner Elements Custom Complex Modifications
List of modifications for the standard Dvorak Keyboard Layout.

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

## Modifications for Software Dvorak Keyboards
Applicable to Macs using the "Dvorak Keyboard Layout" ![](README_files/dv_icon.png), the "Remapped Input"s would re-remap into Dvorak on the system level.

| Apparent Input | Remapped Input | Resulting Input |
|----------------|----------------|-----------------|
| ⌘ J            | ⌘ I            | ⌘ C             |
| ⌘ K            | ⌘ . (Period)   | ⌘ V             |
| ⌘ Q            | ⌘ B            | ⌘ X             |
| ⌘ ; (Semicolon)| ⌘ / (Slash)    | ⌘ Z             |
| ⌘ ' (Quote)    | ⌘ X            | ⌘ Q             |

## Modifications for Hardware Dvorak Keyboards
Applicable to Macs using the standard QWERTY layout, but the keyboard remaps keystrokes to Dvorak on the hardware level.

| Apparent Input | Remapped and Resulting Input |
|----------------|------------------------------|
| ⌘ J            | ⌘ C                           |
| ⌘ K            | ⌘ V                           |
| ⌘ Q            | ⌘ X                           |
| ⌘ ; (Semicolon)| ⌘ Z                           |
| ⌘ ' (Quote)    | ⌘ Q                           |

### Directional Navigation for Hardware Dvorak Keyboards
Applicable to Macs using the standard QWERTY layout, but the keyboard remaps keystrokes to Dvorak on the hardware level. Ignores remaps when using Terminal.
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
| Home           | ⌘ Left Arrow                 | Beginning of Line |
| End            | ⌘ Right Arrow                | End of Line       |
