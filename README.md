
# Aatmanirbhar Samakraman

[![IMAGE ALT TEXT HERE](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=lRjCKhczHtY)

This Project is basically a Application of our Project [Aatmanirbhar Sanchar](https://github.com/BE-Project-VESIT-AatmaSanchar/Aatmanirbhar-Sanchar)

    Using our encryption process, we have developed an auto synchronization file app useful in situations where the user repeatedly stores important readings in the format of a file in a selected directory and wants to securely upload
    the same to a remote server automatically when a new file comes in that particular directory.

This part of Repository contains the Mobile Application code of the application.

Server Side code of the same can be found [here](https://github.com/BE-Project-VESIT-AatmaSanchar/Auto-File-Sync-App-Server)

Now every time a new file is stored in that specific directory it triggers the application and the file is
automatically uploaded to the remote servers and the local stored file is moved to the second directory. This transfer of
file to the server takes place using the Multi-Part technology after being encrypted with our XOR-encryption
process.

    The user first selects a specific directory to be continuously monitored by the app. 
    He/she then selects another directory where he wants these files to be moved to once uploaded to the server. 
    He then presses the start syncing button to activate the background process

![test](https://github.com/BE-Project-VESIT-AatmaSanchar/Auto-File-Sync-App/blob/master/screenshots/image7.png) 
![test](https://github.com/BE-Project-VESIT-AatmaSanchar/Auto-File-Sync-App/blob/master/screenshots/image23.png)
![test](https://github.com/BE-Project-VESIT-AatmaSanchar/Auto-File-Sync-App/blob/master/screenshots/image22.png)
![test](https://github.com/BE-Project-VESIT-AatmaSanchar/Auto-File-Sync-App/blob/master/screenshots/image20.png)

Along with the file, the current location coordinates of the user are also sent which is then used to display a
tracking history on a [web-based map UI](http://file.aatmanirbhar-sanchar.live/) for easy analysis Along with various filters for ease of use

Code for the Map Based Tracking system is available [here](https://github.com/BE-Project-VESIT-AatmaSanchar/Map-Tracking-for-Auto-Sync-App)

## Deployment

To deploy this project please refer the following link which contains the instructions for UBUNTU OS,CENT OS,WINDOWS 

[Deployment Cookbook](https://docs.google.com/document/d/1fSwpv6ZCRhyami0U6lCNLExHZtTIIsLdNf6ZaCJpGYY/edit#heading=h.fguplrpp8q3l)
