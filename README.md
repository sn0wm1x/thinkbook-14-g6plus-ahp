# ThinkBook 14 G6+ AHP

## Assets

These assets work for the Lenovo ThinkBook 14 G6+ AHP (R7-8845H-32G-1T), and I think the IMH (Intel) version should work as well.

### [Color](/color/)

Extract from `C:\Windows\System32\spool\drivers\color`.

### Impulse

TODO

## Flakes

TODO

```nix
{
  inputs = {
    nixpkgs.url = "github:NixOS/nixpkgs/nixos-unstable";
    tb14g6plus.url = "github:sn0wm1x/thinkbook-14-g6plus-ahp";
  }
}
```
