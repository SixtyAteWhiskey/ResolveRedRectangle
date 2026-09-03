# Linux Mint

I am on Linux mint so the install instructions are meant for that, but you could do the same on PC/Mac by going to the same directory.

# Install 

- Download the .setting file
- Leave it in your downloads folder
- Open terminal and enter the following:
```
mkdir -p ~/.local/share/DaVinciResolve/Fusion/Templates/Edit/Generators/RedHighlightBox

cp ~/Downloads/"Red Highlight Box.setting" \
~/.local/share/DaVinciResolve/Fusion/Templates/Edit/Generators/RedHighlightBox/
```
This makes the requisite directory in davinci, then copy the generator from your downloads to there.

## Verify it worked:
```
find ~/.local/share/DaVinciResolve/Fusion/Templates -type f
```

## For the Paranoid

Below is the VirusTotal results:

<img width="786" height="339" alt="image" src="https://github.com/user-attachments/assets/f235be7a-eac9-4e10-a63a-76348373e8e9" />

Hash:
```
d3dddfb521cbacac9d8b8ab0fcdd6b61afeb24d04ff9122c67c020b61da306c2
```
