# Search-Engine


# Project: Advanced Search Engine with History and Chatbot Integration

### Description
This project is an **advanced search engine** featuring:
#### 1. **Search history tracking** to save and revisit user queries.
#### 2. **Dynamic light/dark mode toggle** with persistent preferences stored locally.
#### 3. **Chatbot integration** via Chatbase for conversational assistance.
#### 4. **Google Custom Search Integration** for delivering precise and accurate results.

The project combines a modern UI with interactive functionality, enhancing the user experience.

---

### Features

#### **1. Search Engine with History**
- **Search Suggestions**: Real-time suggestions powered by Google Custom Search Engine.
- **Search History**: Tracks user queries and displays a history list with options to revisit or delete entries.
- **Persistent Storage**: Saves history and dark mode preferences in `localStorage`.

#### **2. Dark Mode**
- **Toggle Button**: Switch between light and dark themes.
- **Persistent Theme**: Remembers the user's last selected theme using `localStorage`.

#### **3. Chatbot Integration**
- **Chatbase**: A chatbot embedded to assist users with queries and provide conversational interaction.

#### **4. Enhanced Design**
- **Glassmorphism Style**: Stylish UI with transparency effects.
- **Responsive Layout**: Fully responsive for different screen sizes.
- **Animated Greetings**: Updates greeting dynamically based on the time of day (e.g., "Good Morning").

---

### File Structure
```
.
├── index.html      # Main HTML file containing structure and logic
├── assets/         # (Optional) Static assets like images or additional CSS/JS
└── README.md       # Project documentation (this file)
```

---

### Installation and Setup

#### 1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Kushal-911/Search-Engine.git
   cd Search-engine
   ```

#### 2. **Open the Project**:
   - Open the `index.html` file in any modern web browser to view the application.

#### 3. **Run On Live Server**:

---

### Usage

#### **Search Functionality**
#### 1. Enter a query in the search bar.
#### 2. Results are displayed dynamically below the search bar.
#### 3. Press Enter or click the search button to initiate the search.

#### **Search History**
#### 1. The history list saves your last 10 searches.
#### 2. Click on a history item to revisit a previous search.
#### 3. Use the "Clear History" button to delete all saved searches.

#### **Dark Mode**
#### 1. Toggle the theme by clicking the moon/sun icon.
#### 2. The theme preference is saved and applied on the next visit.

#### **Chatbot Integration**
#### 1. The chatbot appears as an embedded widget.
#### 2. Use it to ask questions or get assistance.

---

### Key Components

#### **1. Search History**
- **Local Storage**: Stores queries persistently.
- **Interactive List**: Allows revisiting or deleting queries.

#### **2. Theme Toggle**
- **Persistent Preferences**: Dark mode settings are saved locally.
- **Intuitive Toggle**: Switch themes instantly with smooth animations.

#### **3. Google Custom Search Integration**
- **Powered by Google**: Provides precise and accurate search results.
- **Custom Styling**: Styled to match the overall theme and design.

#### **4. Chatbase Integration**
- **Conversational Assistance**: Embedded chatbot for user queries.
- **Dynamic Loading**: Loads only when required to optimize performance.

---

### Technologies Used
- **HTML5**: Structuring the web application.
- **CSS3**: Styling, including glassmorphism effects and animations.
- **JavaScript (Vanilla)**: Implements interactivity like search history, theme toggling, and chatbot integration.
- **Google Custom Search Engine**: Delivers search results.
- **Chatbase**: Provides the chatbot functionality.

---

### How It Works

#### 1. **Search History**:
   - Listens for user input and saves queries to `localStorage`.
   - Displays the saved history dynamically and allows interactions.

#### 2. **Dark Mode**:
   - Toggles CSS variables to switch between light and dark themes.
   - Saves the user's preference in `localStorage`.

#### 3. **Chatbot**:
   - Embedded using Chatbase's script.
   - Provides conversational support to users.

---

### Future Enhancements
- **Integration with AI APIs**: Use APIs like OpenAI or Gemini to enhance chatbot capabilities.
- **Scam Detection**: Add features to flag suspicious links in search results.
- **User Authentication**: Allow users to log in and save personalized settings.
- **Enhanced Analytics**: Track user interactions for improving search accuracy.

---

### License
This project is licensed under the MIT License.

---

### Acknowledgments
- **FontAwesome**: For providing free icons.
- **Google**: For Custom Search Engine integration.
- **Chatbase**: For chatbot functionality.

For further assistance, contact kushal_rs@ma.iitr.ac.in


## Screenshots

#### This is light mode
![App Screenshot](https://github.com/user-attachments/assets/e97a6d64-acef-4e41-820e-5186b5b836e6)

#### This is dark mode
![App Screenshot](https://github.com/user-attachments/assets/d2058ad8-6617-40bc-8f96-1a9ee611ff3a)

#### This shows search suggestion and completion.
![App Screenshot](https://github.com/user-attachments/assets/bf806825-6a05-4535-b1ac-15d497c79456)

#### This is interaction with chatbot
![App Screenshot](https://github.com/user-attachments/assets/fa34e533-2fdd-4c79-8f2f-5c313c3613ee)

#### This results of the search
![App Screenshot](https://github.com/user-attachments/assets/b1cf9ebb-3acd-430d-b371-8ecea93a10ba)


