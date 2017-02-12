# jQuery-form-validation
Simple jQuery form validation without plugins or Library files
In this file i can work for
  1. If text is empty
  2. Allow only Alphabats
  3. Allow only Numbers
  4. Allow only Alphabats and Number
  5. Email Validation
  
//Email Validation
  
    function ValidateEmail(email) {
        var expr = /^([\w-\.]+)@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.)|(([\w-]+\.)+))([a-zA-Z]{2,4}|[0-9]{1,3})(\]?)$/;
        return expr.test(email);
    };
    
//Alphabats and Numeric Validation
	
    function ValidateAlphanumeric(alphanumeric) {
        var expr = /^([a-zA-Z0-9]+)$/;
        return expr.test(alphanumeric);
    };
	
//Numeric Validation

    function ValidateNumeric(numeric) {
        var expr = /^[0-9]{1,10}$/;
        return expr.test(numeric);
    };
//Alphabats Validation

    function ValidateAlphabats(alphabats) {
        var expr = /^[a-zA-Z ]*$/;
        return expr.test(alphabats);
    };  
