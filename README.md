# gregorio-patch
Files to patch gregorio 6.0.0 to support more NABC neumes and NABC brackets

## How to deploy

Go to fonts/truetype/public/gregoriotex/ inside your Latex installation directory

Backup gregall.ttf

Paste gregall.ttf from this repository in this folder

Go to tex/luatex/gregoriotex/ inside your Latex installation directory

Backup gregoriotex-nabc.lua

Paste gregoriotex-nabc.lua from this repository in this folder

If you have installed the other requirements for the NR project, you can now build it.
