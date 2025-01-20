# Coding 1 | MUST 4707

## Modifying an Existing Object

In this assignment, you will update the file `script.js` and commit it to your assignment repository. Your task will be to add **two new properties** to an existing object and test your work using the JavaScript Console in the browser.

---

### Accessing the Assignment Materials
1. Navigate to the assignment repository in the course [GitHub organization](https://github.com/MUST4707)
2. Click on the green `Use this template` button in the top right corner.
3. Choose 'Create a new repository'
4. Set up the repo name under your account.
5. Click `Create repository`

*You should now be at your own personal repository with the assignment materials.*
6. Click on the green `<> Code` button and select `Open with GitHub Desktop

*You should now be in your GitHub Desktop application that has a pop up window called 'Clone a Repository'*

7. Make sure the local path is where you would like to save this repo.
8. Hit `Clone`
9. You should be able to now click the `Open in Visual Studio Code ` button or navigate to your files and open the folder in Visual Studio Code. 
10. After you finish working on your project please return to GitHub Desktop and
    1. Commit your changes to the `master` (don't to add a summary description)
    2. Click on the `Push Orgin` to sync your commit with the GitHub cloud.
      

### Task Description

1. The provided `script.js` contains an object called `song` with a few properties already defined.
2. Your task is to add **two new properties** to `song`:
    - A property named `releaseYear` that contains a number (e.g., `2023`).
    - A property named `isAvailable` that contains a boolean value (`true` or `false`).

3. After adding these properties, make sure they meet the requirements listed below and pass the provided tests.

---

### Coding Instructions

You will add your code between these comments in `script.js`:

```javascript
//↓↓↓↓↓↓↓↓↓↓↓↓YOUR CODE goes below here↓↓↓↓↓↓↓↓↓↓↓↓

let song = {
   title: "Apple",
   album: "Brat"
}
```

_this is where you will type your code Edit the song object...._

```javascript
//↑↑↑↑↑↑↑↑↑↑YOUR CODE goes above here↑↑↑↑↑↑↑↑↑↑

```

---


### Coding Steps

1. Open the `script.js` file in your repository.
2. Add the following properties to the existing object:
    - `releaseYear` (type: number)
    - `isAvailable` (type: boolean)

3. Save your changes and commit the file in GitHub Desktop.

---

### Testing Your Work

#### Testing (Using VS Code and your Browser)
1. Make sure you have saved all of your files, then click on the `index.html` file.
2. Click on "Go Live"
3. Once the browser window opens with the assignment webpage, open the Javascript Console
4. Run the following test to make sure there are no errors. 
   1. Test 1: `song` 
      - the result should be `{title: 'Apple', album: 'Brat', releaseYear: 2023, isAvailable: false}`
   2. Test 2:`typeof song`
      - result: `'object'`
   3. Test 3:`song.releaseYear`
      - result: `'2023'` (it should be whatever you put in for the release year)
   4. Test 4:`typeof song.releaseYear`
      - result: `'number'`
   5. Test 5:`song.isAvailble`
      - result: `false` (it should be whatever boolean you put in for the availability)
   6. Test 6:`typeof song.isAvailble`
      - result: `boolean`
 
*If any of the above commands return an error or an unexpected result please return to you code and update to fix the error. Repeat this process over and over until their are no errors*



---


### Submission Steps
1. Upload your `script.js` to the Canvas assignment.


### Grading Criteria

The following criteria will be checked:

1. `song` exists
2. `song` is an `'object'`
3. The `releaseYear` property exists.
4. The `releaseYear` property type is a number. 
5. The `isAvailable` property exists. 
6. The `isAvailable` property type is a boolean.

---