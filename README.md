<!DOCTYPE html>
<html lang="en">
<head>
    <title>News</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        * {
            box-sizing: border-box;
        }

        /* Style the body */
        body {
            font-family: Arial;
            margin: 0;
            background-color: #aaaaaa;
        }

        /* Header/logo Title */
        .header {
            padding: 80px;
            text-align: center;
            background: #1abc9c;
            color: white;
        }

        /* Increase the font size of the heading */
        .header h1 {
            font-size: 40px;
        }

        /* Style the top navigation bar */
        .navbar {
            overflow: hidden;
            background-color: #333;
        }

        /* Style the navigation bar links */
        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        /* Right-aligned link */
        .navbar a.right {
            float: right;
        }

        /* Change color on hover */
        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }

        /* Column container */
        .row {
            display: -ms-flexbox; /* IE10 */
            display: flex;
            -ms-flex-wrap: wrap; /* IE10 */
            flex-wrap: wrap;
        }

        /* Create two unequal columns that sits next to each other */
        /* Sidebar/left column */
        .side {
            -ms-flex: 30%; /* IE10 */
            flex: 30%;
            background-color: #f1f1f1;
            padding: 20px;
        }

        /* Main column */
        .main {
            -ms-flex: 70%; /* IE10 */
            flex: 70%;
            background-color: white;
            padding: 20px;
        }

        /* Fake image, just for this example */
        .fakeimg {
            background-image: url("111.jpg");
            width: 100%;
            padding: 500px;
        }

        /* Footer */
        .footer {
            padding: 20px;
            text-align: center;
            background: #ddd;
        }

        /* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
        @media screen and (max-width: 700px) {
            .row {
                flex-direction: column;
            }
        }

        /* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
        @media screen and (max-width: 400px) {
            .navbar a {
                float: none;
                width: 100%;
            }
        }
    </style>
</head>
<body>

<div class="header">
    <h1>News iphone</h1>

</div>


<div class="row">
    <div class="side">

        <div class="fakeimg"  style="height:200px;" > Image</div>
        <p>Реальная цена iPhone 12 оказалась выше объявленной на презентации
            iPhone 12 на самом деле стоит 829 долларов, а iPhone 12 mini — 729 долларов

            iPhone 12 в самом популярном цвете будет дороже на старте продаж
            Как стало известно, iPhone 12 на самом деле стоит не 799 долларов, как было объявлено на вчерашней пресс-конференции. Если вы зайдете на сайт Apple и посмотрите цены на iPhone 12, то на самом деле цена без SIM-карты оператора составит 829 долларов. iPhone 12 mini стоит 729 долларов, а не 699 долларов.

            Рекламируемые цены на самом деле включают скидку оператора связи в размере 30 долларов, которая доступна только для клиентов AT&T и Verizon. Это означает, что если вы покупаете разблокированную версию без SIM-карты или через T-Mobile или Sprint, цена телефона составляет 829 долларов.

            То же самое и с iPhone 12 mini. Реальная цена iPhone 12 mini составляет 729 долларов, если вы не имеете права на скидку в 30 долларов при покупке через AT&T или Verizon. Также похоже, что международные покупатели за пределами США будут вынуждены платить более высокую цену, поскольку специальные предложения операторов не действуют в других странах.</p>


    </div>

</div>

<div class="footer">

</div>

</body>
</html># balausa12.gethub.uo
