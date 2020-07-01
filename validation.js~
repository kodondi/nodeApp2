var check = require('validator').check;


var checkEmail = function(value) {

   try {

      check(value).isEmail();

   } catch (e) {

      return e.message; //Invalid integer

   }

   return value;

};

// Chcek minimum length

var checkMinLength = function(value,len) {

   try {

       check(value,'Please specify a minimum length of %1').len(len);

   } catch (e) {

       return e.message;

   }

   return value;

};


//Check Maximum length

var checkMaxLength = function(value,lenmax) {

   try {

       check(value,'Please specify a maximum length of %2').len(0,lenmax);

   } catch (e) {

       return e.message;

   }
   return value;

};

//Chcek boundary length

var checkBoundaryLength = function(value,lenmin, lenmax) {

    try {

         check(value,'The message needs to be between %1 and %2 characters long (you passed "%0")')

              .len(lenmin,lenmax);

    } catch (e) {

         return e.message;

    }

    return value;

};

//Check Numeric

var checkNumeric = function(value) {

   try {

      check(value).isNumeric();

   } catch (e) {

      return e.message; 

   }

   return value;

};

//Check AlphaNumeric

var checkAlphaNumeric = function(value) {

   try {

      check(value).isAlphanumeric();

   } catch (e) {

      return e.message; 

   }

   return value;

};

//Check LowerCase

var checkLowerCase = function(value) {

   try {

      check(value).isLowercase();

   } catch (e) {

      return e.message; 

   }

   return value;

};

//Check UpperCase

var checkUpperCase = function(value) {

   try {

      check(value).isUppercase();

   } catch (e) {

      return e.message; 

   }

   return value;

};


module.exports.checkEmail = checkEmail;
module.exports.checkMinLength = checkMinLength;
module.exports.checkMaxLength = checkMaxLength;
module.exports.checkBoundaryLength = checkBoundaryLength;
module.exports.checkEmail = checkEmail;

