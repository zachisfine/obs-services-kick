# obs-services-kick

services.json for OBS with Kick streaming included

# How do I install this?

- Paste the following into `Start -> Run` (WinKey + r), or any Windows Explorer address bar and hit `Enter`:

> %APPDATA%\obs-studio\plugin_config\rtmp-services

- Make a copy of `services.json` on your Desktop, or wherever is handy to have backed up.

- Download the revised `services.json` file [here](https://raw.githubusercontent.com/zachisfine/obs-services-kick/main/services.json) into that directory

- Restart OBS

- Go to `File` -> `Settings` -> `Stream` and click `Show All...` in the `Service` list, and you should now see `Kick`

This version has the recommended settings shown, a working `More Info` button, and a working `Get Stream Key` button which links to the Creator Dashboard settings page to directly grab it
