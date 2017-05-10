# task-sync-unit
Simple taskwarrior sync unit and timer file

# Install as user unit
* Copy both files into ```~/.config/systemd/user```
* Start task sync timer job: ```systemctl --user task-sync.timer```
* Enable task sync on login: ```systemctl --user enable task-sync.timer
* Check if timer is running: ```systemctl --user status task-sync.timer```

