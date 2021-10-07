<!-- JS-07 - Fetch & Web Storage APIs -->
<!-- https://github.com/generation-org/JS/tree/master/JS-07%20-%20Fetch%20%26%20Web%20Storage%20APIs -->

 
 ## Part 1: Using the Fetch API
 
1. Download the *js* folder and the *index.html* files from this repository.
2. Open the *index.html* in the browser and observe what it does.
3. Open the *js* folder and the *index.html* with your code editor of choice and analyze the functionality and the code.
4. Implement the function *fetchColorsList* using the fetch API to download the full colors list from the following endpoint:
  https://reqres.in/api/unknown
5. Connect the *fetchColorsList* with the *addItem* funciton so the colors list is filled and displayed in the *index.html* page.

 ## Part 2: Using the Web Storage API
1. Modify the *fetchColorsList* function so when the data is downloaded from the API, the colors list is stored using the local storage.
2. Implement the *loadColorsFromStorage* function so the color values are loaded from the local storage.
3. Open the developer tools and verify that the data is stored in the local storage.
4. Test your application without connection to the internet and verify that the colors list is loaded.

## Challenge Yourself
1. Add a clear button that removes all the elements from the list.
2. Add a load button that calls the *fetchColorsList* function and loads the colors again.