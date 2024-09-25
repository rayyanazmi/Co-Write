Here’s a comprehensive README file for your **Co-Write** project:

---

# Co-Write

[![Vercel Deployment](https://vercel.com/button)](https://co-write-pi.vercel.app)

**Co-Write** is an online collaborative text editor inspired by Google Docs. Built to enable real-time collaboration, it allows multiple users to edit the same document, share it securely, and manage their documents efficiently. The platform is designed to be fully responsive and intuitive, providing a seamless experience across devices.

### 🌐 [Live Demo](https://co-write-pi.vercel.app)

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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Let me know if you need any further adjustments!
