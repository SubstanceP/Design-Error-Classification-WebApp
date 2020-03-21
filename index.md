<html>
    <head>  
      <title>The Materialize Tabs Example</title>  
      <meta name = "viewport" content = "width = device-width, initial-scale = 1">        
      <link rel = "stylesheet"  
         href = "https://fonts.googleapis.com/icon?family=Material+Icons">  
      <link rel = "stylesheet"   
         href = "https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.3/css/materialize.min.css">  
      <style>
          .tabs-fixed-width {
            width:100% !important;
          }
      </style>
        
   </head>
   <body> 
   <div class="container" id="M">
      <div id="card" class="card">
    <div class="card-content">
      <p>Was a goal or pre-concieved notion (with regard to a system/object) in mind while commiting an incorrect action?</p>
    </div>
    <div class="card-tabs">
      <ul class="tabs tabs-fixed-width">
        <li class="tab"><a class="no-autoinit" href="#test4">Yes</a></li>
        <li class="tab"><a href="#test5">No</a></li>
        <li class="tab"><a class="active" href="#test6">Scenarios</a></li>
      </ul>
    </div>
    <div class="card-content grey lighten-4">
     <div id="test4">
        <div class="card">
          <div class="card-content">
            <p>The error type is Slip! Was your intended action forgotten</p>
          </div>
          <div class="card-tabs">
            <ul class="tabs tabs-fixed-width">
              <li class="tab"><a href="#test7">Yes</a></li>
              <li class="tab"><a href="#test8">No</a></li>
              <li class="tab"><a class="active" href="#test8" style="color:white;"> </a></li>
            </ul>
          </div>
          <div class="card-content grey lighten-4">
            <div id="test7">The Slip type is Memory-Lapse-Slip</div>
            <div id="test8">The Slip type is Action-Based-Slip</div>
          </div>
        </div>
      </div>
      <div id="test5">
        <div class="card">
          <div class="card-content">
            <p>The error type is Mistake! Was your goal, plan, or evaluation forgotten?</p>
          </div>
          <div class="card-tabs">
            <ul class="tabs tabs-fixed-width">
              <li class="tab"><a href="#test10">Yes</a></li>
              <li class="tab"><a href="#test11">No</a></li>
              <li class="tab"><a class="active" href="#test8" style="color:white;"> </a></li>
            </ul>
          </div>
          <div class="card-content grey lighten-4">
            <div id="test10">The Mistake type is Memory-Lapse-Slip</div>
            <div id="test11">
              <div class="card">
                <div class="card-content">
                  <p>Did you appropriately diagnose the problem?</p>
                </div>
                <div class="card-tabs">
                  <ul class="tabs tabs-fixed-width">
                    <li class="tab"><a href="#test12">Yes</a></li>
                    <li class="tab"><a href="#test13">No</a></li>
                  </ul>
                </div>
                <div class="card-content grey lighten-4">
                  <div id="test12">The Mistake type is Rule-Based-Mistake</div>
                  <div id="test13">The Mistake type is Knowledge-Based-Mistake</div>
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>
    <div id="test6">
    <ul class="collapsible">
    <li>
      <div class="collapsible-header"><i class="material-icons">filter_drama</i>Error Scenario Description</div>
      <div class="collapsible-body"><span>Revelead answer through completion of the activity, including detailed justifications.</span></div>
    </li>
    <li>
      <div class="collapsible-header"><i class="material-icons">place</i>Error Scenario Description</div>
      <div class="collapsible-body"><span>Revelead answer through completion of the activity, including detailed justification.</span></div>
    </li>
    <li>
      <div class="collapsible-header"><i class="material-icons">whatshot</i>Error Scenario Description</div>
      <div class="collapsible-body"><span>LRevelead answer through completion of the activity, including detailed justification.</span></div>
    </li>
  </ul>
  </div>
</div>



  <script type = "text/javascript" src = "https://code.jquery.com/jquery-2.1.1.min.js"></script>           
  <script src = "https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.3/js/materialize.min.js"></script> 
  <script>
    //var instance = M.Tabs.init(, onShow);
    //init materialize tab
     //var elem = $('.tab')
     //var options = {onShow}
     //var instance = M.Tab.init(elem, options);
     var instance = M.Tabs.init(el, options);



    document.addEventListener('DOMContentLoaded', function() {
    var elems = document.querySelectorAll('.collapsible');
    var instances = M.Collapsible.init(elems, options);
  });
     

  </script>

  </body>
</html>
