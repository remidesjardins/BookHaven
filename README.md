
# BookHaven

Welcome to BookHaven, an online bookstore where you can browse, add, and manage books easily.

## How to Launch the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/remidesjardins/retail-hub-frontend.git
   ```

2. **Navigate to the project folder**:
   ```bash
   cd front-end
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Run the development server**:
   ```bash
   npm run dev
   ```

## Project Structure

```plaintext
.
├── Dockerfile                # Configuration file for building Docker images.
├── index.html                # Main HTML file serving as the entry point of the app.
├── jsconfig.json             # Configuration file for JavaScript language features in IDE.
├── package.json              # Project dependencies and scripts.
├── package-lock.json         # Lock file with exact versions of installed dependencies.
├── src
│   ├── App.vue               # Main Vue component for the application.
│   ├── components            # Directory for reusable components.
│   │   ├── AddBookForm.vue   # Form component for adding new books.
│   │   ├── BookDetails.vue   # Component displaying book details.
│   │   ├── BookList.vue      # Component displaying a list of books.
│   │   ├── CategoryList.vue  # Component displaying a list of book categories.
│   │   ├── Header.vue        # Component for the site's header and navigation.
│   │   ├── SearchBar.vue     # Search bar component to filter books.
│   │   └── UpdateBookForm.vue # Form component for updating book details.
│   ├── main.js               # Entry point for the Vue application.
│   ├── router                # Directory for routing configuration.
│   │   └── index.js          # File defining routes for the application.
│   ├── store                 # Directory for Vuex store (state management).
│   │   └── index.js          # Vuex store configuration and initial state.
│   └── views                 # Directory for page views.
│       ├── CategoryBookList.vue # View displaying books in a specific category.
│       ├── Favorites.vue     # View displaying user's favorite books.
│       ├── Home.vue          # Home view displaying the main content.
│       ├── LogIn.vue         # View for the login form.
│       └── SignIn.vue        # View for the signup form.
└── vite.config.js            # Configuration file for Vite, the front-end build tool.
```

## Documentation

The documentation for this project is generated with [Swimm](https://swimm.io/), an AI-powered documentation tool. For more information about Swimm, visit their [website](https://swimm.io/).

In the `docs` folder in the root of the project, you’ll find markdown files for each component. Each file contains detailed explanations about the code and its functionalities.

The PDF for the user manual is also located in the `docs` folder.

## Links

- **GitHub Repository**: [https://github.com/remidesjardins/bookhaven.git](https://github.com/remidesjardins/retail-hub-frontend.git)
- **Deployed Website**: [https://bookhaven.site](https://bookhaven.site)

***This README.md is generated with ChatGPT***