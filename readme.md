# Terminal.app profiles from the community

Terminal.app is a standard terminal emulator in OS X. You can customize colors and other settings. If you prefer multiple sets of settings for different occasions, you should use profiles:

<img src="https://raw.github.com/binaryage/terminal-profiles/master/readme-settings-pane.png" width="300"/>

For example. Profiles are used by [TotalTerminal](http://totalterminal.binaryage.com) plugin. It provides a system-wide window available on a hot-key called "Visor". TotalTerminal uses "Visor" profile for all shell session created in tabs under this special window. This way you can customize it and distinguish it from your classic terminal windows.

My initial motivation was to create a place where new TotalTerminal users can find nice-looking profile when starting. But more generally this can become a place where community can share their profiles in a cultivated way (e.g. with history).

# How could you add your own profile?

Note: Please make sure you are using the Lion version of Terminal.app.

1. Fork the project
2. Create your own folder (a folder name is the name of your profile, e.g. `My Profile`)
3. On Preferences->Settings pane, select your profile and use Export to save it into your folder (it should have same name as your folder say `My Profile.terminal`)
4. Commit and push
5. Send a pull request to [darwin](http://github.com/darwin)