# Task-7

# User Data Fetcher

## Overview

This is a simple web application that demonstrates how to fetch and display user data from a public API using **JavaScript's Fetch API**. It dynamically renders user information (name, email, and address) on the page, includes basic error handling, and provides a "Reload Data" button for refreshing the displayed content.

## Features 

* **Dynamic Data Fetching**: Retrieves user data from `https://jsonplaceholder.typicode.com/users`.

* **User Information Display**: Shows each user's name, email, and full address.

* **Bolded Details**: **Email** and **address** fields are bolded for readability.

* **Error Handling**: Gracefully manages network errors (e.g., when the internet connection is off).

* **Reload Functionality**: A dedicated button to refetch and refresh the user data.

* **Responsive Design**: Styles adapt for different screen sizes, including mobile.

* **Modern Styling**: Utilizes Tailwind CSS for a clean and appealing user interface.

## How to Run Locally 

To get this project up and running on your local machine, follow these simple steps:

1.  **Save the Code**: Copy the entire HTML content provided and save it as an `.html` file (e.g., `index.html`) on your computer.

2.  **Open in Browser**: Locate the saved `index.html` file and open it with any modern web browser (e.g., Chrome, Firefox, Edge, Safari).

The application will automatically fetch and display the user data upon loading.

## API Used 

The application fetches sample user data from the following public API:
`https://jsonplaceholder.typicode.com/users`

This API provides mock data for testing and prototyping, making it ideal for this demonstration.

## Project Structure 

The project consists of a single HTML file containing:

* **HTML**: Structure of the web page.

* **CSS**: Inline `<style>` block for custom styling, augmented by Tailwind CSS via a CDN.

* **JavaScript**: `<script>` block containing the logic for fetching, parsing, and displaying data, along with error handling and event listeners.

## Testing Error Handling 

To test the error handling functionality:

1.  Open the `index.html` file in your browser.

2.  **Disable your internet connection** (e.g., turn off Wi-Fi or unplug your Ethernet cable).

3.  Click the "Reload User Data" button on the page.
    You should see an error message indicating that the data could not be loaded. Re-enabling your internet connection and clicking "Reload User Data" will restore the display.

## Results
![image](https://github.com/user-attachments/assets/73d43e96-b0ab-47ca-9ec7-b149a282cfdd)
![image](https://github.com/user-attachments/assets/c68c27a3-1a67-4fc5-b72d-659742f02fb7)



