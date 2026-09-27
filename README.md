# IM26 Deductible Lab

An interactive teaching exercise on Swiss health-insurance deductible choices.

The website compares deductibles using CARA preferences and a subjective cost distribution. Risk preferences are measured with a five-choice cost staircase (pay a sure amount or keep a 10% chance of paying CHF 2,000), which is a teaching design, and compared with the lottery staircase component of the Preference Survey Module. Cost beliefs use an adaptation of bins-and-balls elicitation. The healthcare context and CARA conversion are teaching assumptions, described in the exercise's Methods & sources.

All calculations take place in the browser. Answers are kept in the browser's local storage on the student's device until cleared; reports and progress files are downloaded to the device. Nothing is sent to a server.

`index.html` is the self-contained website, including Plotly.js and its MIT license. It is generated from the maintained local Deductible Lab source using `build.mjs`.
