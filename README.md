Parmenion Technical Test for Back End Developers
==================================

The technical test cosists of a coding test and a few follow-up questions.  You can take as long as you want but we would allow at least 4 hours.

Once complete please send a zip file containing two folders.  One with all the code required to run you solution and the other with the answers to the questions as a PDF.

## Code Test

We need to add a simple tool to the adviser’s site to allow them to generate a projection to determine if their client’s investment targets are realistic.  It will be a single web page and will consist of a few inputs and a graph to show output. 

### Inputs

- Lump Sum Investment (£)
- Monthly Investment (£)
- Target Value (£)
- Timescale (years)
- Risk Level (low / medium / high)

### Assumptions

- Ignore inflation
- Ignore any adviser/platform charging, this is all wrapped up in the growth figures
- Annual Growth Figures are:
  - Low Risk 
    - Wide Bounds: 1 - 3%
    - Narrow Bounds: 1.5 - 2.5%
  - Medium Risk
    - Wide Bounds: 0 - 5%
    - Narrow Bounds: 1.5 - 3.5%
  - High Risk
    - Wide Bounds: -1 - 7%
    - Narrow Bounds: 2 - 4%
- Data for the output is calculated monthly

### Output

- Single Graph
- Time (years) on X-Axis
- Value (£) on Y-Axis
- Marker Lines to indicate
  - Target Amount
  - End Timescale
- Graph Line to Indicate
  - Total Invested
- Coloured Regions to Indicate
  - Expected Value based on Growth Bounds for selected Risk Level

### Technical Requirements

- Requirements
  - Visual Studio Solution
  - Calculation of projection is done backend via a web service
  - Backend is either C# or VB.NET
  - Runs on modern browsers with no browser plugins required
- Flexibility On
  - Look/Feel
  - Browser Compatibilty
  - Libraries Used
  - Graph can be rendered frontend or backend 
  - User Interface
  - Pretty much everything else!

### Level of Finish/Timescales

- Prototype
  - It doesn’t need to be complete, just demonstrate the concepts
- Approximate Timescale
  - It should be possible to rough up a prototype in half a day if everything goes smoothly, don’t worry about spending ages on it but let me know how long you did spend
  - Feel free to drop areas of functionality if they are a significant time drain, the aim is a prototype not a finished product

## Follow Up Questions

1. How long did you spend on the code test?
2. What went well?
3. Was there anything that was attempted but was not possible to get working in the time so is not visible in the code?
4. What would you do to improve it / continue development?
