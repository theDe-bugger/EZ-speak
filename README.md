# EZ-Speak : https://thede-bugger.github.io/EZ-speak/PresetCode/index.html
## Inspiration
Meet Hacky. Hacky is another one of us affected by the coronavirus. He has lost his confidence, needs to practice for big interviews, and is looking for his voice. There are millions of people just like him, looking for jobs, needing to do interviews for schools, preparing for conferences, and just trying to gain confidence when speaking. Presenting in front of a mirror may feel awkward and does not allow him to track progress. Practicing with someone else may make Hacky feel uncomfortable. Speaking with confidence and power is something a lot of people wish to do, but haven't been able to practice it nor have they received the natural talent of doing so. There also isn't a perfect, defined method of improvement for this yet. That is why EZ speak was developed! To help people work on their public speaking and communication skills, prepare for the big moments in life, and to ensure they don't regret their efforts in preparation because of discomfort. 

## What it does
EZ speak is an analytical, self-improvement web-application that helps users improve their confidence and public speaking skills. The website starts off at the home page, which was designed using basic Front-End tools like HTML, CSS, JavaScript. From there, Hacky can either view his past scores, or begin a new test. The test provides a random topic from the database and uses a JavaScript timer to allow him to prepare. Once the timer runs out, Hacky is redirected to a page where an automatic recorder, from MediaRecorder API, begins and he must start his presentation. He may click stop or speak for a whole minute before EZ speak automatically stops the recording. This recording is stored in Google FireBase Storage and he is able to download it if he wishes to. An attempt was made to pass this file into the Google Cloud Speech to Text API to determine confidence levels, stutters, repetition, and more. This leads Hacky to the final stage where he is presented with his results. Based on these results, Hacky can track his progress and improve his skills over time. He can even compete with friends and gain points for doing better!

## Challenges we ran into
The biggest challenge was incorporating the Google Cloud Speech to Text API. This required a somewhat complicated setup in Google Cloud Storage and different environments for separate APIs. This also required the conversion of blob webm video files to mp3 or raw audio data so that the Speech API could analyze it. This was a complicated process as most conversion APIs we found online were not free and the original media recorded was a video. We changed to webm audio with little time left, but it was not compatible. We were unable to resolve this issue in the given time, but it is something we plan to solve in the future.

## Accomplishments that we're proud of
We are proud of being able to create such a functional prototype in only 36 hours considering our minimal experience. The team was able to build a base prototype with most features such as video recording API’s, multiple pages, Google FireBase, JavaScript timers along with the use of a lot of open-source software. 

## What's next for EZ speak
This is a highly feasible project due to its use of simple tools and processes. The future outlook for this app is amazing due to its low maintenance requirements, one-time setup cost, and potential for upgrades. We hope to launch this app after adding features such as: 
- Speech to Text Analytics
- Graphing and Improvement Statistics
- Collaboration and Competition with other users
- Leaderboards + Prize Systems
- Releases with multiple organizations such as DECA, schools, and more.
