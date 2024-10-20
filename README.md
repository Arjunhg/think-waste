## Youtube Demo Link for the Project:

[https://youtu.be/SWYvxlB9os8](https://youtu.be/SWYvxlB9os8)

## Getting Started

Run the given command to install all the neccessary packages:

```bash
npm install
# or
bun install (recommended)
```

To make this project create .env file and add the given key value pairs to it:

```bash
NEXT_DATABASE_URL= 'your dastabase connection string (in this case we are using postgress neonDB)'
NEXT_WEB3_AUTH_CLIENT_ID= 'your web3 authentication client ID'
NEXT_PUBLIC_GEMINI_API_KEY= 'your gemini api key'
```

Now, run the development server:

```bash
npm run dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Inspiration  ✨
The idea for GreenGuard was sparked by a pressing need to improve waste management, especially in densely populated areas. With waste piling up and improper disposal becoming more common, I was driven to create a system that not only makes waste reporting easier but also motivates people to act responsibly through rewards. The concept evolved from recognizing how small contributions can collectively lead to massive environmental impacts, and Iwanted to build something that could foster collective responsibility. 🌍

## What it does 🚮
GreenGuard is a waste management platform that allows users to report waste in their vicinity, track their contributions, and earn rewards for their efforts. Here's how it works:

**1. Reporting:** Users can report waste with details like location, type, and status via Google Maps integration.

**2. Rewards:** Each user’s contributions are tracked, and they earn points that can be redeemed for rewards.

**3. Notifications:** Real-time notifications keep users informed about the status of their reports.

**4. Collective Impact:** The platform also tracks the collective waste managed, showing how individual efforts contribute to a larger cause.

**5. Classing:** Implemented AI-based waste classification, allowing users to classify the type of waste automatically with a photo.

## How it was built 🛠️
GreenGuard was developed using a robust tech stack:

**1. Next.js:** For building the web application’s frontend and backend.

**2. ShadCN:** To style components and create a sleek UI.

**3. DrizzleORM:** With PostgreSQL (hosted on Neon) to interact with the database, DrizzleORM allowed us to safely manage tables and relationships in TypeScript.

**4. ShadCN:** For secure authentication, using the Sepolia network for decentralized identity management.

**5. Google Maps API:** For location-based waste reporting.

**6. React Hot Toast:**  For seamless notifications.

**7. Lucide-React:** To enhance the UI with icons and a modern design language.
Gemini AI for some experimental features aimed at enhancing waste management analytics.

## Challenges Faced 🤔
One of the biggest challenges was integrating Web3Auth with our database system. Managing authentication while ensuring users could create reports without running into authorization issues was tricky. Additionally, integrating the Google Maps API for precise waste location reporting required precise handling of APIs and managing the complexities of location suggestions.

Another challenge was designing a user interface that kept everything clean while still providing powerful functionality, such as showing real-time notifications and the overall collective waste impact.

## Accomplishments 🎉

**1.** Successfully integrating **Web3Auth** with database, enabling secure and decentralized user management.

**2.** Making use of **DrizzleORM**, which allowed to manage the database with TypeScript’s safety features, streamlining development.

**3.** Implementing a smooth user experience that allows for real-time waste reporting with **Google Maps API** integration and an intuitive rewards system.

**4.** Building a system that encourages collective action for environmental betterment, which I believe has real potential for making a difference.

## What I learned 📚
Throughout the development process, I gained valuable insights into working with decentralized authentication systems like Web3Auth, how to manage databases using DrizzleORM with PostgreSQL, and the importance of real-time interactivity in user experiences. I also learned the intricacies of API integration, especially with Google Maps, and how to handle various edge cases that come with location-based services.

## What's next for GreenGuard 🚀
In the future, the plan is to:

**1.** Improve collective tracking by adding gamification elements where neighborhoods or communities can compete to reduce waste.

**2.** Expand the rewards system by partnering with eco-friendly brands.

**3.** Add support for mobile applications to increase accessibility and engagement.

**4.** Enhance the real-time collaboration features to make it easier for city authorities and waste management services to respond to reports.

GreenGuard is just getting started, and its exciting to see where this project will lead in helping cities become cleaner and more sustainable! 🌱

