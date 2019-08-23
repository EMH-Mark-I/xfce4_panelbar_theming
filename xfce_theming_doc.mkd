## XFCE 4.14 Panelbar Theming

----

### CSS Selectors

#### Classes:

    .xfce4-panel
    .tasklist

#### ID's:

    #whiskermenu-button
    #xfce4-notification-plugin
    #xfce4-power-manager-plugin
    #pulseaudio-button
    #clock-button

#### Elements

    wnck-pager

### Plugin themeing examples

Panelbar background color.

    .xfce4-panel.background {
      background-color: rgba(36, 36, 36, 0.8); }

Tasklist toggle button background colour, text color, and border radius.

    .tasklist .toggle {
      background-color: lightblue;
      color: black;
      border-radius: 3px; }

<p align="left">
<img src="Screenshots/tasklist_button.png" alt="Panelbar tasklist button"/>
</p>

Whisker Menu panel button.

    #whiskermenu-button label {
      color: lightblue;
      font-weight: bold;
      font-style: italic; }

<p align="left">
<img src="Screenshots/whiskermenu_button.png" alt="Whisker Menu panel button"/>
</p>


Pulseaudio menu mpris buttons.

    #pulseaudio-button menu .linked button {
      color: lightblue;   /* This will apply a colour to the mpris button icons */
      border-color: gray; }  /* This will apply a cololur to the mpris button border */

<p align="left">
<img src="Screenshots/pulseaudio_menu.png" alt="Pulseaudio menu MPRIS buttons"/>
</p>

*The pulseaudio menu contains common GTK widgets such as a scale, trough, switch, and slider.*

Workspace switcher colours for selected and active states.

    wnck-pager:selected {
      background-color: lightblue; }
    wnck-pager:hover {
      background-color: gray; }

<p align="left">
<img src="Screenshots/workspace_switcher.png" alt="Panelbar workspace switcher"/>
</p>