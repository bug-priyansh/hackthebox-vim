# hackthebox vim terminal

## Installation Steps
1. Open hackthebox-vim.dconf and save it as `hackthebox-vim.dconf` in your `home folder` without txt extension that the browser will infer 
2. Open Gnome Terminal and run:
    ```js
    dconf load /org/gnome/terminal/legacy/profiles:/:b1dcc9dd-5262-4d8d-a863-c897e6d979b9/ < ~/ hackthebox-vim.dconf
    ```
3. Open a new window to see if the theme has been applied, if not open the `preferences` and select the `hackthebox vim Theme` profile.
