# hackthebox vim terminal

## Installation Steps
1. Open hackthebox-vim.dconf and save it as `hackthebox-vim.dconf` in your `home folder` without txt extension that the browser will infer 
2. Open Gnome Terminal and run:
    ```js
    dconf load /org/gnome/terminal/legacy/profiles:/:profile_id_default/ < hackthebox-vim.dconf
    ```

// to get profile_id_default : first create a new profile(with any name) in gnome terminal then use `dconf-editor` to get profile id
// profile_id: open dconf-editor using `Alt+f2`, the locate to `/org/gnome/terminal/legacy/profiles:/` 
3. Open a new window to see if the theme has been applied, if not open the `preferences` and select the `hackthebox vim Theme` profile.
