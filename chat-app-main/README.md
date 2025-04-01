# ChatX : Real-Time Chat Application

This is a **Real-Time Chat Application** built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to communicate in real-time through a user-friendly interface.

## Features

- **User Authentication**: Secure login and registration using JWT (JSON Web Tokens).
- **Real-Time Messaging**: Instant communication using WebSockets via Socket.IO.
- **Dynamic Theme Switching**: 32 different themes available using Daisy UI.
- **Responsive Design**: Works seamlessly on desktops and mobile devices.

## Tech Stack

### Frontend
- React.js
- Zustand
- Daisy UI
- CSS/SCSS 
- Axios 

### Backend
- Node.js with Express.js
- MongoDB for the database
- Mongoose for object data modeling
- JWT for authentication
- Socket.IO for real-time communication

## Deployment

The application is live and accessible at: https://chatx-aui0.onrender.com/* 
Deployed using Render.

## Project Structure

### Backend
```
server/
├── src/
    ├── controllers/
    ├── models/
    ├── routes/
    ├── lib/
    ├── middlewares/
    ├── index.js
```

### Frontend
```
client/
├── src/
    ├── components/
    ├── constants/
    ├── lib/
    ├── pages/
    ├── store/
    ├── App.js
    ├── index.js
```

## Usage
1. Visit the deployed application at the provided URL.
2. Register a new account or log in with existing credentials.
3. Search for users to start a private chat.
4. Start sending real-time messages.

## Future Enhancements
- **Typing Indicators**: Show when a user is typing.
- **Message Reactions**: Allow users to react to messages.
- **Notifications**: Add push notifications for new messages.

## Contributing
Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [Socket.IO](https://socket.io/)
- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

---

Enjoy chatting in real time with this MERN-based application! 🎉
