# Co-Write

**Co-Write** is a powerful, modern, and intuitive collaborative-text editor platform, designed to enhance teamwork and productivity. Inspired by Google Docs, Co-Write allows multiple users to work on the same document simultaneously with real-time synchronization. Whether you're editing a document with colleagues, sharing it with clients, or managing multiple projects, Co-Write ensures seamless collaboration and document management.

Built using the latest web technologies, **Co-Write** leverages **Next.js** for a robust and dynamic user interface, **Liveblocks** for real-time collaboration, and **TailwindCSS** for responsive design and elegant styling. The platform is secured with **GitHub authentication**, allowing users to safely log in, manage their documents, and collaborate without worrying about security breaches.

### Key Highlights:
- **Real-Time Collaboration**: No more waiting to see changes—edit documents with your team in real time.
- **Advanced Document Management**: Create, share, and organize documents with ease, equipped with rich features like permissions management and threaded comments for in-depth discussions.
- **Seamless User Experience**: Co-Write is fully responsive, offering a smooth experience on desktops, tablets, and mobile devices.

Designed to demonstrate advanced developer skills in handling real-time environments, scalable architecture, and modern UI/UX practices, **Co-Write** is the ideal project for showcasing my expertise in web development and collaborative tools.

### 🌐 [Live Demo](https://co-write-pi.vercel.app)
![Co-Write](https://github.com/user-attachments/assets/1f28ed92-fb8e-4f40-bb9c-deb63825980c)

## Features

- **Authentication**: Secure GitHub sign-in/out using NextAuth for session management.
- **Real-time Collaboration**: Multiple users can edit documents simultaneously, with real-time updates powered by Liveblocks.
- **Documents Management**:
  - Create, delete, and share documents via email or link with view/edit permissions.
  - List all documents owned or shared, with search and sorting options.
- **Comments**: Add inline and general comments with threaded discussions.
- **Active Collaborators**: See real-time presence indicators for active collaborators.
- **Notifications**: Get notified of document shares, new comments, and collaborator activities.
- **Responsive Design**: Optimized for all devices and screen sizes.
- **Modern Tech Stack**: Built with cutting-edge tools like Next.js, TypeScript, TailwindCSS, and ShadCN for a smooth developer and user experience.

## Tech Stack

- **Frontend**: Next.js, TypeScript, TailwindCSS
- **Real-time Collaboration**: Liveblocks
- **Editor**: Lexical Editor
- **UI Components**: ShadCN
- **Authentication**: NextAuth

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine
- [Git](https://git-scm.com/) for version control

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/co-write.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd co-write
   ```

3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Set up environment variables**

   Create a `.env.local` file in the root directory and add the following variables:

   ```bash
   NEXTAUTH_URL=http://localhost:3000
   GITHUB_ID=your_github_client_id
   GITHUB_SECRET=your_github_client_secret
   ```

   For authentication, you need to set up a GitHub OAuth App. You can do that [here](https://docs.github.com/en/developers/apps/building-oauth-apps/creating-an-oauth-app).

5. **Run the development server**

   ```bash
   npm run dev
   ```

   Visit [http://localhost:3000](http://localhost:3000) in your browser to view the project.

### Deployment

Co-Write is deployed on Vercel. To deploy your own instance, follow these steps:

1. Create a Vercel account at [Vercel](https://vercel.com/).
2. Link your GitHub repository with Vercel.
3. Set up the environment variables (as mentioned above) in your Vercel project settings.
4. Deploy the project, and it will be live on your chosen domain.

## Contributing

Contributions are welcome! Feel free to open a pull request or submit an issue to report bugs or suggest new features.
