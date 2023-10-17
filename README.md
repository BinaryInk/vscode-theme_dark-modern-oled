# Dark Modern (OLED Black) Theme Set

Visual Studio Code theme designed to be the "OLED Black" variant of the default
"Dark/Light Modern" themes shipped with the application; along with a few light themes.

## Included Themes

### Dark Modern (OLED Black)

![Screenshot](images/Screenshot_0.2.0_oled-black.png)

- Backgrounds are black (#000).
- Foregrounds are white (#fff).
- Activity bar foregrounds are bright white, while the selected foreground takes on
the accent color.
- Status bar shows status through border and foreground color rather than background color.
- Overall, accent color is leaned into more to show active items. Inactive text is bright
white rather than greyed out.

### Dark Modern (OLED Black) Stylized

![Screenshot2](images/Screenshot_0.2.0_oled-black-stylized.png)

- Constants and enums: bold
- Functions: italic bold
- Types/Classes: underline
- Comments: italic

### Dim & Dim+

![Screenshot3](images/Screenshot_1.0_dim+.png)

- Foreground white is darker.
- Accent color is muted.
- (Dim+) Syntax colors are muted.
- See the Custom Colors section below to set your own color.
- Screenshot Note: I have highlighting of brackets turned on in VSCode. I would recommend disabling this feature if you plan to use Dim+.

### Light Modern (OLED) Saturated & Stylized

- Stylized is the same as Light Modern with stylization added.
- Saturated is Light Modern with the syntax coloring more saturated. The primary goal is to make
  the syntax highlighting more distinct and readable overall. The only deviations are that the 
  comments are grey instead of green and function declarations are green instead of yellow.

(I happen to think the default light theme looks great as-is, though I may provide changes down the road that amp up the contrast a touch. I primarily wanted to provide a stylized counterpart.)

### Color Variants

The following color variants are available for "Dark Modern (OLED Black)" and its stylized variant:

- Red
- Orange
- Yellow
- Green
- Teal
- Purple
- Fuchsia
- White

#### Custom Colors

Since I cannot concievably make every color under the sun, [a reminder that you
can customize any theme using your settings.json](https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme).

Below are the workbench attributes that have the accent color:

- activityBarBadge.background
- activityBar.foreground
- activityBar.activeBorder
- editorLineNumber.activeForeground
- notificationCenterHeader.background
- panelTitle.activeBorder
- panelTitle.activeForeground
- progressBar.background
- scrollbarSlider.activeBackground
- settings.modifiedItemIndicator
- checkbox.foreground
- statusBar.border
- statusBar.foreground
- statusBarItem.remoteForeground
- tab.activeForeground
- badge.background
- badge.foreground
- button.background
- button.foreground
- button.hoverBackground
- editorGutter.modifiedBackground
- focusBorder
- inputOption.activeBackground
- inputOption.activeBorder
- statusBar.focusBorder
- statusBarItem.focusBorder
- tab.activeBorderTop
- terminal.tab.activeBorder
- welcomePage.progress.foreground

There are no changes to syntax highlighting colors above.

## Most Recent Changes

- Added the following variants for standard and stylized:
  - **Light Modern (OLED) Saturated**

See CHANGELOG for previous changes.

## Disclaimer

This is not designed to reduce "burn-in" on OLED screens. This is a very
high contrast themeset and could have the opposite effect (except Dim+).

OLED, in this case, refers to the fact that the backgrounds are pitch-black.
The nomenclature derives from the fact that OLED screens are very good at
producing pure black and many UIs designed around OLED leverage this fact.
Further, "Dark theme" has come to refer to any theme that is darker, not black,
hence the initial need for the descriptor.

## Contributing

I use VSCode daily but I do not use every facet, so there may be areas in the
theme I did not give attention to if I didn't notice it.

If there's any area of the UI I have missed, or if a subsequent update changes
a background color or otherwise breaks the theme, feel free to submit an issue
or branch and propose a fix.
