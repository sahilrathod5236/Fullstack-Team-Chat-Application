# Fullstack Team Chat Application: Next.js 13, React.js, TypeScript, Tailwind CSS, MongoDB, Prisma, Socket.io 

Description: 

A chat application built for users to chat (send messages) via Text, Audio and Video Channels to other users (members of the same channel) and also allows direct communication between users.

Features:

- Real-time messaging using Socket.io
- Create Text, Audio and Video call Channels
- Send attachments (images and PDF) as messages using UploadThing
- Delete & Edit messages in real time for all users
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (Tanstack Query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Toggle between Light and Dark mode
- Websocket fallback: Polling with alerts
- MongoDB database 
- ORM using Prisma
- Authentication with Clerk
- Server side APIs are handled in route handlers (app/api)
- Data Fetching is done in server react components by directly accessing the database (without API)
