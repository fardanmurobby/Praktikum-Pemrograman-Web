# Praktikum-Pemrograman-Web
<!DOCTYPE html>
<html lang="id">
<head>
    <title>Pizza Beast</title>
</head>
<body style="text-align: left;">
    <h1>Pizza Beast</h1>
    <P style="margin-left:10px;">Your Information</p>
    <form action="/pesanan_pizza.html">
        <div style="margin-left: 20px;">
            <label for="nama">Name:</label>
            <input type="text" id="nama" name="nama" value=" "><br>
            <label for="alamat"> Address:</label>
            <input type="text" id="alamat" name="alamat" value=" "><br>
            <label for="nomorhp">Telephone Number:</label>
            <input type="text" id="nomorhp" name="nomorhp" value=" "><br>
            <label for="e-mail">Email:</label>
            <input type="email" id="e-mail" name="e-mail" value=" "><br>
            <p>Delivery Instructions:</p>
            <textarea name="catat" rows="10" cols="30"></textarea>
            <br>    

            <p><strong> Design Your Dream Pizza </strong></p>
            <p> Pizza specs :</p>
            <p>Crust (Choose one):</p>
            <input type="radio" name="ukuran box" value="Classic White">
            <label>Classic White</label><br>
            <input type="radio" name="ukuran box" value="Cheese Stuffled Crust">
            <label>Cheese Stuffled Crust</label><br>
            <input type="radio" name="ukuran box" value="Gluten-free">
            <label>Gluten-free</label><br>

            <p>Toppings (Choose as many as you want ) :</p>
            <input type="checkbox" id="topping1" name="topping1" value="Mozarella Cheese">
            <label for="topping1"> Mozarella Cheese </label><br>
            <input type="checkbox" id="topping2" name="topping2" value="Mushrooms">
            <label for="topping2"> Mushrooms </label><br>
            <input type="checkbox" id="topping3" name="topping3" value="Peppers">
            <label for="topping3"> Peppers </label><br>
            <input type="checkbox" id="topping4" name="topping4" value="Red Sauce">
            <label for="topping4"> Red Sauce </label><br>
            <input type="checkbox" id="topping5" name="topping5" value="White Sauce">
            <label for="topping5"> White Sauce </label><br>
            <input type="checkbox" id="topping6" name="topping6" value="Crispy Tomatoes">
            <label for="topping6"> Crispy Tomatoes </label><br>
            <input type="checkbox" id="topping7" name="topping7" value="Hot Sausage ">
            <label for="topping7"> Hot Sausage </label>
            <br><br>

            <p><b>Number</b></p>
            <label>How many pizzas:
                <input type="number" name="pizza" min="1" max="10"></label>
                <br><br>
            <input  type ="submit" value="Bring me a pizza!" name="proses"></a>
            <input type="reset" value="Reset">
        </div>
    </form>
</body>
</html>