# Accessibility Troubleshooting
Source code provided by Mozilla Developer Network

## Tools Used
- WAVE Web Accessibility Evaluation Tool
- ChromeVox screen reader

## Accessibility Issues Addressed
### Color
The text is difficult to read because of the current color contrast.
![Screenshot of unaltered site provided by MDN](media/ColorExBeforeChange.png)

WAVE reports 19 contrast errors.
This means that WAVE detected very low contrast between foreground and background colors. Adequate contrast is necessary for all users, especially users with low vision.
![Screenshot of unaltered site with WAVE's contrast report](media/ContrastErrorReport.png)