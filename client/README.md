# video-platform-mern

## Introduction

This is a comprehensive fullstack project that amalgamates the functionalities of YouTube and Twitter. It offers a diverse range of features including user management, video management, tweet management, subscription management, playlist management, like management, comment management, dashboard, and server health status checks.

## Important Links

- [API Documentation](https://documenter.getpostman.com/view/19466088/2sA2xb6bG2)
- [Model](https://app.eraser.io/workspace/WOjXpohG6Y3A91JKHdw4?origin=share)
- [UI](https://www.figma.com/file/FVrnFm93HwlaI4F0so5MRE/video-platform-mern-ui?type=design&t=tMke2fxmi5zU3B43-6)


## Features

### User Management:

- **Registration, Login, Logout, and Password Reset:** Users can register for an account, securely log in, log out, and reset their passwords if necessary.
- **Profile Management:** Users have the ability to manage their profiles, including uploading avatars, setting cover images, and updating personal details.
- **Watch History Tracking:** The system tracks users' watch history to provide personalized recommendations and enhance user experience.

### Video Management:

- **Video Upload and Publishing:** Users can upload videos to the platform and publish them for public viewing.
- **Video Search, Sorting, and Pagination:** Comprehensive search functionality allows users to find videos easily, with sorting and pagination options for efficient navigation.
- **Video Editing and Deletion:** Content creators can edit and delete their uploaded videos as needed.
- **Visibility Control:** Creators can control the visibility of their videos, choosing to publish or unpublish them as desired.

### Tweet Management:

- **Tweet Creation and Publishing:** Users can compose and publish tweets within the platform, sharing their thoughts and updates.
- **Viewing User Tweets:** The system enables users to view their own tweets as well as those of other users.
- **Updating and Deleting Tweets:** Users have the ability to edit or remove their tweets after publishing.

### Subscription Management:

- **Subscribing to Channels:** Users can subscribe to channels to stay updated with new content from their favorite creators.
- **Viewing Subscriber and Subscribed Channel Lists:** Users can see who is subscribed to their channels and manage the channels they are subscribed to.

### Playlist Management:

- **Creating, Updating, and Deleting Playlists:** Users can create personalized playlists, update them, and delete them as needed.
- **Adding and Removing Videos from Playlists:** The system allows users to add videos to their playlists or remove them, providing a curated viewing experience.
- **Viewing User Playlists:** Users can access and view their own playlists, organizing their saved videos efficiently.

### Like Management:

- **Liking and Unliking Content:** Users can express their appreciation by liking videos, comments, and tweets, with the ability to undo their likes if desired.
- **Viewing Liked Videos:** Users can easily access a list of videos they have liked for quick reference.

### Comment Management:

- **Adding, Updating, and Deleting Comments:** Users can engage with videos by adding comments, editing their comments, and deleting them when necessary.

### Dashboard:

- **Viewing Channel Statistics:** Content creators can access comprehensive statistics about their channels, including views, subscribers, video metrics, and likes.
- **Accessing Uploaded Videos:** Creators have easy access to their uploaded videos for management and analysis purposes.

### Health Check:

- **Endpoint for Backend Health Verification:** The system provides an endpoint to verify the health and status of the backend infrastructure, ensuring optimal performance and reliability.


## Prerequisites

Before you begin, make sure you have the following software installed on your machine:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)
- [MongoDB](https://www.mongodb.com/)
- [Cloudinary Account](https://cloudinary.com/)


## Technologies Used

### Backend
- Node.js 
- Express.js
- MongoDB
- Cloudinary

### Frontend
- React
- Redux
- Tailwind CSS

### UI/UX
- Figma
- Locofy.ai


## Installation and Setup

### Clone the repository:

```bash
git clone https://github.com/jeevankc17/video-platform-mern.git
```


# Install required packages and start the server:



## Backend Setup

### Node.js Backend

Install required packages and start the server:

```bash
cd video-platform-mern/server
npm install
npm run dev

```

The Node.js backend server should now be running on http://localhost:3000.



## Frontend Setup

### React.js Frontend

Install React.js packages and start the development server:

```bash
cd video-platform-mern/client
npm install
npm start
```

The React.js frontend development server should now be running on http://localhost:5173/.


# Access the Application
1. Open your web browser and go to http://localhost:5173/ to access the web application.
2. Configure the .env on both client and server site.
3. To see the json response of nodejs backend go to http://localhost:3000/api/v1{specific-routes}



