# WEB102 Prework - *Game Changer*

Submitted by: **Yusra Abdelrahman**

**Game Changer** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] The website includes a navigation bar at the top to navigate to the About, Stats, and Our Games sections.
* [x] The navigation bar remains accessible at the top of the page as the user scrolls, allowing for easier navigation.
* [x] When hovering over the navigation buttons, as well as the "Show Funded Games," "Show Unfunded Games," and "Show All Games" buttons, the cursor changes to a pointer, and the background and font colors change to enhance usability, interactiveness, and visual appeal.
* [x] When clicking on the "Show Funded Games," "Show Unfunded Games," or "Show All Games" buttons, the page scrolls to the Our Games section so the games are fully in view.
* [x] The site smoothly scrolls when clicking on navigation buttons.

## Video Walkthrough

Here's a walkthrough of implemented features:

![web102prework](https://github.com/user-attachments/assets/63036282-471f-4e54-aeb7-7af4df9eb5eb)

<!-- Replace this with whatever GIF tool you used! -->
GIF created with LiceCap  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Some challenges I encountered while building the app included integrating the navigation bar within the header. I used Flexbox and nested div containers to customize the styling and positioning of the buttons, ensuring they were properly spaced. I also styled the header to remain fixed at the top of the screen and span the full width. Another challenge was preventing the fixed header from covering the section titles when navigating via anchor links. I resolved this by linking the navigation buttons to empty div elements positioned above the section titles, offset by the height of the header, to keep the titles visible.

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
