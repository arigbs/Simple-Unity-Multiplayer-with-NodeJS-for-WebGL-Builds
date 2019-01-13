Amended scripts for the client and server from the video tutorial series for unity multiplayer networking with socket io.
Originally by Adam Carnagey
link to video tutorial series: https://www.youtube.com/watch?v=tn3cWcSYmHE&list=PLH83kaN0EWK5wkiNhGlhfSI_nGDcR1DX8&index=1
link to original github repo: https://github.com/acarnagey/Unity-Multiplayer-Networking-NodeJS

Adapted by Ayodele Arigbabu in January 2019 to work with the asset 'SocketIO for Native and Webgl builds' by Daspete
assetstore link here: https://assetstore.unity.com/packages/tools/network/socketio-for-native-and-webgl-builds-76508

To run this, download the 'SocketIO for Native and Webgl builds'asset and place the Unity SocketIO folder in the asset folder of the Unity project.
Unzip the server package contained in the asset folder and build dependecies by running 'npm install' and a command prompt launched in the location  
of the server folder. Then run 'node server.js' to launch the server.

Create a Webgl build of the unity project into the same folder that contains the server, and launch and point a browser or more at http://localhost:3000/
you can also play from the unity scene. Entering a player name and pressing the button would launch a new player visible on all clients on the network.

For reference, in case something gets screwed, all gameobjects in the scene have been made into prefabs at the location: Assets > Scenes > ScenePrefabs

This sample project is hosted here by Ayodele Arigbabu under an ISC License (https://en.wikipedia.org/wiki/ISC_license)