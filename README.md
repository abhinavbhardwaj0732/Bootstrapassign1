<!DOCTYPE html>
<html>
  <head>
    <title>Bootstrap Page</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
  </head>
  <body>
    <div class="container-fluid" >
      <div class="row">
        <!-- First column -->
        <div class="col-sm-6">
          <h1 class="text-center">FORM</h1><br><br>
          <form>
            <div class="form-group">
              <label for="name">YOUR Name:</label>
              <input type="text" class="form-control" id="name" placeholder="Enter Your name">
            </div>
            <div class="form-group">
                <label for="phoneno"> YOUR Phone No:</label>
                <input type="text" class="form-control" id="phoneno" placeholder="Enter Your phoneno">
            </div>
            <div class="form-group">
                <label for="dob">DATE OF BIRTH:</label>
                <input type="date" class="form-control" id="dob" placeholder="Enter Your DOB">
            </div>
            <div class="form-group">
                <label for="address">Address:</label>
                <textarea class="form-control" id="message" rows="3" placeholder="Enter Your Address"></textarea>
            </div>
            <div class="form-group">
                <label for="gender">Gender:</label>
                <input type="radio" name="gender"/> Male
                <input type="radio" name="gender"/> Female
            </div>
            <div>
                <label for="city">City:</label>
                <select name="city" id="city">
                    <option value="">--Select--</option>
                    <option value="Delhi">AGRA</option>
                    <option value="Varanasi">MATHURA</option>
                    <option value="Mumbai">ALLAHABAD</option>
                </select><br><br>
            </div>
            <div>
                <label for="hobbies">Hobbies:</label>
                <div>
                    <input type="checkbox" id="hobby1" name="hobbies" value="Reading">
                    <label for="hobby1">BASKETBALL</label><br>
                    <input type="checkbox" id="hobby2" name="hobbies" value="Travelling">
                    <label for="hobby2">Travelling</label><br>
                    <input type="checkbox" id="hobby3" name="hobbies" value="Cooking">
                    <label for="hobby3">BADMINTON</label><br><br>
                </div>
            </div>
            <div class="d-flex justify-content-center">
                <button type="submit" class="btn btn-primary">CLICK HERE</button>
              </div>              
          </form>
        </div>
        <!-- Second column -->
        <div class="col-sm-6">
          <h1 class="text-center">TABLE</h1><br><br>
          <table class="table">
            <thead>
              <tr>
                <th class="border border-width-3">SNo</th>
                <th class="border border-width-3">Name</th>
                <th class="border border-width-3">Phone no</th>
                <th class="border border-width-3">Gender</th>
                <th class="border border-width-3">City</th>
                <th class="border border-width-3">Hobbies</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="border border-width-3">1</td>
                <td class="border border-width-3">ABHISHEK</td>
                <td class="border border-width-3">9838321023</td>
                <td class="border border-width-3">Male</td>
                <td class="border border-width-3">AGRA</td>
                <td class="border border-width-3">Travelling, BASKETBALL</td>
              </tr>
              <tr>
                <td class="border border-width-3">2</td>
                <td class="border border-width-3">HIMANSHU</td>
                <td class="border border-width-3">9876543211</td>
                <td class="border border-width-3">male</td>
                <td class="border border-width-3">MATHURA</td>
                <td class="border border-width-3">Reading, Cooking</td>
              </tr>
              <tr>
                <td class="border border-width-3">3</td>
                <td class="border border-width-3">Ishika</td>
                <td class="border border-width-3">9876453672</td>
                <td class="border border-width-3">FEMale</td>
                <td class="border border-width-3">ALLAHABAD</td>
                <td class="border border-width-3">Cooking, Travelling</td>
              </tr>
            </tbody>
        </table>
        </div>
      </div>
    </div>
    <!-- Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>
