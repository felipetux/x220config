# x220config

keybindings

<keybind key="XF86MonBrightnessUp">
        <action name="Execute">
                <command>xbacklight -inc 5</command>
        </action>
</keybind>
<keybind key="XF86MonBrightnessDown">
        <action name="Execute">
                <command>xbacklight -dec 5</command>
        </action>
</keybind>
<keybind key="XF86AudioRaiseVolume">
        <action name="Execute">
                <command>amixer set Master 5%+</command>
        </action>
</keybind>
<keybind key="XF86AudioLowerVolume">
        <action name="Execute">
                <command>amixer set Master 5%-</command>
        </action>
</keybind>
<keybind key="XF86AudioMute">
        <action name="Execute">
                <command>amixer set Master toggle</command>
        </action>
</keybind>
