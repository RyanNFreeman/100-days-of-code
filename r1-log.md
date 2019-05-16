# #100DaysOfCode Log - Round 1 - [Your Name Here]

The log of my #100DaysOfCode challenge. Started on [May 14, Tuesday, 2019].

## Log

### R1D1

Worked on coding challenge to compare two individuals BMI (calculated using the formula: BMI = mass / height^2 = mass / (height \* height))

let marksMass = 78; //kg
let marksHeight = 1.69; //m
let johnsMass = 70; //kg
let johnsHeight = 1.5; //m

marksBMI = marksMass / (marksHeight _ marksHeight);
johnsBMI = johnsMass / (johnsHeight _ johnsHeight);

let markHigherBMI = marksBMI > johnsBMI;

console.log(`Is Mark's BMI higher? True or false`, markHigherBMI);

### R1D2

Worked on a challenge to see who's average score out of all these teams is highest.

johnsTeam = (89 + 120 + 103) / 3;
mikesTeam = (89 + 120 + 103) / 3;
marysTeam = (33 + 200 + 40) / 3;

if (johnsTeam > mikesTeam && marysTeam) {
console.log("John's team is winning, their average score is " + johnsTeam);
} else if (mikesTeam > johnsTeam && marysTeam) {
console.log("Mike's team is winning, their average score is " + mikesTeam);
} else if (marysTeam > mikesTeam && johnsTeam) {
console.log("Mary's team is winning, their average score is " + marysTeam);
} else if ((johnsTeam === mikesTeam) === marysTeam) {
console.log("Mike's team and John's team are equal");
} else if (johnsTeam === mikesTeam && johnsTeam > marysTeam) {
console.log("John and Mike are tied, but Mary lost");
} else if (marysTeam === mikesTeam && marysTeam > johnsTeam) {
console.log("John and Mary are tied, but John lost");
} else {
console.log("Mary and Mike are tied, but John lost");
}
