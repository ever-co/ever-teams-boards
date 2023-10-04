# Ever Teams Boards

This repo is a modified fork of https://github.com/excalidraw/excalidraw (Copyright (c) 2020 Excalidraw, [MIT license](https://github.com/excalidraw/excalidraw/blob/master/LICENSE))

### Firebase Storage and Access-Control-Allow-Origin

If you encounter this error

<img width="1425" alt="Screenshot 2023-10-04 at 10 54 14" src="https://github.com/ever-co/ever-teams-boards/assets/35149259/1a863529-2aee-4fd3-b5b7-fb458756f322">

Fix this by following the procedure below

Open the GCP console and start a cloud terminal session by clicking the `>_` icon button in the top navbar. 
Or search for "cloud shell editor" in the search bar.

Click the pencil icon to open the editor, then create the `cors.json` file.

Run `gsutil cors set cors.json gs://ever-teams.appspot.com`

<img width="1233" alt="Screenshot 2023-10-04 at 11 00 24" src="https://github.com/ever-co/ever-teams-boards/assets/35149259/95a6aad6-3c24-4883-8c17-4b4ac4775089">
