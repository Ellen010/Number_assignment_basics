# Number_assignment_basics
//asssigns random number to the participant according to the age//
let raceNumber = Math.floor(Math.random() * 1000);
let registeredEarly = true; 
let runnerAge= 25;
if (runnerAge >= 18 && registeredEarly===true) {
    raceNumber += 1000;
}
console.log(raceNumber);
