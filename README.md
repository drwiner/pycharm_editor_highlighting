# pycharm_editor_highlighting
Configuring settings repository

If you want to share your IDE settings, perform the following steps:

On the computer where the PyCharm instance whose settings you want to share is installed, navigate to File | Settings Repository. Specify the URL of the repository you've created and click Overwrite Remote.
On each computer where you want your settings to be applied, in the Settings/Preferences dialog, expand the Tools node and choose Settings Repository, specify the URL of the repository you've created, and click Overwrite Local.
You can click Merge if you want the repository to keep a combination of the remote settings and your local settings. If any conflicts are detected, a dialog will be displayed where you can resolve these conflicts.

If you want to overwrite the remote settings with your local settings, click Overwrite Remote.
Your local settings will be automatically synchronized with the settings stored in the repository each time you perform an Update Project or a Push operation, or when you close your project or exit PyCharm.

If you want to disable automatic settings synchronization, navigate to File | Settings | Tools | Settings Repository and disable the Auto Sync option. You will be able to update your settings manually by choosing VCS | Sync Settings from the main menu.

https://www.jetbrains.com/help/pycharm/2017.1/sharing-your-ide-settings.html
