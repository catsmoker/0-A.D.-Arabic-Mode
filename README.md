# 0-A.D. Arabic Mode -test- 0.27.0

**0 A.D. does not currently support right-to-left (RTL) languages** such as Arabic, Persian, or Hebrew.

The game’s text rendering system (based on **GUI XML and Unicode fonts**) supports Unicode characters but **does not include RTL layout or contextual shaping** (like joining Arabic letters). This means:

* Arabic letters appear **disconnected**.
* Text direction stays **left-to-right**.
* UI alignment and menus are not adapted for RTL.
