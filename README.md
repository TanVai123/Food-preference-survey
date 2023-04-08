# Food-preference-survey
User can Choose the food preferences from the form, Basic html code used
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> food survey</title>
    
    <style>
        body
        {
            font-family: sans-serif;
        }
    
    th,td {
        padding: 10px
    }
   label    
   {
    margin-right: 20px;
   }
   button
   {
    margin: 2px;
   }
    </style>
</head>
<body>
    <h1>food Prefence-Survey form </h1>
<h5> Please Fill out and submit the Survey form at the earliest </h5>
</hr>
    <form action="/"method="post">
    <table>
            <tr>
            <td>1.Name</td> 
            <td><input type ="text"name="user" /> </td>
            </tr>
            <tr>
            <td>2.Age</td>
            <td><input type="number"name="age" min="13" max="100" /> </td>
            </tr>
            <tr>
            <td>3.Where do you eat most?</td>
            <td> 
                <input type ="radio" id="home" name ="location" value="home"/>
            <label for="home">at home</label>
            <input type ="radio" id="Resturant" name ="location" value="Resturant"/> 
                <label for="Resturant">at Resturant</label> 
        
               <input type="radio" id="work_or_school" name="location" value="work_school"/>
                <label for="work_or_school">at work/school</label>
                </td>
                <tr>
                    <td colspan="2">4.Specify how often </td>

                             </tr>
                             
    <tr>
        <td colspan="2">
            <table style="font-size: 0.7em; border: 1px solid">
                        <thead>
                            <tr>
                                <th></th>
                        <th>Everyday</th>
                        <th>most often</th>
                        <th>few times a week</th>
                        <th>once in week</th>
                        <th>once in a month</th>
                        <th>less often than once a month</th>
                   </tr>
                    </thead>
                    <tbody>
                       
                        <tr>
                            <td > You prepare your own meal</td>
                            <td style="text-align: center"><input type="radio" name="you_prepare" value="every day" /></td>
                            <td style="text-align: center"><input type="radio" name="you_prepare" value="once a month" /></td>
                            <td style="text-align: center"><input type="radio" name="you_prepare" value="once a week" /></td>
                            <td style="text-align: center"><input type="radio" name="you_prepare" value="more often" /></td>
                            <td style="text-align: center"><input type="radio" name="you_prepare" value="once a month" /></td>
                            <td style="text-align: center"><input type="radio" name="you_prepare" value="less often once a month" /></td>
                        </tr>
                        <tr>
                            <td> You Eat out </td>
                            <td style="text-align: center"><input type="radio" name="you_eat_out" value="every day" /></td>
                            <td style="text-align: center"><input type="radio" name="you_eat_out" value="once a week" /></td>
                            <td style="text-align: center"><input type="radio" name="you_eat_out" value="more often" /></td>
                            <td style="text-align: center"><input type="radio" name="you_eat_out" value="once a month" /></td>
                            <td style="text-align: center"><input type="radio" name="you_eat_out" value="once a month" /></td>
                            <td style="text-align: center"><input type="radio" name="you_eat_out" value="less often once a month" /></td>
                        </tr>
                        <tr>
                            <td> You order food for home </td>
                            <td style="text-align: center"><input type="radio" name="you_order_food" value="every day" /></td>
                            <td style="text-align: center"><input type="radio" name="you_order_food" value="once a week" /></td>
                            <td style="text-align: center"><input type="radio" name="you_order_food" value="more often" /></td>
                            <td style="text-align: center"><input type="radio" name="you_order_food" value="once a month" /></td>
                            <td style="text-align: center"><input type="radio" name="you_order_food" value="once a month" /></td>
                            <td style="text-align: center"><input type="radio" name="you_order_food" value="less often once a month" /></td>
                        </tr>
                        </tr>
                    
                    
                </tr>
            
    </tr>
        
        <tr>
            <td colspan="2">5.The most common places you visit are Resturant serving food of origin:</td>
        </tr>
        <tr>
            <td colspan="2"></td>
            <table>
                <tr>
                    <td>
                        <input type="checkbox" id="polish" name="food_origin_preference" value="polish" />
                        <label for="polish">polish</label>
                    </td>

                    <td>
                        <input type="checkbox" id="Indian" name="food_origin_preference" value="Indian" />
                        <label for="Indian">Indian</label>
                    </td>
                    
                </tr>
                <tr>
                    <td>
                        <input type="checkbox" id="Italian" name="food_origin_preference" value="Italian" />
                        <label for="Italian">Italian</label>
                    </td>

                    <td>
                        <input type="checkbox" id="Spanish" name="food_origin_preference" value="Spanish" />
                        <label for="Spanish">Spanish</label>
                    </td>
                    
                </tr>
                <tr>
                    <td>
                        <input type="checkbox" id="Asian" name="food_origin_preference" value="Asian" />
                        <label for="Asian">Asian</label>
                    </td>

                    <td>
                        <input type="checkbox" id="Chinese" name="food_origin_preference" value="Chinese" />
                        <label for="Chinese">Chinese</label>
                    </td>
                    <tr>
                        <td>
                            <input type="checkbox" id="American" name="food_origin_preference" value="American" />
                            <label for="American">American</label>
                        </td>
    
                        <td>
                            <input type="checkbox" id="Other" name="food_origin_preference" value="Other" />
                            <label for="Other">Other</label>
                        </td>
                        <tr>
                            <td>6.Given an option would you go Vegan</td>
                            <td><input type="radio" name="Vegan" id="Sure" value="Sure" />
                            <label for="Sure">Sure</label> 
                            <td><input type="radio" name="Vegan" id="No" value="Sure" />
                                <label for="No">No</label> 
                            </td>
                        </tr>
                        <tr>
                            <td><button>submit</button><button type="reset">reset</button></td>
                        </tr>
                        
                    </tr>
                    
                </tr>
            </table>
        </tr>
        
        </tr>
    </form>
    </table>
</body>
</html>