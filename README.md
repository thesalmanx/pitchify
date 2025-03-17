## https://startups.salmann.dev

<h1 align="center">Startup Directory Platform</h1>

<div align="center">
  <br />
  <a href="https://startups.salmann.dev">
    <img src="https://github.com/user-attachments/assets/471e2baa-8781-43b8-aaed-62e313d03e99" alt="Project Banner">
  </a>
  <br />

</div>

## ⚙️ Tech Stack

- React 19
- Next.js 15
- Sanity
- TypeScript
- ShadCN
- TailwindCSS


## <a name="features">🔋 Features</a>

### 📡 Live Content API  
- Dynamically displays the **latest startup ideas** on the homepage.  
- Powered by **Sanity's Content API** for real-time updates.  

### 🔑 GitHub Authentication  
- **Seamless login** using **GitHub OAuth** for quick access.  

### ✍️ Pitch Submission  
- Users can **submit startup ideas** with:  
  - 🏷 **Title**  
  - 📝 **Description**  
  - 🏷 **Category**  
  - 🎥 **Multimedia links** (image or video)  

### 🔍 View Pitches  
- Browse through **submitted startup ideas**.  
- **Filter by category** for better discovery.  

### 📄 Pitch Details Page  
- Click on any **pitch** to view its **detailed page**.  
- Includes **multimedia, description, and relevant details**.  

### 👤 Profile Page  
- Users can **view all pitches** they have submitted.  

### 🌟 Editor Picks  
- **Admins** can **highlight top startup ideas** via **Sanity Studio**.  
- Curated selection of the **best pitches**.  

### 📊 Views Counter  
- **Tracks the number of views** per pitch instead of an upvote system.  

### 🔎 Search Functionality  
- **Efficient search** to quickly find and view startup ideas.  

### 🎨 Minimalistic Design  
- **Clean & fresh UI** with only **essential pages**.  
- **Simple and intuitive** experience for users.  

and many more, including the latest **React 19**, **Next.js 15** and **Sanity** features alongside code architecture and
reusability

## <a name="quick-start">🤸 Quick Start</a>

**Cloning the Repository**

```bash
git clone https://github.com/thesalmanx/pitchify.git
cd pitchify
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
AUTH_SECRET = ""
AUTH_GITHUB_ID = ""
AUTH_GITHUB_SECRET = ""
NEXT_PUBLIC_SANITY_PROJECT_ID = ""
NEXT_PUBLIC_SANITY_DATASET = ""
NEXT_PUBLIC_SANITY_API_VERSION = ""
SANITY_WRITE_TOKEN = ""

```

Replace the placeholder values with your actual Sanity credentials. You can obtain these credentials by signing up &
creating a new project on the [Sanity website](https://www.sanity.io/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.