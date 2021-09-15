### Vim and Angular 2 snippets

Port of [John Papa's VSCode Snippets](https://github.com/johnpapa/vscode-angular2-snippets)

### TypeScript Snippets

```typescript

ngcomp              // Component
ngpipe              // Pipe
ng2-route-config    // @RouteConfig
ng2-route-path      // Routing path
ngserv              // Service
ngservr             // Service with providedIn: 'root'
ngsubs              // Observable subscription
nghttpg             // Http get call
nghttpp             // Http post call
ng2-component-root  // Angular 2 root App component
ng2-bootstrap       // Angular 2 bootstraping, for main.ts
```

### HTML Snippets

```html
ngclass
ngfor
ngfora     // async
ngif
ngifa      // async as data
ngmodel
routerlink
ngstyle
ngswitch
```

### Installation

####[vundle](https://github.com/gmarik/vundle)

    Plugin 'mhartington/vim-angular2-snippets'

to `.vimrc`, and then run `:PluginInstall`.

####[pathogen.vim](https://github.com/tpope/vim-pathogen)

    cd ~/.vim/bundle
    git clone https://github.com/mhartington/vim-angular2-snippets.git

Then reload vim, run `:Helptags`

####[apt-vim](https://github.com/egalpin/apt-vim)

    apt-vim install -y https://github.com/mhartington/vim-angular2-snippets.git

For those who need it, a tarball is available from
[here](https://github.com/mhartington/vim-angular2-snippets/archive/master.zip).

### Note

Only `snipemate` format at the moment. Works with [NeoSnippets](https://github.com/Shougo/neosnippet.vim), my preferred snippets plugin.
If you're up for adding UltiSnips compatibility, feel free to send a PR.
