<div align="center">
  <h1>gruvbox-material-tridactyl</h1>
  <p>A <strong><a href="https://tridactyl.xyz/">Tridactyl</a></strong> theme based on the wonderful <a href="https://github.com/sainnhe/gruvbox-material">Gruvbox Material</a>¹ color palette.</p>

  <br />

</div>

<img src="https://user-images.githubusercontent.com/288160/166327179-2d24507e-7046-4c38-8c90-200333e7c2b1.png" alt="Commands Screenshot²" title="Commands Screenshot²">
<img src="https://user-images.githubusercontent.com/288160/166327172-66f576e1-0025-4c10-aa2d-8055e4aeaf19.png" alt="Buffers Screenshot²" title="Buffers Screenshot²">
<img src="https://user-images.githubusercontent.com/288160/168132504-7065307b-48b8-4a44-85d9-b52392f3c83e.png" alt="Hints Screenshot²" title="Hints Screenshot²">

¹This is a ~work in progress~³ — 🚧 — so far only the **Dark Soft** variant has been implemented.

²You can find the Firefox theme used in the screenshot [here](https://addons.mozilla.org/en-US/firefox/addon/gruvbox-material-dark-soft/).

³I just switched to **[Glide](https://glide-browser.app/)**, so I probabaly won't be updating this theme much, though I'll try and help with fixes if I can. You should check out Glide, especially if you're into configuring a browser with TypeScript. I plan on theming it with this same theme, and I'll update here when I have something.

### Installation

```vim
:colourscheme --url https://github.com/jrolfs/gruvbox-material-tridactyl/releases/download/v0.1.1/dark-soft.css gruvbox-material-dark-soft
```

#### Fix Hints

Either run these commands from the Tridactyl command line or add them to your **`.tridactylrc`**. See **https://github.com/jrolfs/gruvbox-material-tridactyl/issues/6#issuecomment-3591906336** for details.

```vim
set hintstyles.fg none
set hintstyles.bg none
```

#### Credits

This was originally based off of [base16-tridactyl](https://github.com/bezmi/base16-tridactyl), 🙏🏻 thanks **[@bezmi](https://github.com/bezmi)**
