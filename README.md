
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>

    
</head>

<body>
    
    <div id="form1">
        <h1>Registration Form</h1>
        <form>
            <div class="div1">
                <label for="FirstName">FirstName:</lable>
                    <input type="text" name="FirstName" id="FirstName">
            </div>
            
            <div class="div2">
                <label for="LastName">LastName:</label>
                <input type="text" name="LastName" id="LastName">
            </div>


            <div class="div3">
                <label for="password">Password:</label>
                <input type="password" password="password" id="password">
            </div>
            <div class="div4">
                <label for="Gender">Gender:</label>
                <label for="Male">Male</label>
                <input type="radio" male="Male" id="male">

                <label for="Female">Female</label>
                <input type="radio" male="Female" id="Female">
            </div>
            <div class="div6">
                <label for="Religion">Religion:</label>
                <input type="checkbox" Islam="Islam" id="Islam">
                <label for="Islam">Islam</label>

                <input type="checkbox" Hindo="Hindo" id="Hindo">
                <label for="Islam">Hindo</label>

                <input type="checkbox" other="other" id="other">
                <label for="other">other</label>


            </div>
            <div class="div7">
                <label for="Department">Department:</label>
                <select Name="Department">
                    <option value="CSE">CSE</option>
                    <option value="EEE">EEE</option>
                    <option value="MT">MT</option>
                </select>
            </div>
            <div class="div8">

                <label for="comment">Comment:</label>
            </div>
            <div>
                <textarea cols="30" rows="5"></textarea>

            </div>
            <div class="div9">
                <input type="Reset" value="Clear">
                <input type="Submit" value="Registor">

            </div>
        </form>

    </div>
</body>

</html>
