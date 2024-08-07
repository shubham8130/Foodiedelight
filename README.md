# Restaurant Management System Assessment

## Introduction

This assessment demonstrates the creation of a basic Restaurant Management System using React for the frontend,
Used Dummy mock api for reference to show the other way but right now i have used in memory storage and updation .

## Features

### 1. Display Restaurants

- **Route**: `http://localhost:3000`
- **Description**: Displays a list of all available restaurantspted.

### 2. Add Restaurant

- **Popup Form**: A popup form is provided to add a new restaurant.
- **Validation**: The form includes required field validation to ensure that all necessary information is provided.
- **Fields**: Includes fields for the restaurant's name, description,location

### 3. Edit Restaurant

- **Edit Form**: Allows users to edit the details of an existing restaurant.
- **Validation**: Similar to the add form, it includes validation for required fields.

### 4. Delete Restaurant

- **Delete Functionality**: Users can delete a restaurant from the list.

## Implementation Details

### Backend (mockapi.io) Dummy End Points Displayed

- **API Endpoints**: 
  - **GET /restaurants**: Fetch all restaurants.
  - **POST /restaurants**: Add a new restaurant.
  - **PUT /restaurants/:id**: Edit an existing restaurant.
  - **DELETE /restaurants/:id**: Delete a restaurant.


### Frontend (React)

- **UI Components**:
  - **RestaurantTable**: Displays the list of restaurants with filters.
  - **Restaurant Admin**: Popup form to add a new restaurant.
- **State Management**: State is managed using React's `useState` and `useEffect` hooks.
- **Validation**: Form validation is implemented to ensure required fields are filled out.

## Conclusion

The Restaurant Management System provides a basic yet functional interface for managing restaurant data. Users can view, add, edit, and delete restaurant information with ease, utilizing the filtering options to find specific restaurants based on various criteria. The use of React, in memeory storage ensures a robust and scalable application.
