```
Archived - 30 Nov 2025


I have decided not to further develop COSMIC applets.

COSMIC is a great step forward, but it is not ready yet. Therefore, I am not actively using it and am not gaining anything from developing these applets.

COSMIC still lacks basic features, such as proper drag-and-drop support and Nightlight.

The COSMIC toolkit is also not ready and requires a lot of boilerplate code for simple features.


The applets are still perfectly usable because, unlike GNOME, COSMIC does not frequently break applets.

They don't statically link to the latest LIBCOSMIC version, so they won't receive new features, but they work fine otherwise.


Best regards,


bGVia3VjaGVu


Thank you!
```

![Screenshot_2025-05-23_22-39-32](https://github.com/user-attachments/assets/dbc9f0fe-f99b-4eb0-bfcc-c869207033e0)

# Install 
```sh
git clone https://github.com/bGVia3VjaGVun/cosmic-ext-applet-emoji-selector 
cd cosmic-ext-applet-emoji-selector 
cargo b -r
sudo just install
```

# Config
The configuration directory is `~/.config/cosmic/dev.dominiccgeh.CosmicAppletEmojiSelector/v1/`.
In addition, the default schema can be installed with `just install-schema`. 
More documentation is provided [here](CONFIG.md).

# Emoji font
`Noto Color Emoji` is the default emoji font and is required by default. 
The default can be changed in `~/.config/cosmic/dev.dominiccgeh.CosmicAppletEmojiSelector/v1/font_family`.
A font which supports Unicode 15.1 is generally recommended.

# License
Files without an SPDX identifier are licensed under the MIT LICENSE
