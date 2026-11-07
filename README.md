🎮 PS4 F-PKG Region Converter (USA ➡️ EU)

A streamlined guide and setup for changing the CUSA (region ID) of Fake PKG (.pkg) files on jailbroken PlayStation 4 consoles. This allows you to convert games from USA region releases to EU region releases to ensure compatibility with localized DLCs, updates, and add-ons.

⚡ How It Works

The process unpacks the game package, updates internal metadata identifiers, and repacks the modified files into a working Fake PKG:

Unpack: Extract the source USA .pkg file using PS4 PKG Tools / Orbis-Toolchain.

Modify: Edit the internal param.sfo file to change the original CUSAXXXXX to your target EU CUSAXXXXX.

Repack: Rebuild the project into a new .pkg using the Fake PKG Generator.

🛠️ Required Tools

PS4 Fake PKG Generator (Orbis / Cyb1k tools)

PS4 PKG Tool

Param.SFO Editor

Jailbroken PS4 console running GoldHEN

⚠️ Notes & Caveats

Save Data: Changing the CUSA ID means your old USA save files will not automatically load. You will need to convert save files separately using tools like Apollo Save Tool.

Disclaimer: This repository is intended strictly for educational and research purposes. It does not contain copyrighted game files, encryption keys, or pirated content.
