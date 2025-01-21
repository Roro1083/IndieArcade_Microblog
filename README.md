# IndieArcade: A Microblog for Indie Game Enthusiasts 🎮

IndieArcade is a microblogging platform designed for indie game lovers to share their thoughts, rate games, and connect with like-minded gamers. 
This project emphasizes accessibility, interactivity, and responsive design to provide a seamless experience on both desktop and mobile devices.

---

## Features

- **Home Page**:
  - View all posts from users in reverse chronological order.
  - Filter posts by tags; sort by newest, oldest, or most-liked.
  - View post details including: title, content, tags, like, user avatar, and timestamp.

- **User Authentication**:
  - Log in or register via Google Authentication
  - Generates a custom avatar based on the username's first letter.

- **Post Interaction**:
  - Create posts with a title, content, emojis, game ratings, and tags.
  - Real-time post updates on the home page.
  - Like others' posts and delete your own posts.
 
- **Profile Page**:
  - View personal account details (avatar, username, membership date).
  - Browse all personal posts in chronological order.
  - Personalized message for users with no posts.

- **Responsive Design**:
  - Optimized for mobile, tablet, and desktop views.

---

## My Contributions

During the development of IndieArcade, I primarily contributed to the front-end design, layout structuring, and some interactive features:
- **HTML & CSS**:
  - Designed and implemented the website's layout and structure, including the homepage, registration, and login pages.
  - Styled components such as posts, tags, footers, and navigation links.
  - Developed responsive designs using media queries to ensure mobile, tablet, and desktop compatibility.
  - Added animations for interactive elements like trash icons, likes, and star ratings.
- **JavaScript**:
  - Created event listeners for user interactions (e.g. placeholder text for incomplete post forms, star rating hover and click functionality).
  - Developed post-sorting functionality, including dropdown filters (e.g. sorting by likes, newest, oldest).
  - Contributed to asynchronous functions like `getPosts`, `addPost`, and `deletePost` to manage and display post data.
  - Formatted post timestamps for better readability.
- **Collaboration**:
  - Worked with my partner to understand and learn back-end features, including Google OAuth, database functionality, and advanced JavaScript concepts.

---

## Technical Details

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: SQLite3
- **Authentication**: Google OAuth
- **APIs**: Emoji API for enhanced post functionality
- **Deployment**: Render

---

## Known Issues

- **Google Authentication**
  - Currently, Google Authentication does not work on Render due to missing access to the Google Cloud console settings.
  - Unfortunately, the original account owner is unavailable to provide updates.
  - If you'd like to set up your own credentials to test this feature locally, please refer to [Google Cloud Console Setup Guide](https://console.cloud.google.com/).
  - For a demonstration of this feature, please see the demo video below!
- **Tag Filtering**
  - Clicking on a tag is intended to display all posts associated with that tag.
  - However, this feature is currently non-functional in the deployment and may cause the application to crash.
  - This issue will be addressed in a future update, but a demonstration of this feature can be viewed in the demo video!
---

## Demo Video

Watch the full demo of IndieArcade in action here: 
[IndieArcade Microblog Demonstration](https://youtu.be/Q_3ZmiVCELs?si=Sk75fCLMMI3z_P_f).

**Note**: The Google Authentication feature is demonstrated using a collaborator's Google account.

---

## Documentation

For a detailed walkthrough of the project with screenshots, see the [IndieArcade Functionality Overview PDF](https://docs.google.com/document/d/1LNlixTRRa_umbLDpKB1SOF_8JIcRNclKMa62kfQHp1E/edit?usp=sharing)!

---

## Local Setup Instructions
To set up this project locally, 
1. **Clone Repository**
- To clone the repo, type the following into your bash terminal:
```bash
git clone https://github.com/Roro1083/IndieArcade_Microblog.git
cd IndieArcade_Microblog
```
2. **Install Dependencies**
In the terminal, type the following to install dependencies:
```bash
npm install
```
3. **Create ENV File**
- Create a .env file in the root directory of the project with the following variables:
```
PORT=3000
DATABASE_URL=sqlite://indie_arcade.db
EMOJI_API_KEY=your-emoji-api-key
CLIENT_ID=your-google-client-id
CLIENT_SECRET=your-google-client-secret
SESSION_SECRET=your-session-secret
```
4. **Run Server**
- In the terminal, type the following to run the server:
```bash
node server.js
```
5. **Open Website**
- Open your browser and navigate to `http://localhost:3000`.

---

## Acknowledgements

- Special thanks to my project collaborator for their contributions.
- This project was completed as part of an academic assignment at the University of California, Davis.
