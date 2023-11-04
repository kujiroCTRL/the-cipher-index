# Presentation to the Cipher Academy Discord server's code archive
## A little bit about the CA server
I am not feeling particularly poetic lately so no description for this commit :)



## `ciphers/`
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

On

## `attachments/`
`attachments/` contains all files loaded as part (or as a supplement) for the codes in `ciphers/`

The file names are for the most part the same as the ones loaded on the server, exception made for homonymous files

For compressed files you can also find a subfolder containing the extracted files
