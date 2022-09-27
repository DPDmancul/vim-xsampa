# vim-xsampa

automatic X-SAMPA to IPA translation

see `:h xsampa' for more information

Released under GPLv3

## Installation

```vim
" vim-plug
Plug 'DPDmancul/vim-xsampa'

" packer.nvim
use 'DPDmancul/vim-xsampa'
```

### NixOs

```nix
buildVimPlugin rec {
  name = "vim-xsampa";
  src = pkgs.fetchFromGitHub {
    owner = "DPDmancul";
    repo = name;
    rev = "2a7ccb69c508e49126b541625e990b03a90e262f";
    sha256 = "te8pq/TxDepG/Lz4+rxfDa32K0sSWCFLcxlR3H79Wdg=";
  };
}
```

