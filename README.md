## Introduction

The room is an interactive 3D space sharing a context with the other visitors of the room.

## the_room_client

This component captures the client side which serves a browser context leaveraging node.js as the server which provides a react.js webpage. The basis of the webpage is a WebGL/Three.js environment.

The node server is used to deliver a initial common context, loaded by the React application. Once this has been loaded, the React application will utilize an eventstream generated from a separate service. With this model, scaling considerations are compartmentalized between the data stream and the client-side business logic.
