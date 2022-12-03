<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>



    <script>

             // Calculate Your Own Age Program  (Date of Birth)....


      var date =  prompt("Enter The Date which You are Born ");
      var month = prompt("Enter The Month which You are Born ");
      var year = prompt("Enter The Year which You are Born");

      var cdate = prompt("Enter The  current Date ");
           var cmonth = prompt("Enter The  Current Month ");
          var cyear = prompt("Enter The current  Year ");
   var date1 , month1 , year1 ;

   
      
      if(date<=cdate)
     
      { 
        date1 = 30 + date;

        //  temp=date +30;
        // date1 = temp -cdate ;  
    
      
      }
      else{
        console.log("Date is correct");
      }
      if(month<=cmonth)
      {
        month1 = month + 12;
      }
      else{
        console.log("month is correct");
      }

      console.log("exact Age ", date1);
      console.log("exact Age ", month1);
      console.log("exact Age ", year1);



    </script>

</body>
</html>
