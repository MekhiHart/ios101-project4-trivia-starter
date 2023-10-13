# Project 4 - *Triva App Part 2*

Submitted by: **Mekhi Hart Dela Cruz**

**The Trivia App Part 2 ** focuses on API calls and handling the data collected correctly by checking if the server status code is correct, the response is the correct type, and data is not invalid

Time spent: **2.5** hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] User can view and answer at least 5 trivia questions.
- [X] App retrieves question data from the Open Trivia Database API.
- [X] Fetch a different set of questions if the user indicates they would like to reset the game.
- [X] Users can see score after submitting all questions.
- [X] True or False questions only have two options.


The following **optional** features are implemented:

  
- [] Allow the user to choose a specific category of questions.
- [ ] Provide the user feedback on whether each question was correct before navigating to the next.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here is a reminder on how to embed Loom videos on GitHub. Feel free to remove this reminder once you upload your README. 

https://youtu.be/NmbkDwV5R0w

## Notes

The biggest challenge was understanding the concept of using the main thread and background thread when changing the UI. I had to understand that when creating an API call is automatically ran as a task in the global thread, with a quality of service of a background. Which is why changing the UI was not working as expected until I used the main thread to make the UI changes.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
