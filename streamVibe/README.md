# StreamVibe

StreamVibe is a sleek and responsive web application built with React that allows users to explore and discover shows. It features a clean UI, seamless navigation, and smooth integration with an external API to fetch show data. The app ensures a great user experience across devices with Tailwind CSS for styling and Redux for state management.

## 🚀 Features

- 🔍 **Show Listing:** Displays shows in a neat grid layout.
- 🔎 **Search Functionality:** Real-time search to filter shows.
- 📄 **Show Details:** Detailed view for each show.
- 📱 **Responsive Design:** Ensures usability across mobile and desktop.
- ⚙️ **Global State Management:** Powered by Redux.
- ❌ **Error Handling:** Handles API failures gracefully.

## 🏗️ Tech Stack

- **Frontend:** React, Redux Toolkit, Tailwind CSS
- **State Management:** Redux
- **Routing:** React Router
- **Deployment:** Netlify

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/rsakm/streamVibe.git
```
2. Navigate into the project:
```bash
cd streamVibe
```
3. Install dependencies:
```bash
npm install
```
4. Run the app:
```bash
npm run dev
```
App runs locally at `http://localhost:5173`.

## 🌐 Live Demo
Check out the live app here: [StreamVibe](https://streamvibebyrajshree.netlify.app/)

## 📤 Deployment

1. Build the project:
```bash
npm run build
```
2. Deploy using Netlify:
```bash
netlify deploy --prod
```

## 🚧 Challenges & Solutions

1. **Global State Management:** Avoided prop drilling with Redux.
2. **API Integration:** Used `createAsyncThunk` for smooth API calls.
3. **Responsive UI:** Tailwind CSS made responsiveness effortless.

## 📌 Future Enhancements
- Add user authentication.
- Implement watchlist functionality.

## 🎉 Acknowledgments
- API: [TVMaze API](https://www.tvmaze.com/api)

## 📬 Contact
For any inquiries or suggestions, feel free to reach out at [rajshreeakm@gmail.com].

---
Made with ❤️ by Rajshree

