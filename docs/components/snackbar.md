#Snackbar
Snackbars provide brief messages about app processes on the screen. These normally do not require user interaction, and disappear from view after a short period of time.
### Message
The message should be short and to the point, taking up no more than two line in the snackbar.
### Behavior
Snackbars appear one at a time upon an event trigger, and don't require interaction from the user. They disappear from view automatically, with the time of display ranging depending on the use case but normally between 1000ms and 5000ms.
### Placement
The snackbars display at the top of the screen and should not cover other primary navigation objects. Please see [MD Snackbar placement](https://material.io/components/snackbars#placement) guidance, outside of their decision to position them at the bottom of the screen.

![snackbar](https://github.com/user-attachments/assets/278197a4-d846-48bb-a934-a5bd1c6d3e27)

## Properties
A snackbar can contain a single action. "Dismiss", "Cancel", "Undo" actions are optional.

**None**: No actionable activities are associated with the notification
**Beside**: The default, when an actionable event is presented to the user. The action is positioned to the right of the message.
**Below**: For actions that have longer wording we can place the action below the message.
