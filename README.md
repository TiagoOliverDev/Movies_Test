<h1 align="center">Movies Test</h1>
Movies Test is a website created in React that allows the user to search by movie, filter by genre and see the details
<hr/>

![background](https://github.com/TiagoOliverDev/Movies_Test/blob/refactor/ajustar-readme/src/assets/images/ft1.png)

![background](https://github.com/TiagoOliverDev/Movies_Test/blob/refactor/ajustar-readme/src/assets/images/ft2.png)


<hr/>

# Features 

- Pesquise e assista a filmes: os usuários podem pesquisar filmes por título e assisti-los facilmente
- Genre-wise display: movies can be sorted by genre
- Trending Movies: displays a section for trending movies
- Upcoming movies: displays a section for upcoming movies
- Movie Details: users can view detailed information about each movie
- Bookmark Movies: users can bookmark their favorite movies for later viewing
- Google Authentication: users can sign in using their Google account

<hr/>

# Technology

Movies Test is built using the following technologies:

- ReactJS
- TMDB API
- Firebase Google Authentication
- Framer Motion

<hr/>

# Steps for run project

## Step 1: Clone the repository

- Choose a folder in your local machine where you want this repository to be copied

- Clone this [repository](git@github.com:TiagoOliverDev/Movies_Test.git) to your local machine 
- ```
  git clone git@github.com:TiagoOliverDev/Movies_Test.git
  ```

- Navigate to `cd Movies_Test`  directory.

- To install all the app dependencies on the command line run
- ```
  npm install
  ``` 

## Step 2: Obtain the TMDB Movies API Key and Firebase Configuration

Before starting the website, you will need to obtain the TMDB Movies API key and Firebase configuration. Follow these steps to obtain them and add them to your `.env` file.

### Get TMDB API Key 

- Go to https://www.themoviedb.org/ and login.
- Click on your user profile picture in the navigation bar, and select "Settings".
- In the settings, select "API" and generate an API key.

### Firebase Setup 

Note that Firebase is only required for Google authentication. If you are not using Google authentication in your application, you can skip this step.

- Go to the Firebase Console and create a new app.
- After creating the app, build a web app by clicking "Add App" and following the instructions.
- Clicking "Web".

![Firebase Add App Screenshot](https://github.com/TiagoOliverDev/Movies_Test/blob/refactor/ajustar-readme/src/assets/images/firebase01.png)

- Copy the configuration information provided in the green line, and paste it into the `.env` file:

![image](https://github.com/TiagoOliverDev/Movies_Test/blob/refactor/ajustar-readme/src/assets/images/firebase02.png)

- Next, to activate Google authentication in Firebase, go to **Build > Authentication** and enable Google authentication.
- To use Google authentication in localhost, add your localhost/127.0.0.1 as an Authorized Domain at **Build > Authentication > Settings > Authorized Domains** and add localhost or 127.0.0.1 to this section.

![image](https://github.com/TiagoOliverDev/Movies_Test/blob/refactor/ajustar-readme/src/assets/images/auth.png)

## Step 3: Run the project

Open folder project and open a terminal and run the following command:

```bash
npm run dev
```
This will start the application. Open a web browser and navigate to http://localhost:3000 or http://localhost:5173/ to access the website.

Note: Ensure that you have carefully added the TMDB API key and Firebase authentication configuration to your .env file. If the .env file is not working, add all the API keys and configuration manually.

<hr/>

# Demo 

- Click: https://movies-test-silk.vercel.app/
 

## Author

:man: **Tiago Oliveira**

- [GitHub](https://github.com/TiagoOliverDev/)
- [LinkedIn](https://www.linkedin.com/in/tiago-oliveira-49a2a6205/)

## 🤝 Contributing
- Contributions, issues, and feature requests are welcome!
- Feel free to check the [issues page](https://github.com/TiagoOliverDev/Movies_Test/issues).

# Show your support
Give a ⭐ if you like this project!
