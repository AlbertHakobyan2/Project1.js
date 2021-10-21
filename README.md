# Project1.js
let heightT = 40;
let baseT = 15;
let heightR = 15;
let widthR = 20;

let areaT = (1 / 2) * baseT * heightT;
let areaR = heightR * widthR;

if (areaT > areaR) {
    console.log("The area of the triangle is greater");
}
else if (areaT < areaR) {
    console.log("The area of the rectangle is greater")
}
else {
    console.log("The areas are equal");
}



Project2.js
let a = 50;
let b = -4;
let c = 40;

let discriminant = b ** 2 - 4 * a * c;
let x1 = (-b + Math.sqrt(discriminant)) / (2 * a);
let x2 = (-b - Math.sqrt(discriminant)) / (2 * a);

let d0x = -b / (2 * a);
console.log(discriminant);

if (discriminant < 0) {
    console.log("Please enter a correct polynomial !!!");
}
else if (discriminant == 0) {
    console.log(" There is only 1 root for the polynomial and that is : " + d0x);
}
else {
    console.log("The polynomial has 2 roots which are X1: " + x1 + " X2: " + x2);
}





Project3.js
let x1 = 5;
let y1 = 5;
let x2 = 4;
let y2 = 6;
let line = Math.sqrt((x2 - x1) ** 2 + (y2 - y1) ** 2);
let exec = false;

if (x1 >= 0 && x2 >= 0 && y1 >= 0 && y2 >= 0) {
    exec = true;
}
else {
    exec = false;
    console.log("please enter a positive number");
}

if (exec == false) {
    console.log("MISTAKE");
}
else {
    console.log(line);
}





Project4.js
let x1 = -10;
let x2 = -5;
let y1 = 6;
let y2 = 5;
let line = Math.sqrt((x2 - x1) ** 2 + (y2 - y1) ** 2);
console.log(line);
