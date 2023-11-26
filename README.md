# Welcome to the Cipher Academy Discord community's code archive, aka the `cipher index`

## A little bit about the CA server

I am not feeling particularly poetic lately so no description for this commit :)

## About `ciphers/`

In `ciphers/` you'll find all codes published in the CA discord server

Each `.md` file corresponds to one code and includes the given prompt as well as the solution to the code (if any have been found)

Additional info's may be included in each file although atm the only info's are the difficulty of the code, it's author, the link to the original message and whether it has been solved or not

In the future I may add the solver's name and the overall time taken

Each `.md` follows the following naming convention


```
<author>-<code number>[-Solved].md
```

and `-Solved` is only applied to codes that've been cracked

If you are on a \*nix machine, you can list all solved codes by running

```bash
ls "*-Solved.md"
``` 

and likewise you can list unsolved ciphers running

```bash
ls -I "*-Solved.md"
```

The file name's format may change over time and feedbacks on anything regarding this repository are welcome

## About `attachments/`

`attachments/` contains all files loaded as part (or as a supplement) for the codes in `ciphers/` or in `private-ciphers/`

The file names are for the most part the same as the ones loaded on the server, exception made for homonymous files

For compressed files you can also find a subfolder containing the files extracted from it 

## About `private-ciphers/`

The `private-ciphers/` directory contains ciphers that have not been published on the Discord community and have been sent privately

These of course don't include any codes that are intimate to the author and or to the target solver 

The file names' formatting is the same of the codes in `ciphers/`

## About `leaky-poker/`

In `leaky-poker/` you can find the designs for the CA community's very own "Leaky poker" as well as the original manga's designs for reference
