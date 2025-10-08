# Project 3 - *Trivia*

Submitted by: **Gerald Shimo**

**Trivia** is an app that allows users to test their knowledge across different categories, such as Science, Geography, and Astronomy. Users can select answers to multiple-choice questions, see whether they are correct, and view their final score at the end of the quiz

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] User can view the current question and 4 different answers
- [x] User can view the next question after tapping an answer
- [x] User can answer at least 3 different questions


The following **optional** features are implemented:

- [ ] User can use the vertical orientation of the app on any device
- [x] User can track the question they are on and how many questions are left
- [x] User can see how many questions they got correct after answering all questions
- [ ] User should be able to restart the game after they've finished answering all questions

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/106de133c4674581a6094b308feba382">
      <p>Videos | Library | Loom - 7 October 2025 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/106de133c4674581a6094b308feba382">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/106de133c4674581a6094b308feba382-66c4599f19ece694-full-play.gif">
    </a>
  </div>

## Notes

-Initially, buttons were crashing the app because the storyboard connections were pointing to non-existent methods (unrecognized selector error). This was fixed by consolidating all buttons into a single IBAction.

-Tracking the final score required adding a separate property and updating it correctly when the user tapped answers.

-Ensuring the app gracefully handles the end of the quiz and hides buttons while displaying the score.

## License

    Copyright [2025] [Gerald Shimo]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
