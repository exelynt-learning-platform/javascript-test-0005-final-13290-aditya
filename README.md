# javascript-test-0005-final-13290-aditya
Final Project Assignment - This repository contains the complete final project code and documentation.


counter = 1;
for (let i = 1; i <= 5; i++) {
    let row = '';
    for (let j = 1; j <= i; j++) {
        row += counter + ' ';
        counter++;
    }
    console.log(row.trim());
