# html-basic-table

<!DOCTYPE html>
<html>
<head>
   <style>
       
 table,th,td {
    
    border: solid gold;
    border-collapse: collapse;
}
th, td{

    padding: 25px;
    text-align: center;
}
 </style>
 
 <title>
     Table
 </title>
</head>
<body>
    <table>

        <tr>
            <th rowspan="2", colspan="6">Company Logo</th>
            <th colspan="2">Sample Product Details</th>
          </tr>
          <tr>
              <th>all rates>rs 100000</th>
              <th>total>=2000/</th>
              </tr>
              <tr>
                  <th>Item</th>
                  <th colspan="5">Qty</th>
                  <th>Rate</th>
                  <th>Total</th>
              </tr>
              <tr>
              <th>Mobile Phone</th>
              <th rowspan="3" colspan="5">Each 1 no.</th>
              <th>23000</th>
              <th>23456</th>   
              </tr>
              <tr>
             <th>Desk Top Computer</th>
             <th>rs24556</th>
             <th>34567</th>
              </tr>
</table>

    
</body>
</html>
