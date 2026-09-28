# IM26 Deductible Lab

An interactive teaching exercise on Swiss health-insurance deductible choices.

The website compares deductibles using CRRA preferences and a subjective cost distribution. Risk preferences use the HRS lifetime-income gambles, giving a parameter interval under CRRA. The utility curve, expected utility and certainty equivalent are shown during the risk-preference step. Cost beliefs adapt bins-and-balls elicitation, with a probability chart that updates as tokens move. Results compare expected costs, certainty-equivalent costs, annual cost-sharing caps and sensitivity to the assumptions.

The methods draw on Barsky et al. (1997), Kimball, Sahm and Shapiro (2008), Delavande and Rohwedder (2008), and the Swiss deductible framework in Biener and Zou (2024). The student wording, healthcare application, wealth assumption and interval starting values are teaching adaptations. Sources and assumptions are documented in the exercise's Methods & sources.

All calculations take place in the browser. Answers are kept in the browser's local storage on the student's device until cleared; reports and progress files are downloaded to the device. Nothing is sent to a server.

The downloadable report includes all five charts. Earlier progress retains costs and reflections, while earlier CARA answers are archived separately from the new CRRA questions.

`index.html` is the self-contained website, including Plotly.js and its MIT license. It is generated from the maintained local Deductible Lab source using `build.mjs`.
