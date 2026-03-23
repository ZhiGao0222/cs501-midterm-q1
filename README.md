# CS501 Q1 - Compose Counter App

This is a simple counter app built using Jetpack Compose.

## Features
- Displays a number starting from 0
- Increment button to increase the count
- Reset button to reset the count to 0
- UI updates automatically when the state changes
- State is preserved during screen rotation using `rememberSaveable`

## Technologies Used
- Kotlin
- Jetpack Compose
- mutableStateOf
- rememberSaveable

## How it works
The app uses `mutableStateOf` to store the counter value.  
When the value changes, Compose automatically recomposes the UI to reflect the updated state.  

`rememberSaveable` ensures that the counter value is not lost when the screen is rotated.

## AI Usage
ChatGPT was used to help clarify concepts related to Jetpack Compose, including state management and recomposition.  
All code was written, modified, and tested independently.

## Author
Zhi Gao
