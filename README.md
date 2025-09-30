# Social-Media-Dashboard

COMPANY: CODEC TECHNOLOGIES

NAME: KEMIDI SRI CHARAN

DESIGNATION: MERN STACK DEVELOPER INTERN

LOCATION: HYBRID / INDIA

DURATION: 05/09/2025 to 05/10/2025

# DESCRIPTION:

The Social Media Dashboard is a full-stack web application developed using the MERN stack (MongoDB, Express.js, React.js, and Node.js) with additional integration of Socket.IO for real-time communication and Redis for notifications. The main goal of this project is to simulate the core features of a modern social media platform such as Instagram or Twitter, while also providing an analytics dashboard to measure user engagement.

At its foundation, the project allows users to create profiles and interact with each other through posts, likes, comments, and follow/unfollow actions. Each user can register and maintain a profile, and they can upload media content to share with others. Posts created by users are stored in MongoDB, a NoSQL database, where the schema captures important details such as the author, content, likes, and comments.

One of the most important parts of the project is real-time communication. By using Socket.IO, users are able to send and receive messages instantly without refreshing the page. When User A sends a message to User B, the message is transmitted via sockets and displayed in real time on the recipient’s chat window. This creates an interactive, dynamic user experience similar to popular messaging apps.

The application also supports likes, comments, and follows. These interactions trigger notifications so that users stay updated on activities involving their profiles or posts. To make notifications scalable and efficient, Redis Pub/Sub is integrated. Whenever an event such as a like, comment, or new message occurs, the backend publishes a notification to Redis. Any user who is the intended recipient automatically receives the event through a subscribed channel. On the frontend, Socket.IO listens for these notifications and displays them as instant alerts.

Another key highlight of the project is the analytics dashboard. Using MongoDB’s aggregation framework on the backend and data visualization libraries such as Recharts on the frontend, the dashboard presents insights about user engagement. For example, it can display the number of registered users, total posts created, and other useful metrics. These insights are presented in the form of interactive charts, enabling administrators or developers to better understand how users are engaging with the system.

From a technical perspective, the backend is built with Node.js and Express.js, managing routes for user registration, posting content, liking, commenting, and analytics. MongoDB serves as the database to store all user and post information. Redis is connected through the ioredis client for publishing and subscribing to notification events. On the frontend, React.js provides a clean and modular interface with dedicated pages for the feed, chat, and analytics dashboard.

In summary, this Social Media Dashboard project demonstrates the integration of multiple modern web technologies into a single working prototype. It provides user profiles with media uploads, real-time messaging, social interactions, a notification system powered by Redis, and an analytics dashboard. Even though it is a simplified version of real platforms, it successfully captures the essence of social networking applications and showcases the practical use of the MERN stack for building scalable, real-time, and user-friendly web apps.

# OUTPUT:

