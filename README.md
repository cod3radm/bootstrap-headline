# bootstrap-headline

<!DOCTYPE html>

<html>
<head>
    <title>Create a Bootstrap Headline</title>
    
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <link href="https://cdnjs.com/libraries/animate.css/" rel='stylesheet' type='text/css'>
    
    <!--
    <script src="//code.jquery.com/jquery-1.12.4.js"></script>
    <script src="//code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
    
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <link rel="stylesheet" href="https://ajax.googleapis.com/ajax/libs/jqueryui/1.12.1/themes/smoothness/jquery-ui.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.js"></script>
    -->
    
    <link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
    
    <!-- You can add Bootstrap to any app by adding the following code to the top of your HTML -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"/>
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css"/>
    
</head>

<body>

<!-- Only change code above this line -->
<div class="container-fluid">
<h3 class="text-primary text-center" >jQuery Playground</h3>
    <div class="row">
        
        <div class="col-xs_6">
            <h4>#left-well</h4>
          <div id="left-well" class="well">
            <button id="target1" class="target" class="btn btn-default">#target1</button>
            <button id="target2" class="target" class="btn btn-default">#target2</button>
            <button id="target3" class="target" class="btn btn-default">#target3</button>
          </div>
            
            
        </div>
        <div class="col-xs_6">
            <h4>#right-well</h4>
          <div id="right-well" class="well">
            <button id="target4" class="target" class="btn btn-default">#target4</button>
            <button id="target5" class="target" class="btn btn-default">#target5</button>
            <button id="target6" class="target" class="btn btn-default">#target6</button>
          </div>
            
        </div>
        
    </div>
    
    <script>
    $("document").ready(function() {
        
        $("button").addClass("animated bounce");
        $("div").addClass("animated shake");
        
    });   
    </script>
</div>

</body>
</html>
