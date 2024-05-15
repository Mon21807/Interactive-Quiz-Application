# Interactive Quiz Application with React

This project is an interactive quiz application built using React, focusing on the application of the useState hook for state management. The quiz allows users to answer multiple-choice questions and calculates their score based on their answers.

## Features

- Display multiple-choice questions to the user.
- Allow users to select answers for each question.
- Calculate the user's score based on their answers.
- Display the user's score after submitting the quiz.
- Include a restart button to allow users to retake the quiz.
2. Open the index.html file in a web browser.

## Implementation Details

- The Quiz component manages state using the useState hook to keep track of user answers, the current score, and whether the quiz has been submitted.
- Multiple-choice questions are stored as an array of objects containing the question, options, and correct answer.
- The handleAnswerSelection function updates the user's answer for a specific question.
- The handleSubmit function calculates the user's score based on their answers and sets the state to display the score.
- The handleRestart function resets the quiz state to allow users to retake the quiz.

## Observations and Learnings

- Learned how to manage component state using the useState hook in React.
- Practiced handling user input and events in React components.
- Explored conditional rendering to display different components based on state.
- Gained insights into structuring and organizing React components for interactive applications.

## Challenges Faced

- Ensuring that the quiz restart functionality resets all relevant state variables appropriately required careful consideration of state management.
- Implementing radio button inputs and handling user selections for each question while maintaining a clear and user-friendly interface posed some challenges.

## Resources

- [React documentation](https://reactjs.org/docs/getting-started.html)
- [MDN Web Docs: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs: JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## Setup

To run this project locally, follow these steps:

1. Clone the repository:

