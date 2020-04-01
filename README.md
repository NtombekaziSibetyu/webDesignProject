# webDesignProject
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF8">
        <link rel="stylesheet" type="text/css" href = "css/bootstrap-grid.min.css">
        <script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
        <script src="js/bootstrap.min.js"></script>
        <link rel="stylesheet" type="text/css" href="custom.css">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Page1</title>
    </head>
    <body>
        <div class="nav">
            <ul>
                <li><a href="#Home">Home</a></li>
                <li><a href="#Newsfeed">Newsfeed</a></li>
                <li><a href="#Users">Users</a></li>
                <li><a href="Admin">Admin</a></li>
            </ul>
        </div>
        <div class="row">
            <div class="col-sm-4">
                <div class="card">
                    <img class="card-img-top" src="Saved Pictures/lisa.jpeg" alt="Lisa image":>
                    <div class="card-body">
                        <h5 class="card-title">Accountant</h5>
                        <p class="card-text">
                        Fullname: Lisa Smith<br>
                        Email: SmithLisa@yahoo.com<br>
                        Cell number:0635278651<br>
                        Landline:0215456423</p>
                        
                    </div>
                </div>
            </div>
            <div class="col-sm-4">
                <div class="card">
                    <img class="card-img-top" src="Saved Pictures/kevin.jpeg" alt="kevin image":>
                    <div class="card=body">
                        <h5 class="card-title">Sales Manager</h5>
                        <p class="card-text">
                        Fullname:Kevin Sergh<br>
                        Email: Serghk@gmail.com<br>
                        Cell number: 078561492<br>
                        Landline:021537495
                    </p>
                    
                    </div>
                </div>
            </div>
            <div class="col-sm-4">
                <div class="card">
                    <img class="card-img-top" src="/Saved Pictures/enzo.jpeg" alt="enzo image":>
                    <div class="card=body">
                        <h5 class="card-title">Marketing Management</h5>
                        <p class="card-text">
                        Fullname: Enzo Mtoba<br>
                        Email: enzomtoba@gmail.com<br>
                        Cell number:0825034763<br>
                        Landline: 0214532075
                        </p>
                        <button class="btn btn-primary" data-toggle="modal" data-target = "#myModal">
                        See more
                        </button>
                        <div class="modal" id="myModal">
                            <div class="modal-dialog">
                                <div class="modal-content">
                                    <div class="modal header">
                                        <h5 class="modal-title">more details</h5>
                                        <button class="close" data-dismiss="modal">close</button>
                                    </div>
                                    <div class="modal-body">
                                    <p class="modal-content">
                                        Address:24,Plein Street, Mandalay,4556<br>
                                        Next of kin: Azra Moli <br>
                                        Relationship:Cousin<br>
                                        Next of kin contact no. :0810312584<br>
                                        Next of kin email:azram@gmail.co.za
                                    </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </body> 
</html>
