# GoalFitApp Test Evidence Site

This GitHub Pages site hosts the **functional and non-functional test evidence** for the GoalFitApp NEA project. It supporst direct linking from the NEA report to individual test cases where the evidence video is located.

## Structure

Test cases are grouped by priority and requirement type:

- [Must-Have Tests](must-haves.html)
- [Should-Have Tests](should-haves.html)
- [Could-Have Tests](could-haves.html)
- [Non-Functional Requirements (NFRs)](nfrs.html)

Each test case includes:
- A descriptive heading
- An embedded video showing the test execution
- A unique anchor ID for direct linking from the NEA report

## Usage

Moderators can:
- Navigate via the [Home Page](index.html)
- Jump directly to any test case using anchor links (e.g. `must-haves.html#m1_1`)
- View inline video evidence without downloading files
- Cross-reference test IDs with the NEA report’s test tables

All video files are stored in `/test_video_evidence/` and named using the format:  
`<TestID>_Evidence.MP4`  
Example: `M1.1_Evidence.MP4`

## Notes

- This site is for evidence presentation only — it is not the GoalFitApp project itself.
- All tests were executed against the final version of the application.
