# Instagram Clone

This project is an Instagram clone built using React.js. It aims to replicate some of the core features and functionalities of the popular social media platform Instagram, providing users with a familiar interface for browsing photos, liking, commenting, and more.


## Features

- **Authentication**: Users can sign up, log in, and log out securely.
- **Feed**: View a feed of posts from users they follow.
- **Explore**: Discover new users and content through an explore page.
- **Post Creation**: Create new posts with captions and images.
- **Interactions**: Like and comment on posts.
- **Profile**: View and update user profile information and see posts from a user's profile.
- **Responsive Design**: Ensures a seamless experience across devices.

## Technologies Used

- **React.js**: Frontend JavaScript library for building user interfaces.
- **Firebase**: Backend-as-a-Service (BaaS) platform used for authentication, database, and storage.

## Installation

To run the Instagram clone locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Nikhildevnikhil/Instagram-clone.git
```

2. Navigate to the project directory:

```bash
cd Instagram-clone
```

3. Install dependencies:

```bash
npm install
```

4. Set up Firebase:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Set up authentication with email/password.
   - Set up Firestore database and storage.
   - Copy Firebase configuration details.
   - Create `.env` file in the project root and add Firebase configuration:

   ```plaintext
   REACT_APP_FIREBASE_API_KEY=<YOUR_FIREBASE_API_KEY>
   REACT_APP_AUTH_DOMAIN=<YOUR_AUTH_DOMAIN>
   REACT_APP_PROJECT_ID=<YOUR_PROJECT_ID>
   REACT_APP_STORAGE_BUCKET=<YOUR_STORAGE_BUCKET>
   REACT_APP_MESSAGING_SENDER_ID=<YOUR_MESSAGING_SENDER_ID>
   REACT_APP_APP_ID=<YOUR_APP_ID>
   ```

5. Start the development server:

```bash
npm start
```

6. Open your web browser and navigate to `http://localhost:5173` to view the Instagram clone.

## Contributing

Contributions are welcome! If you find any bugs, have suggestions for improvements, or want to add new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by the functionality and design of Instagram.
- Thanks to [Nikhildevnikhil](https://github.com/Nikhildevnikhil) for creating and sharing this Instagram clone project.

---
