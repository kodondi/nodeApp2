var checkData = require('./validation');




console.log("In testvalidation -->"+checkData.checkEmail("piyas.de@gmail.com"));
console.log("In testvalidation -->"+checkData.checkEmail("piyas.de@gmailcom")); // Return error
console.log("In testvalidation -->"+checkData.checkMinLength("abc",2));
console.log("In testvalidation -->"+checkData.checkMinLength("abc",4)); // Return error
console.log("In testvalidation -->"+checkData.checkMaxLength("abc",2)); // Return error
console.log("In testvalidation -->"+checkData.checkMaxLength("abc",4));
console.log("In testvalidation -->"+checkData.checkBoundaryLength("abc",2,4));
console.log("In testvalidation -->"+checkData.checkBoundaryLength("abc",4,6)); // Return error
console.log("In testvalidation -->"+checkData.checkNumeric("12"));
console.log("In testvalidation -->"+checkData.checkNumeric("ABC")); // Return error
console.log("In testvalidation -->"+checkData.checkAlphaNumeric("AAA")); // Return error
console.log("In testvalidation -->"+checkData.checkAlphaNumeric("A23"));
console.log("In testvalidation -->"+checkData.checkLowerCase("lower"));
console.log("In testvalidation -->"+checkData.checkLowerCase("Lower")); // Return error
console.log("In testvalidation -->"+checkData.checkUpperCase("UPPER")); 
console.log("In testvalidation -->"+checkData.checkUpperCase("upPeR")); // Return error
 

