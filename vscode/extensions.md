# Visual Studio Code extensions

## List extensions Unix:
    
    code --list-extensions | xargs -L 1 echo code --install-extension       
        
## List extensions Windows:

    code --list-extensions | % { "code --install-extension $_" }        
    
## My extensions:

    code --install-extension firefox-devtools.vscode-firefox-debug
    code --install-extension marcostazi.VS-code-drupal
    code --install-extension MS-CEINTL.vscode-language-pack-es
    code --install-extension ms-vscode.vscode-typescript-tslint-plugin
    code --install-extension msjsdiag.vscode-react-native
    code --install-extension NuclleaR.vscode-extension-auto-import
    code --install-extension rbbit.typescript-hero
    code --install-extension redhat.vscode-commons
    code --install-extension redhat.vscode-yaml
    code --install-extension riazxrazor.html-to-jsx
    code --install-extension rifi2k.format-html-in-php
    code --install-extension ritwickdey.LiveServer
    code --install-extension sidneys1.gitconfig
    code --install-extension steoates.autoimport
    code --install-extension TabNine.tabnine-vscode
    code --install-extension teeLang.vsprettier
    code --install-extension TheNouillet.symfony-vscode
    code --install-extension tht13.html-preview-vscode
    code --install-extension tombonnike.vscode-status-bar-format-toggle
    code --install-extension VisualStudioExptTeam.vscodeintellicode
    code --install-extension vscode-icons-team.vscode-icons
    code --install-extension zag7juuw4mfdvt4fpmfiocbzlwtsuh4t2udzl4sda7kdgyor6k4a.eslint-plugin-linting-lightning
    code --install-extension ZainChen.json
