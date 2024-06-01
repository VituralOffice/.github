## Virtual Office Space - Your Collaborative Workspace in the Cloud

**Description**

This is a collaborative virtual office platform designed to empower geographically dispersed teams to work together seamlessly in a simulated office environment. It offers a suite of features to enhance communication, productivity, and team engagement.

**Features**

* **Immersive 2D Workspace:** Create a realistic and engaging virtual office experience with customizable avatars, offices, and meeting rooms.
* **Real-Time Communication:** Foster seamless collaboration through features like video conferencing, instant messaging, and screen sharing.
* **Security and Privacy:** Implement robust security measures to protect user data and ensure a safe virtual work environment.
* **File Sharing and Collaboration:** Share documents, presentations, and other files securely within your virtual office for easy access and co-editing.
* **Customizable Layouts: (planned)** Designate workspaces, meeting rooms, and social areas to match your team's needs and preferences.
* **Project Management Tools (planned):** Organize tasks, track progress, and streamline workflows using built-in project management tools.


**Usage**

1. **Sign Up:** Create an account or log in using your existing credentials.
2. **Customize Your Avatar:** Choose an avatar that represents you in the virtual office.
3. **Join or Create a Workspace:** Find an existing workspace to join or create your own for your team.
4. **Explore Your Workspace:** Navigate through your virtual office, interact with colleagues, and access features like video conferencing

**Thanks to Open Source** 

* The development of this virtual office space product is made possible in part by the amazing open-source community. We'd like to express our gratitude for the following open-source tools that we leverage:

    [Skyoffice](https://github.com/kevinshen56714/SkyOffice), [Colyseus](https://colyseus.io/), [Phaser3](https://phaser.io/), [Peerjs](https://github.com/peers/peerjs)

* Without these fantastic open-source projects, creating this virtual office space platform would be much more challenging. Thank you to all the developers who contribute their time and effort to the open-source ecosystem!

**Optimizing from PeerJS to mediasoup** 

We acknowledge that PeerJS, while simple to use, might not be the most scalable solution for real-time communication in a large virtual office environment. We are considering migrating to mediasoup, a more robust WebRTC server implementation, for the following reasons:

* **Scalability**: mediasoup is designed to handle a large number of concurrent connections, making it suitable for supporting many users in your virtual office.
* **Security**: mediasoup offers enhanced security features compared to PeerJS, which is crucial for protecting user data and privacy in a collaborative environment.
* **Flexibility**: mediasoup provides more control over the WebRTC connection, allowing for customization and optimization of media streams for different network conditions.