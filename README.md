# SangeetSuno

**SangeetSuno** is an android app that allows users to listen to music from their phone's external storage.
Submitted by: **Kashaf Mujeeb**

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

* [X] User can view a list of MP3 songs from their mobile storage.
* [X] User can play and pause the song.
* [X] User can click the next button to move to the next song in the list.
* [X] User can click the back button to pay the previous song from the list.
* [X] User can use the Seekbar to change the progress of the currently playing song.


## Video Walkthrough

Here's a walkthrough of implemented user stories:

![SangeetSuno](https://user-images.githubusercontent.com/89542741/180890542-74dbef0a-0611-4c0a-93a1-c7d7a9b0f24a.gif)


## Notes

Describe any challenges encountered while building the app.

While trying to code this app, I was not sure how to allow my application to get an excess to the mobile's external storage. Therefore, I had to do some online research and thats when I came across Dexter android library and added its permissions to the gradle script of the app. Another challenge that I faced while making this application was that I did not know how to go back from the song playing activity to the main list activity After, I checked StackOverflow thread on this topic, i added  "android:parentActivityName=.MainActivity" to my AndroidManifest.xml file and it added a back button to my Main list activity in the app.
## License

    Copyright [2022] [Kashaf Mujeeb]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
