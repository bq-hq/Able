# Snackbar

## Overview
The Snackbar component is a compact, temporary notification that appears at the edge of the screen to inform users of a process, action, or event. It can include an icon, a message, and an optional action button, making it perfect for lightweight feedback or quick actions.

![tooltip](https://github.com/user-attachments/assets/58bb6c71-afd1-4325-9b3b-0ce36640261f)


## Properties
Note: For each property, the **bolded** value indicates the default setting.

- **Sb** – Toggle Snackbar visibility  
  Values: **Visible**, Hidden

- **Sblcn** – Toggle icon visibility  
  Values: **Visible**, Hidden

- **SbBtn** – Toggle action button visibility  
  Values: **Visible**, Hidden

- **SbStyle** – Style variant  
  Values: **none** (string)

- **SblcnSrc** – Icon source  
  Values: **default** (string)

- **SbTxtSrc** – Snackbar message text  
  Values: **Snackbar message goes here and wrap** (string)

- **SbBtnTxtSrc** – Action button text  
  Values: **Action** (string)

- **SbBtnLink** – Action button link  
  - **Type**: link, document, phone, email, arrow, custom  
  - **URL**: **#** (string)  
  - **Open in**: **This tab**, New tab  
  - **Preload**: **Default** (string)

- **SbBtnClick** – Action button click event  
  Values: (event handler)

- **SbLoc** – Snackbar location  
  Values: **top** (string)
