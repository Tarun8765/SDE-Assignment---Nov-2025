SDE Assignment – Merge Discontinuous Time Ranges
📄 Problem Statement

You are given an array of time ranges representing when a system was active.
Each range is [start, end) where start and end are UNIX timestamps in milliseconds.
The goal is to merge all overlapping or nearly continuous time ranges into sorted, non-overlapping intervals.

If the gap between two ranges is smaller than or equal to a threshold, they should be treated as continuous and merged.
⚙️ Project Setup
1️⃣ Clone or Extract

Download or clone the repository/folder:

git clone <your-repo-url>
cd sde-assignment

2️⃣ Install Node.js

Make sure you have Node.js v14+ installed.
Check using:

node -v

3️⃣ Run the Module
node test.js

Usage Example
const { mergeTimeRanges } = require('./my-module');

const ranges = [
  [0, 10],
  [12, 15],
  [17, 25],
  [27, 35]
];
const threshold = 3;

console.log(mergeTimeRanges(ranges, threshold));
// Output: [ [0, 35] ]

🧪 Run Tests via NPM

If your package.json has the script:

npm test


This will automatically run node test.js.

🧑‍💻 Author

Tarun Ghawri
Email: tarunghavri4@gmail.com

LinkedIn: linkedin.com/in/tarunghawri1111
