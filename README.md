# 🍿usePopcorn

A React application that allows users to search for movies using the OMDb API, rate them, and maintain a personal "watched" list.

##  ✨Features
- Real-time Search: Search for any movie in the OMDb database as you type.
- Movie Details: View detailed information including actors, director, genre, and IMDb rating.
- Interactive Rating: Rate movies using a custom-built Star Rating component.
- Watchlist Management: Add movies to your "Watched" list and track your personal ratings.
- Summary Statistics: View your average ratings and total runtime for the movies you've watched.

## 🛠️Tech Stack
- React (Functional Components)
- CSS (Vanilla CSS for styling)
- OMDb API (External data source)

## 🚀Getting Started
Follow these steps to get the project up and running on your local machine.

### 1. Prerequisites
Make sure you have Node.js installed. You will also need an API Key from OMDb.
Get a free API key here: http://www.omdbapi.com/apikey.aspx

### 2. Installation

Clone the repository:
```shell
git clone https://github.com/szabolcsstefan/usepopcorn.git
```
Navigate into the project directory:
```shell
cd usepopcorn
```
Install the dependencies:
```shell
npm install
```
### 3. Configuration
Open the App.js and replace the placeholder API key with your own:
- const KEY = "your_api_key_here";

### 4. Running the App
Start the development server:
```shell
npm run start
```
The app should now be running at http://localhost:3000.

## 📖Lessons Learned
- Effect Cleanup: Managing API abort controllers to prevent memory leaks.
- Component Composition: Avoiding "prop drilling" by using the children prop.
- Custom Hooks: Abstracting complex logic into reusable functions.
