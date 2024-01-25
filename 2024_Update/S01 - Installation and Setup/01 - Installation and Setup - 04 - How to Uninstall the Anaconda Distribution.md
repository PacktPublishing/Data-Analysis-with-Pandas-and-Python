# How to Uninstall the Anaconda Distribution

In case you need to remove Anaconda, the complete instructions for uninstalling the distribution can be found here:

![https://docs.anaconda.com/free/anaconda/install/uninstall/](https://docs.anaconda.com/free/anaconda/install/uninstall/)

There are two options available: the more comprehensive Full Uninstall and the easier Simple remove. The Simple remove option may leave some files/folders behind on the hard drive but will uninstall the core/bulk of the distribution.

## Windows

1. Open your Windows File Explorer.
2. In your user folder (the one that is named after the user you're logged into), locate the anaconda3 directory.
3. Delete the envs and pkgs folders. The easiest way is to select them, then click the Trash icon on the top toolbar. Alternatively, right-click and select the Trash Icon on the pop-up modal.
4. Use the Start menu to search for Add or remove programs.
5. Locate the Anaconda program, then click the three-dot menu on the right, and select Uninstall.
6. Confirm by clicking the Uninstall button in the modal.

## macOS

1. Press Cmd + Space to bring up Spotlight Search.
2. Search for Terminal in the input field and open the Terminal application.
3. The Terminal is a prompt for issuing text commands to your computer. Execute the following commands one at a time to delete Anaconda 3 folders. The rm -rf command removes/deletes directories on the computer. Anaconda may be installed in different locations which is why there are multiple commands.

```bash
rm -rf anaconda3
rm -rf ~/anaconda3
rm -rf ~/opt/anaconda3
```
