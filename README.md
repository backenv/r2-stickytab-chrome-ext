# r2-stickytab-chrome-ext
Rancher v2 sticky tabs, hides [ Download YAML ] [ Delete ] buttons, includes styles.css as new css rule

# How to use it

- Fork the repository or Clone it to your computer.
- Edit `manifest.json` and replace `<YOUR_RANCHER2_WEBPAGE>` with the url of your host
  - e.g.: `https://myrancher.example.com`.
- Download from repository to local directory if edited online.
- Open a tab in Chrome browser to `chrome://extensions`.
  - Drag and drop your compressed file [ deprecated ].
- or:
  - Activate developer mode and load uncompressed directory

## TODO

- Add `options.ui` to alter `manifest.json` entry: `content_scripts.matches`
