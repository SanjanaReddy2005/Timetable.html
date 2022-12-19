<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time Table</title>
    <style>
        table,td,th{
            border: 1px solid black;
        }

    </style>
</head>
<body>
    <table>
        <thead>
            <th>Period<br>Day</th>
            <th>1<br>9:00AM-10:00AM</th>
            <th>2<br>10:00AM-11:00AM</th>
            <th>3<br>11:00AM-12:00PM</th>
            <th>4<br>12:00PM-1:00PM</th>
            <th>1:00PM-2:00PM</th>
            <th>5<br>2:00PM-3:00PM</th>
            <th>6<br>3:00PM-4:00PM</th>
            <th>7<br>4:00PM-5:00PM</th>
            <th>8<br>5:00PM-6:00PM</th>
        </thead>
        <tbody>
            <tr>
                <th>MON</th>
                <td>-</td>
                <td>L:IC 153</td>
                <td>L:CH 103</td>
                <td>L:MA 105</td>
                <td rowspan="6">L<br>U<br>N<br>C<br>H</td>
                <td>T:CH 103</td>
                <td>T:MA 105</td>
                <td>-</td>
                <td>T:PH 105</td>
            </tr>
            <tr>
                <th>TUE</th>
                <td>-</td>
                <td>L:PH 105</td>
                <td>L:CS 103</td>
                <td>L:MA 105</td>
                <td colspan="3"> T:HS 159  </td>
                <td>-</td>
            </tr>
            <tr>
                <th>WED</th>
                <td>L:PH 105</td>
                <td>L:IC 153</td>
                <td>L:CH 103</td>
                <td>L:CS 103</td>
                <td colspan="3">P:CH 103</td>
                <td>-</td>
            </tr>
            <tr class="border">
                <th>THU</th>
                <td>UP</td>
                <td>DAA</td>
                <td>AJWT</td>
                <td>CA</td>
                <td colspan="3" >CN&UNIX LAB</td>
                <td>-</td>
            </tr>
            <tr class="border">
                <th>FRI</th>
                <td>-</td>
                <td>L:PH 105</td>
                <td>L:CH 103</td>
                <td>L:MA 105</td>
                <td colspan="3">P:IC 153</td>
                <td>-</td>
            </tr>
            <tr class="border">
                <th>SAT</th>
                <td>-</td>
                <td>L:CH 105</td>
                <td>L:CS 103</td>
                <td>L:MA 105</td>
                <td colspan="3">P:IC 151</td>
                <td>-</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
