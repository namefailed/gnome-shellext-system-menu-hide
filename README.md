

# gnome-shellext-system-menu-hide-items
 GNOME Shell Extension to hide the Screen Lock & Settings menuitem

I simply never use the "Lock" & "Settings" items in the System Menu, so after a quick search for an extension like this came up with just an extension to hide the lock item, I decided to fork it and start maintaining it. Tested solely on GNOME 42/PopOS 22.04 because this is just a quick personal fixup, but I'll put it on the extensions site in case anyone else wants to try it on their system.

Roadmap: Instead of hiding the item, move it into the "Power Off/Log Out" submenu, and then rename the menu for users who still want access to it. I tried messing with this but couldn't figure out how to deregister the item from its current position and didn't feel like digging too deep as my JS chops are way rusty and GNOME's documentation of the JS api kinda blows. Feel free to fork/pr if you know how to do this. Also creating a GUI to toggle any or all of the system menu items would be a further progression.

THIS IS A FORK OF THE ORIGINAL https://github.com/adyrosebrigg/gnome-shellext-hide-lock
Credit to the original author of the project. It's no longer maintained, hence creating the fork and making minimal edits to the readme, etc.
