<html>
    
<head>
    <script src="https://code.jquery.com/jquery-3.1.0.js"></script>
    <script>
        function getCityInfo() {
        
             $.ajax({
                type: "GET",
                url: "http://hosting.otterlabs.org/laramiguel/ajax/zip.php",
                dataType: "json",
                data: {
                    "zip_code": $("#zip").val()
                },
                success: function(data,status) {
                    if (data.city == null) {
                        $('#city').html("Unknown");
                        $("#lon").html("Unknown");
                        $("#lat").html("Unknown");
                        $('#zip-valid').html("zip is invalid");
                        $('#zip-valid').css("color", "red");
                    } else {
                        console.log(data); 
                        $("#city").html(data.city);
                        $("#lon").html(data.longitude);
                        $("#lat").html(data.latitude);
                        $('#zip-valid').html("zip is valid");
                        $('#zip-valid').css("color", "green");
                    }
                   
                    
                },
                complete: function(data,status) { //optional, used for debugging purposes
                     //alert(status);
                }
             });
        }
        
        function getCountyList() {
            $.ajax({
                    type: "GET",
                    url: "http://hosting.otterlabs.org/laramiguel/ajax/countyList.php?",
                    dataType: "json",
                    data: { "state": $("#state").val()},
                    success: function(data,status) {
                    //alert(data);
                    console.log(data);
                    $("#county").html("<option> Select One </option>");
                    for (var i=0; i< data['counties'].length; i++){
                        $("#county").append("<option>" + data["counties"][i].county + "</option>" );
                    }

                    },
                    complete: function(data,status) { //optional, used for debugging purposes
                    //alert(status);
                    }
                    
                    });//ajax
                    
        }
        
        function checkPassword() {
            if ($("#pass").val().trim().length < 6) {
                $("#passwordError").html("*Password must be at least 6 characters!");
                isValid = false;
            }
                if (!/[0-9]/.test($('#pass').val())) {
                        $('#passwordError').html("*Password must have one digit!");
                        isValid = false;
                }

                if (!/[A-Z]/.test($('#pass').val())) {
                        $('#passwordError').html("*Password must have one uppercase character!");
                        isValid = false;
                }
        }
        
        
         function validateUsername() {
              alert("starting ajax call");
            $.ajax({
               
                type: "get",
                url: "https://kern336-hw3-kylekern.c9users.io/usernameLookup.php",
                dataType: "json",
                data: {
                    'username': $('#username').val(),
                    'action': 'validate-username'
                },
                success: function(data,status) {
                    if (data.length > 0) {
                        $('#username-valid').html("Username is not available"); 
                        $('#username-valid').css("color", "red");
                    } else {
                        $('#username-valid').html("Username is available");
                        $('#username-valid').css("color", "green");
                    }
                    
                  },
                complete: function(data,status) { 
                    //optional, used for debugging purposes
                     //alert(status);
                }
            });
                }
    </script>
</head>
<body id="dummybodyid">
   <h1> Sign Up Form </h1>
    <form>
        <fieldset>
           <legend>Sign Up</legend>
            First Name:  <input type="text"><br> 
            Last Name:   <input type="text"><br> 
            Email:       <input type="text"><br> 
            Phone Number:<input type="text"><br><br>
            Zip Code:    <input id="zip" onchange="getCityInfo();" type="text"><br><span id="zip-valid"></span><br>
            City:  <span id="city"></span>
            <br>
            Latitude: <span id="lon"></span>
            <br>
            Longitude: <span id="lat"></span>
            <br><br>
            State: <input id="state" onchange="getCountyList();"type="text"><br>
            Select a County: <select id="county"></select><br>
            Desired Username: <input onchange="validateUsername();" id='username' type="text"> <span id="username-valid"></span><br>
            Password: <input type="password"><br>
            Type Password Again: <input onchange"checkPassword" input type="password"><br>
            <input type="submit" value="Sign up!">
        </fieldset>
    </form>
</body>
</html>
