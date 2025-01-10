# Unhandled Promise Rejection in React Native Data Fetching

This repository demonstrates a common issue in React Native applications where an unhandled promise rejection occurs during asynchronous data fetching.  The application crashes without providing clear error details, making debugging difficult. The solution focuses on proper error handling using try...catch blocks and clear error messages.

## Problem

The original `DataList.js` component attempts to fetch data from an API. However, it doesn't handle potential errors during the fetch or JSON parsing process, leading to a crash if the API request fails.  This is a common problem that leads to poor user experience and difficult debugging.

## Solution

The `DataListSolution.js` component improves the error handling by incorporating a `try...catch` block. This allows the application to gracefully handle errors, display informative messages to the user, and prevent unexpected crashes.