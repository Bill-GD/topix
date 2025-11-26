# **topix**

### What is this and why was this made?

A cross-platform social media platform, made for both web and mobile devices.
This is my graduation project (08/2025 - 12/2025).

### Features

- Posts: Users can upload posts (text, images, video),
  manage (view, edit, delete) and interact (react, reply) with them.
- Threads: Users can create their own threads, group of related posts of any topic.
  Others can view, interact and follow threads for update notifications.
- Groups: Users can create, join and be active in groups with like-minded users.
  Groups can have posts, threads (with tags).
- Chat: Users can also chat with each other in real-time.

### Technical features

- Authentication & Authorization: Uses JWT to determine user credentials and roles.
- Media storage: Uses 3rd party service Cloudinary to store images & videos.
- Headless architecture: Backend with no influence on the UI, allows many clients
from many platform to consume the RESTful API.
- Web client is responsive for many screen sizes.
- Android client is also available.
- Uses HTTP for general API, WebSocket for real-time chat and SSE for notifications.
- Containerized using Docker.

### Notes

- Only Android client is currently available for mobile, and is limited.
- Only the backend is containerized.
- System is not deployed.
