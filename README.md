Time Counter

Simple application used to count time spent on certain activities. 

1. Main assumptions
    - App used to count how much time was spent on certain project
    - Choosable projects
    - Pomodoro mode 
    - Visualization of statistics
    - CLI 
    - Synchronize on multiple devices (server needed)
    - Two work modes:
        - background - counter not visible
        - foreground - counter visible in console session

2. Basic structure (concept)
    main.py - main source file
    timer.py - basic functions used to count time 
    projects.py - functions used to create and manage projects
    pomodoro.py - functions used in 'pomodoro' mode
    cli.py - functions used to parse commands from user
    visualize.py - functions used for visualization (in foreground mode)
    logs.py - function used to logging (for debuggins)

