# Nix cheatsheet
Text here... <br />
Remember `sudo` !
<br />
<br />

### NixOS general purpose
General purpose commands that I can't remember.
<br />
<br />
Rebuild, upgrade and switch to new generation.
<br />
`nixos-rebuild swtich --upgrade`
<br />
<br />

### Nix garbage collection
Why do I write descriptions for these?
<br />
<br />
Nix-store garbage collection.
<br />
`nix-store --gc`
<br />
<br />

### Searching for packages
???
<br />
<br />
Using the NixOS website.
<br />
`search.nixos.org`
<br />
<br />
Using nix search.
<br />
`nix search firefox` <br />
! Experimental feature !
<br />
<br />
Using nix-env.
<br />
`nix-env -qaP`
<br />
