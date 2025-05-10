# ZK ZSH autocomplete

Really basic [zk-org](https://zk-org.github.io/zk/) autocompletion for ZSH.
Don't expect too much :)

## Install

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/sudores/zk-org-autocomplete ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zk
    ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

    ```sh
    plugins=( 
        # other plugins...
       zk 
    )
    ```

3. Start a new terminal session.

## Uninstal

1. Remove the code referencing this plugin from `~/.zshrc`.
2. Remove the git repository from your hard drive

    ```sh
    rm -rf ~/.zsh/zk # Or wherever you installed
    ```
