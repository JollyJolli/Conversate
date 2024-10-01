# **Conversate** 💬✨  
A simple yet powerful real-time chat web app for seamless conversations.

## **Overview**  
**Conversate** is a real-time chat application that allows users to communicate instantly by joining chat rooms. The app supports text messaging, geolocation sharing, and real-time updates of participants in each room. Whether you're chatting one-on-one or in a group, Conversate keeps everything smooth and responsive. Currently in development, it aims to provide a user-friendly experience with core functionality already implemented.

## **Features** 🌟

- 💬 **Real-time Messaging**: Exchange messages instantly with others in the same chat room.
- 👥 **Group Chat**: Create or join rooms for group conversations.
- 🌍 **Location Sharing**: Easily share your current location with others in the room.
- 🧑‍🤝‍🧑 **Dynamic User Updates**: Stay updated on who’s currently active in the room with live user lists.
- 📜 **Autoscroll**: Automatic scrolling to the latest messages, ensuring a smooth conversation flow.
- 😊 **Emoji Support**: Express yourself with emojis in your messages.
- 📎 **File Sharing** *(Coming Soon)*: Share documents, images, and other files within the chat.

## **Tech Stack** ⚙️  
Conversate leverages the following technologies to provide a seamless experience:

- **Front-end**:  
  - 🎨 HTML5, CSS3 (minified for production)  
  - 📝 Mustache.js for templating  
  - 🕰️ Moment.js for time formatting  
  - ✨ Vanilla JavaScript for dynamic behavior and DOM manipulation

- **Back-end**:  
  - ⚡ **Socket.io** for real-time communication  
  - 🚀 Express.js (Node.js) as the server framework  

- **Other Integrations**:  
  - 🌍 **Geolocation API** for sharing location data  
  - 🛠️ **Qs** for parsing query strings

## **Getting Started** 🚀  

To get started with Conversate on your local machine, follow these steps:

### **Prerequisites** 📋

Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your machine.

### **Installation** 💻

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/conversate.git
   ```

2. **Navigate into the project directory**  
   ```bash
   cd conversate
   ```

3. **Install dependencies**  
   ```bash
   npm install
   ```

4. **Run the application**  
   ```bash
   npm start
   ```

5. Open your browser and go to:  
   ```
   http://localhost:3000
   ```

## **Usage** 🎯

1. On the landing page, enter your **display name** and the **room** you want to join.
2. Once inside, you can:
   - 📝 Send messages to everyone in the room.
   - 🌍 Share your location by clicking the "Send Location" button.
   - 👥 View a real-time list of users currently in the room on the sidebar.

## **Folder Structure** 📁  
```
Conversate/
├── public/
│   ├── css/
│   │   └── styles.min.css     # Minified CSS for the app
│   ├── img/
│   │   └── favicon.png        # Favicon image
│   ├── js/
│   │   └── chat.js            # Client-side chat logic
│   ├── index.html             # Entry page for the app
│   └── chat.html              # Chat room page
├── server/
│   └── server.js              # Main server code
├── package.json               # NPM package file with dependencies
└── README.md                  # You are here!
```

## **Contributing** 🤝  

We welcome contributions! To contribute to Conversate, follow these steps:

1. **Fork the repository** 🍴  
   Click the "Fork" button at the top-right of this page.

2. **Clone your fork**  
   ```bash
   git clone https://github.com/yourusername/conversate.git
   ```

3. **Create a new branch**  
   ```bash
   git checkout -b my-feature-branch
   ```

4. **Make your changes** ✍️  
   Implement your feature or fix the bug.

5. **Commit your changes**  
   ```bash
   git commit -m "Add new feature"
   ```

6. **Push your branch to your fork**  
   ```bash
   git push origin my-feature-branch
   ```

7. **Submit a pull request**  
   Go to the original repository and create a pull request from your branch.

## **Future Enhancements** 🔮

- 📎 **File Sharing**: The ability to share files such as images and documents in the chat.
- 🔒 **Private Messaging**: Allow users to initiate one-on-one conversations within rooms.
- 😊 **Message Reactions**: Enable users to react to messages using emojis.

## **License** 📄  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## **Acknowledgements** 🙏  

- 💡 The project utilizes **Mustache.js** for clean, logic-less templates.
- ⚡ Real-time functionality is powered by **Socket.io**.
- 🕰️ Thanks to **Moment.js** for making date and time formatting a breeze.
