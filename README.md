# sortable

## Description

The sortable is a web application that allows users to organize and explore data about superheroes. This project was created as a response to the following challenge:

> You are a villain and your dream is to get rid of those annoying, yoga-pant-wearing, weird masked superheroes. You never understood why some of them are considered to be superheroes, just because they are rich. Others annoy you with their philosophical speeches.
> 
> We've found confidential information about those superheroes. Your task is to build a web page to organize all the data about those smartypants.

## Features

- Fetch and display superhero data from a JSON file
- Interactive search functionality
- Sortable columns
- Pagination with adjustable page size
- Responsive design

## Files

- `index.html`: The main HTML structure of the application
- `style.css`: CSS styles for the application
- `sortable.js`: JavaScript code for functionality

## Setup

1. Clone this repository or download the files.
2. Ensure you have an `images` folder with:
   - `search.png`: An icon for the search input
   - `hero.png`: A background image for the page
3. Open `index.html` in a web browser to run the application.

## How It Works

1. **Data Fetching**: On page load, the application fetches superhero data from a JSON file.

2. **Data Processing**: The fetched data is stored in memory and initially sorted.

3. **Display**: The data is displayed in a table format, showing key information about each superhero.

4. **Search**: Users can search for heroes by name. The search is dynamic, updating results as the user types.

5. **Sorting**: Clicking on column headers sorts the data based on that column. Repeated clicks toggle between ascending and descending order.

6. **Pagination**: Users can navigate through pages of results and adjust the number of items displayed per page.

7. **Responsive Design**: The layout adjusts for different screen sizes, ensuring usability on various devices.

## Usage

- **Search**: Type in the search box to filter heroes by name.
- **Sort**: Click on any column header to sort by that column. Click again to reverse the order.
- **Paginate**: Use the page buttons at the bottom to navigate through results. Select a page size from the dropdown menu.

