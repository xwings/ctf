```
{
    "$schema": "https://aka.ms/terminal-profiles-schema",
        "alwaysShowTabs" : true,
        "defaultProfile" : "{7f9aa0f1-fc04-455a-b5b5-ffdbf51cfefa}",
        "initialCols" : 120,
        "initialRows" : 30,
        "keybindings" : 
        [
            {
                "command" : "closeTab",
                "keys" : 
                [
                    "ctrl+w"
                ]
            },
            {
                "command" : "newTab",
                "keys" : 
                [
                    "ctrl+t"
                ]
            },
            {
                "command" : "newTabProfile0",
                "keys" : 
                [
                    "ctrl+shift+1"
                ]
            },
            {
                "command" : "newTabProfile1",
                "keys" : 
                [
                    "ctrl+shift+2"
                ]
            },
            {
                "command" : "newTabProfile2",
                "keys" : 
                [
                    "ctrl+shift+3"
                ]
            },
            {
                "command" : "newTabProfile3",
                "keys" : 
                [
                    "ctrl+shift+4"
                ]
            },
            {
                "command" : "newTabProfile4",
                "keys" : 
                [
                    "ctrl+shift+5"
                ]
            },
            {
                "command" : "newTabProfile5",
                "keys" : 
                [
                    "ctrl+shift+6"
                ]
            },
            {
                "command" : "newTabProfile6",
                "keys" : 
                [
                    "ctrl+shift+7"
                ]
            },
            {
                "command" : "newTabProfile7",
                "keys" : 
                [
                    "ctrl+shift+8"
                ]
            },
            {
                "command" : "newTabProfile8",
                "keys" : 
                [
                    "ctrl+shift+9"
                ]
            },
            {
                "command" : "nextTab",
                "keys" : 
                [
                    "ctrl+tab"
                ]
            },
            {
                "command" : "openSettings",
                "keys" : 
                [
                    "ctrl+,"
                ]
            },
            {
                "command" : "prevTab",
                "keys" : 
                [
                    "ctrl+shift+tab"
                ]
            },
            {
                "command" : "scrollDown",
                "keys" : 
                [
                    "ctrl+shift+down"
                ]
            },
            {
                "command" : "scrollDownPage",
                "keys" : 
                [
                    "ctrl+shift+pgdn"
                ]
            },
            {
                "command" : "scrollUp",
                "keys" : 
                [
                    "ctrl+shift+up"
                ]
            },
            {
                "command" : "scrollUpPage",
                "keys" : 
                [
                    "ctrl+shift+pgup"
                ]
            },
            {
                "command" : "switchToTab0",
                "keys" : 
                [
                    "alt+1"
                ]
            },
            {
                "command" : "switchToTab1",
                "keys" : 
                [
                    "alt+2"
                ]
            },
            {
                "command" : "switchToTab2",
                "keys" : 
                [
                    "alt+3"
                ]
            },
            {
                "command" : "switchToTab3",
                "keys" : 
                [
                    "alt+4"
                ]
            },
            {
                "command" : "switchToTab4",
                "keys" : 
                [
                    "alt+5"
                ]
            },
            {
                "command" : "switchToTab5",
                "keys" : 
                [
                    "alt+6"
                ]
            },
            {
                "command" : "switchToTab6",
                "keys" : 
                [
                    "alt+7"
                ]
            },
            {
                "command" : "switchToTab7",
                "keys" : 
                [
                    "alt+8"
                ]
            },
            {
                "command" : "switchToTab8",
                "keys" : 
                [
                    "alt+9"
                ]
            },
            {
                "command" : "paste",
                "keys" : 
                [
                    "ctrl+v"
                ]
            },
            {
                "command" : "copy",
                "keys" : 
                [
                    "ctrl+c"
                ]
            },
            {   "command": "closePane", 
                "keys": "ctrl+shift+w" 
            },
            { "command": { "action": "resizePane", "direction": "down" }, "keys": "alt+shift+down" },
            { "command": { "action": "resizePane", "direction": "left" }, "keys": "alt+shift+left" },
            { "command": { "action": "resizePane", "direction": "right" }, "keys": "alt+shift+right" },
            { "command": { "action": "resizePane", "direction": "up" }, "keys": "alt+shift+up" }                   
        ],
        "requestedTheme" : "system",
        "showTabsInTitlebar" : true,
        "showTerminalTitleInTitlebar" : true,
        "wordDelimiters" : " ./\\()\"'-:,.;<>~!@#$%^&*|+=[]{}~?\u2502"
    ,
    "profiles" : 
    [
        {
            "acrylicOpacity" : 1.0,
            "closeOnExit" : true,
            "commandline": "wsl.exe ~ -d Ubuntu-20.04",
            "cursorColor" : "#FFFFFF",
            "cursorShape" : "bar",
            "fontFace" : "Consolas",
            "fontSize" : 12,
            "guid" : "{7f9aa0f1-fc04-455a-b5b5-ffdbf51cfefa}",
            "historySize" : 9001,
            "icon" : "ms-appx:///ProfileIcons/{61c54bbd-c2c6-5271-96e7-009a87ff44bf}.png",
            "name" : "WSL2Bash",
            "padding" : "0, 0, 0, 0",
            "snapOnInput" : true,
            "startingDirectory" : "%USERPROFILE%",
            "useAcrylic" : false

        },
        {
            "acrylicOpacity" : 0.5,
            "closeOnExit" : true,
            "colorScheme" : "Campbell",
            "commandline" : "powershell.exe",
            "cursorColor" : "#FFFFFF",
            "cursorShape" : "bar",
            "fontFace" : "Consolas",
            "fontSize" : 12,
            "guid" : "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
            "historySize" : 9001,
            "icon" : "ms-appx:///ProfileIcons/{61c54bbd-c2c6-5271-96e7-009a87ff44bf}.png",
            "name" : "Windows PowerShell",
            "padding" : "0, 0, 0, 0",
            "snapOnInput" : true,
            "startingDirectory" : "%USERPROFILE%",
            "useAcrylic" : false
        },
        {
            "acrylicOpacity" : 0.5,
            "closeOnExit" : true,
            "colorScheme" : "Campbell",
            "commandline" : "powershell.exe -Command Start-Process -Verb RunAs cmd.exe '/c start wt.exe -p \"Windows PowerShell\"'",
            "cursorColor" : "#FFFFFF",
            "cursorShape" : "bar",
            "fontFace" : "Consolas",
            "fontSize" : 12,
            "guid" : "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
            "historySize" : 9001,
            "icon" : "ms-appx:///ProfileIcons/{61c54bbd-c2c6-5271-96e7-009a87ff44bf}.png",
            "name" : "Windows PowerShell (Admin)",
            "padding" : "0, 0, 0, 0",
            "snapOnInput" : true,
            "startingDirectory" : "%USERPROFILE%",
            "useAcrylic" : false
        },        
        {
            "acrylicOpacity" : 0.75,
            "closeOnExit" : true,
            "colorScheme" : "Campbell",
            "commandline" : "cmd.exe",
            "cursorColor" : "#FFFFFF",
            "cursorShape" : "bar",
            "fontFace" : "Consolas",
            "fontSize" : 15,
            "guid" : "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
            "historySize" : 9001,
            "icon" : "ms-appx:///ProfileIcons/{0caa0dad-35be-5f56-a8ff-afceeeaa6101}.png",
            "name" : "cmd",
            "padding" : "0, 0, 0, 0",
            "snapOnInput" : true,
            "startingDirectory" : "%USERPROFILE%",
            "useAcrylic" : true
        },
        {
            "guid": "{c6eaf9f4-32a7-5fdc-b5cf-066e8a4b1e40}",
            "hidden": false,
            "fontFace" : "Consolas",
            "fontSize" : 15,
            "name": "Ubuntu-18.04",
            "source": "Windows.Terminal.Wsl"
        },
        {
            "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
            "hidden": false,
            "name": "Azure Cloud Shell",
            "source": "Windows.Terminal.Azure"
        },
        {
            "guid": "{07b52e3e-de2c-5db4-bd2d-ba144ed6c273}",
            "hidden": false,
            "name": "Ubuntu-20.04",
            "source": "Windows.Terminal.Wsl"
        }
    ],
    "schemes" : 
    [
        {
            "background" : "#0C0C0C",
            "black" : "#0C0C0C",
            "blue" : "#0037DA",
            "brightBlack" : "#767676",
            "brightBlue" : "#3B78FF",
            "brightCyan" : "#61D6D6",
            "brightGreen" : "#16C60C",
            "brightPurple" : "#B4009E",
            "brightRed" : "#E74856",
            "brightWhite" : "#F2F2F2",
            "brightYellow" : "#F9F1A5",
            "cyan" : "#3A96DD",
            "foreground" : "#CCCCCC",
            "green" : "#13A10E",
            "name" : "Campbell",
            "purple" : "#881798",
            "red" : "#C50F1F",
            "white" : "#CCCCCC",
            "yellow" : "#C19C00"
        },
        {
            "background" : "#282C34",
            "black" : "#282C34",
            "blue" : "#61AFEF",
            "brightBlack" : "#5A6374",
            "brightBlue" : "#61AFEF",
            "brightCyan" : "#56B6C2",
            "brightGreen" : "#98C379",
            "brightPurple" : "#C678DD",
            "brightRed" : "#E06C75",
            "brightWhite" : "#DCDFE4",
            "brightYellow" : "#E5C07B",
            "cyan" : "#56B6C2",
            "foreground" : "#DCDFE4",
            "green" : "#98C379",
            "name" : "One Half Dark",
            "purple" : "#C678DD",
            "red" : "#E06C75",
            "white" : "#DCDFE4",
            "yellow" : "#E5C07B"
        },
        {
            "background" : "#FAFAFA",
            "black" : "#383A42",
            "blue" : "#0184BC",
            "brightBlack" : "#4F525D",
            "brightBlue" : "#61AFEF",
            "brightCyan" : "#56B5C1",
            "brightGreen" : "#98C379",
            "brightPurple" : "#C577DD",
            "brightRed" : "#DF6C75",
            "brightWhite" : "#FFFFFF",
            "brightYellow" : "#E4C07A",
            "cyan" : "#0997B3",
            "foreground" : "#383A42",
            "green" : "#50A14F",
            "name" : "One Half Light",
            "purple" : "#A626A4",
            "red" : "#E45649",
            "white" : "#FAFAFA",
            "yellow" : "#C18301"
        },
        {
            "background" : "#002B36",
            "black" : "#073642",
            "blue" : "#268BD2",
            "brightBlack" : "#002B36",
            "brightBlue" : "#839496",
            "brightCyan" : "#93A1A1",
            "brightGreen" : "#586E75",
            "brightPurple" : "#6C71C4",
            "brightRed" : "#CB4B16",
            "brightWhite" : "#FDF6E3",
            "brightYellow" : "#657B83",
            "cyan" : "#2AA198",
            "foreground" : "#839496",
            "green" : "#859900",
            "name" : "Solarized Dark",
            "purple" : "#D33682",
            "red" : "#DC322F",
            "white" : "#EEE8D5",
            "yellow" : "#B58900"
        },
        {
            "background" : "#FDF6E3",
            "black" : "#073642",
            "blue" : "#268BD2",
            "brightBlack" : "#002B36",
            "brightBlue" : "#839496",
            "brightCyan" : "#93A1A1",
            "brightGreen" : "#586E75",
            "brightPurple" : "#6C71C4",
            "brightRed" : "#CB4B16",
            "brightWhite" : "#FDF6E3",
            "brightYellow" : "#657B83",
            "cyan" : "#2AA198",
            "foreground" : "#657B83",
            "green" : "#859900",
            "name" : "Solarized Light",
            "purple" : "#D33682",
            "red" : "#DC322F",
            "white" : "#EEE8D5",
            "yellow" : "#B58900"
        }
    ]
}
```