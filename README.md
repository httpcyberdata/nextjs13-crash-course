# NextJS Crash Course
Tutorial URL: https://www.youtube.com/watch?v=Y6KDk5iyrYE
Tutorial description: A complete crash course to NextJS version 13 and it's new features such as the app directory structure, routing, React Server Components vs client components, layouts and more. 

___________

### Software versions
    nextJS 13.2.4
    reactJS 18.2.0
    react-icons 4.8.0
### Problems in the project:
N/A

### How to use
1. npm install
2. npm run dev
3. change API url to match your repos or any GitHub user to show the list of repositories.

In-browser routes
    - localhost:3000/code/repos
    View list of repositories for the GitHub account 'httpcyberdata' and the functionality to click on each repository to view the directories howerver the links to them are non-functional.


API ROUTES (use in Postman or other app)
- GET /api/courses/search?query=TEXT
    A GET request to ask for courses in the data.json file that contain the text in the query. For example, query for React course and the TraversyMedia's React Front To Back course appears as it's relevant to the 'REACT' query text
- GET /api/courses
    Returns an array of courses.

### Photos of project:
![](/public/nextjs13-cc1.gif)
![](/public/nextjs-13-cc.gif)
![](/public/nextjs-13-image1.png)
![](/public/nextjs13-cc1.gif)

### Apps used:
- Visual Studio Code or (coder slang: VS Code)	[](https://code.visualstudio.com/)
- Google Chrome: [https://www.google.com/chrome/dr/download/](https://www.google.com/chrome/dr/download/)
- GitHub CLI: [https://cli.github.com/](https://cli.github.com/) 

### Coding styles I used:
N/A

### What I learned
1. Using layouts in Nextjs13 is as simple a creating a layout.jsx file and in every child component, the content in the layout.jsx file will persist.
2. What 'use client' is for. I always seen 'use client' in React code while browsing some React code in a repository. In react server components, one of the trade offs is one can't use the useState hook, because it will throw an error in the browser unless they use react client components. However the error goes away with 'use client' at the top of the JavaScript (.jsx) file.