<!doctype html>
<html>
    <head>
        <title>
            <meta charset "utf-8">
            test
        </title>
    </head>
    <body>
        <form action = "codk.php" method = "get">
                tpye: <input type="text" name = "uw">
                <br>
                <input type = "submit">
        </form>
        <?php
            if (isset($_GET["uw"]))
            {
                echo $_GET["uw"];
            }
        ?>
        
    </body>
</html>
