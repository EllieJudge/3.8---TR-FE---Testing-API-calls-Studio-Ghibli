🧪 Assignment - Testing API calls in React with the Studio Ghibli API 🧪
Part 1:
Have a read of the React Testing Library Documentation: https://testing-library.com/docs/react-testing-library/example-intro#full-example
and Mock Service Worker Library: https://mswjs.io/
Once you’re familiar, have a go at this React Testing Library Quiz!
It’s important you do this before starting on the Part 2
: https://forms.gle/SsyLQbj8WUaejvif8

Part 2:
Now you have familiarised yourself with the React Testing and Mock Service Worker Libraries and how to mock an API call example(s) you are ready for the next step!
Your challenge is to put these learnings into practice and mock an API call from a React app (don’t forget the TypeScript flag!) that you’ve created. For this challenge you will be putting into practice your knowledge of TypeScript, React, Hooks, APIs and Testing. 💃
You’ve got this! 🙌

📝 The Brief:
The aim of this is to make a GET request to the Studio Ghibli films end point and for your App component to display the title of the first film that comes back from the API end point ('Castle in the Sky').
Studio Ghibli API docs: https://ghibliapi.herokuapp.com/
In this task you need your App component but you are more than welcome to create another component if you like!
Once your App is calling the Studio Ghibli API and displaying the first film title on your page ('Castle in the Sky'), we'd like you to add a test to mock (or “stub”) the API response. This should enable you to write a test to check the first film title has been rendered correctly (Hint: 'Castle in the Sky' should be in the document 😉).

🔥 Part 3 (extension):
Write a test checking your App component displays an error message saying "Oops… something went wrong, try again 🤕" in the scenario the API returns Status Code 500 (Internal Server Error: https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500 ).
Write another test checking your App component displays an error message saying "418 I'm a tea pot 🫖, silly" in the scenario the API returns Status Code 418 (I’m a tea pot: https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/418 )

💡Top Tips💡

This exercise is about what your app looks like so don’t worry about styling!!! The purpose is to mock an API call in React (if you have time to add styling later - then great! But make sure you get through the extensions first 🫖)
You will need to create a React app from scratch and strip out excess boiler plate.
1npx create-react-app myAppName --template typescript
You will need to make an API call (you may/will want to consider using and the Hook for this)
You will need to consider waiting for your data to load (Hint: and )
Remember to commit little and often to GitHub, and to keep your commit messages nice and descriptive ✅
Don’t forget to add a README explaining how to run your app when it’s done! 🔥
Remember to check the documentation regularly

✨How to make a submission✨
Please submit a GitHub link to your final solution, please ensure you have a clear README file ✅
