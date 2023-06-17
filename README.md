# Ex.08 Customer Registration Form
## AIM
  To write a program in JavaScript for creating a customer registration form for an agro-based company.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define different functions to register the customers based on their qualifications.

### STEP-3
  Using form elements to create the registration details of a customer.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
~~~<!DOCTYPE html>
<head>
    <title>Sample web page</title>
</head>
<style>
    body {
        background-color: orange;
    }
</style>
<body>
    <h1>
        <caption>AGROTECH CUSTOMER REGISTRATION FORM</caption>
    </h1>
<hr color="red">
   
    <h3>
        <form onsubmit="thank()">
            <br>
            Name:
            <input type="text">
            <br>
            <br>
            E-Mail:
            <input type="email">
            <br>
            <br>
            Username:
            <input type="text">
            <br>
            <br>
            Password:
            <input type="password">
            <br>
            <br>   
            Re-type Password:
            <input type="password">
            <br>
            <br>
            Mobile Number:
            <input type="tel">
            <br>
            <br>
            Crop:
            <select>
                <option>Maize</option>
                <option>Rice</option>
                <option>Wheat</option>
                <option>Corn</option>
            </select>
            <br>
            <br>
            Fertilizer Needed:
            <input type="radio">Yes
            <input type="radio">No
            <br>
            <br>
            Address:
            <textarea rows="10" cols="30"></textarea>
            <br>
            <input type="submit" name="submit"><input type="button" value="Clear All" onclick="clearForm()">
        </form>
    </h3>
    <script type="text/javascript">
        function thank() {
            alert("Thank you for registering with us");
        }
    </script>
</body>
</html>
~~~

## OUTPUT
![registration web ex 8](https://github.com/Divyapriyadiya/EX08_Web-Design/assets/128477941/4c7e4f04-5100-4937-a2c6-c5d7d412630b)



## RESULT
  Customer registration form using JavaScript is created successfully.
