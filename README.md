# Cobalt Strike Pseudo Tab Complete

Cobalt Strike 4.x compatible Aggressor Script that provide extra custom pseudo (ie not using the Tab key) "tab completion" or convenience of the Red Team Operator.

Upon actuation of the Pseudo Tab Complete hotkey (default set to Ctrl+Space) it cycles through a completion database and instantiates the contents onto the beacon input commandline one-by-one per the keypress actuation. The script by default builds a database of completables using the configured listeners and targets. 

Additionally, a hotkey has been added for quicker "Select All" of contents on the current beacon line. Dunno about you but quicker to delete long input Iie Rubeus commands) than drag-and-highlight.

## Default Configurations
| Action  | Shortcut Binding |
| :--------------------: | :-------------: |
|Tab Complete     | __Ctrl+Space__ |
| Select All Input| __Ctrl+Alt+A__|

 

## References
- [Raphael Mudge Armitage Scripts](https://github.com/rsmudge/cortana-scripts)
- [Sleep Manual](https://sleep.dashnine.org/)
- [Cobalt Strike Manual](https://hstechdocs.helpsystems.com/manuals/cobaltstrike)

If you wish, you can easily change the key bindings for actuation per [Fortra's guide](https://hstechdocs.helpsystems.com/manuals/cobaltstrike/current/userguide/content/topics_aggressor-scripts/as_cobalt-strike.htm) (see Keyboard Shortcuts section).
---
Tab Completion 

https://github.com/user-attachments/assets/9a7f48d5-489b-4508-99fb-e4ba59642868

Select All

https://github.com/user-attachments/assets/407969cf-348f-4055-ba12-8252a62c2684

