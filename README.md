# Frontend-Assessment

## Movie Application.

### The application has 3 components:
- The Movieform component, which allows the user to enter data about movies.
- The Movieslist component, which displays the movies data.
- The Search component, which allows the user to filter through existing movies.

![ice_screenshot_20240722-071446](https://github.com/user-attachments/assets/fb4cec2d-84a4-4363-9129-15806d2a71fd)

Each movie object in the Movielist should have the following properties:
- name: The name of the movie [STRING]
- rating: The rating of the movie in the range of 0 to 100 [NUMBER]
- duration: The duration of the movie in hours [STRING]

## The application has the following functionalities:

• The Movieform component has the followings fields:
   - 'Movie Name', which accepts a string denoting the movie name.
   - 'Ratings', which accepts an integer denoting the movie's rating.
   - 'Duration', which accepts a string denoting the movie's duration in hours (h) or 
     minutes (m), e.g. in the format 132m or 2.5h.

• The Movieslist component displays the movie data sorted by duration in descending 
  order. The format is as follows:
   - {movie name}
   - Ratings: {ratings}/100
   - {duration} Hrs

• The following functionality should be implemented when the user clicks on the Add 
  Movie button:
   - If the duration format entered by the user is invalid, show the alert error message 
     with the text 'Please specify the time in hours or minutes (e.g. 2.5h or 150m)'. This 
     error message should be cleared once the user starts typing into any of the input 
     fields.
   - If all the input fields are filled with a valid value, a new movie should be added to 
     the list.
   - If the duration is entered in minutes, it must be converted to hours. For example, 
     90m should be converted and displayed as '1.5 Hrs'.

• The Search component allows the user to filter through existing movies in the directory 
  by the beginning characters.
   - It requires the user to input at least 2 characters before the search happens.
   - If the search finds no matches, the message 'No Results Found' is displayed instead 
     of the list.

• Initially, the Movieslist component and the 'No Results Found' message are not visible.

#### Submission Requirements
- Use any frontend framework (preferrably React)
- Code Repository - Provide a link to a GitHub repository containing all the code, scripts, and documentation.
- Code Deployment - Host the application on netlify or other hosting platform of your choice.
- Send the deployment and github links to contact@abiodunsamuel.com
- Also, if you have any question you can forward them to contact@abiodunsamuel.com

Note: Dealine for submission is Friday, 26th July, 2024.
Goodluck. 
