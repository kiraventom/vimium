For hover on scroll to work, add this in custom mapping:

`map C LinkHints.activateMode action=hover-and-scroll`

Build and install:
1. Install `deno` and `zip`
2. Run `./make.js write-firefox-manifest`
3. Run `./make.js package`
4. Open `about:config` in LibreWolf -> set `xpinstall.signatures.required` to `false`
5. Extensions -> Settings -> Install from local -> `vimium/dist/firefox/vimium-firefox-X.X.X.zip`
