# YCdirectory

YCdirectory is a web application designed to help startup founders showcase their ideas to a broader audience. The platform connects startups with potential customers, users, and venture capitalists, helping founders gain traction and funding opportunities.

## 🌟 Features

### 1. **Pitch Your Startup**
   - Users can create detailed posts about their startups, including name, description, and other essential details.
   - Startups are showcased on the platform to attract attention from customers and investors.

### 2. **User Profiles (GitHub Integration)**
   - Authentication is handled via **GitHub** using `NextAuth.js`.
   - User profiles display:
     - Name
     - GitHub username
     - Profile image
     - GitHub bio
   - This ensures credibility and fosters a professional community.

### 3. **Startup Details**
   - Each startup post includes:
     - Date of creation on the platform.
     - Title, description, category, img url and the pitch.
     - The total number of views received, providing insight into its popularity.
   - Posts are dynamically fetched and displayed.

### 4. **Editors' Picks Playlist**
   - Highlighted startups curated by the platform's team to feature the best and most promising ideas.
   - Provides additional exposure to standout startups.

### 5. **Dynamic Rendering**
   - Built with **Next.js** to leverage features like:
     - Server-Side Rendering (SSR): Optimizes loading times for initial requests.
     - Incremental Static Regeneration (ISR): Keeps content up-to-date without slowing down performance.
     - Progressive Page Rendering (PPR): Enhances navigation between pages.

---

## 💻 Tech Stack

- **Frontend:**  
  - React.js  
  - Next.js  
  - TailwindCSS  
  - ShadcnUI (for consistent and modern design components)

- **Backend & CMS:**  
  - Sanity (for managing and fetching content)  

- **Authentication:**  
  - NextAuth (GitHub-based authentication)  

- **Design:**  
  - Figma (implemented uing a Figma design)

---

## 🚀 How It Works

1. **Sign Up/Sign In:**  
   - Users authenticate via their GitHub account.

2. **Create a Startup Post:**  
   - Add details about the startup, including its name and description.

3. **Explore Startups:**  
   - Browse posts from other users and discover promising ideas.  
   - View detailed startup stats, such as creation date and view count.

4. **Editors' Picks:**  
   - Explore the "Editors' Picks" section to see featured startups.

---

## 📷 Screenshots

1. **Home Page:**  
   Displays all the startups with their respective details.

2. **Startup Page:**  
   Detailed view of a single startup, including stats and the creator's profile.

3. **Editors' Picks Playlist:**  
   A curated list of top-performing startups.

---

## 🛠️ Installation and Setup

Follow these steps to set up YCdirectory locally:

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/ycdirectory.git
   cd ycdirectory
