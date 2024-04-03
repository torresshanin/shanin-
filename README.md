# shanin torres bscs 1-1 irregular 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Menu</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-KyZXEAg3QhqLMpG8r+Knujsl7/1L_dstPt3HV5HzF6Gvk/e9T9hXmJ58bldgTk+" crossorigin="anonymous">
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 2rem;
        }

        h1 {
            text-align: center;
            margin-bottom: 3rem;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th,
        td {
            padding: 0.75rem;
            border: 1px solid #fd0ff5;
        }

        th {
            background-color: #fd0ff5;
            font-weight: bold;
        }

        tr:nth-child(even) {
            background-color: #fd0ff5;
        }

        @media (max-width: 767.98px) {
            h1 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>Shanin's viking Restaurant Menu</h1>
        <table>
            <thead>
                <tr>
                  <th>Invoice</th>
                    <th>customer's name</th>
                    <th>How many have been purchased?</th>
                    <th>item name</th>
                    <th>Description</th>
                    <th>Price</th>
                    <th>Purchased Price</th>
                    <th>Status</th>
                    
            <tbody>
                <tr>
                    <td>001</td>
                    <td>earl john</td>
                    <td>1px</td>
                    <td>Bruschetta </td>
                    <td>Toasted bread topped with diced tomatoes, garlic, basil, and olive oil.</td>
                    <td>$9.99</td>
                    <td>$2.50</td>
                    <td>Appetizer</td>
                </tr>
                <tr>
                    <td>002</td>
                    <td>malou</td>
                    <td>1px</td>
                    <td>Spaghetti Carbonara</td>
                    <td> Spaghetti pasta tossed in a creamy egg sauce with bacon and Parmesan cheese.</td>
                    <td> $14.99</td>
                    <td> $4.25</td>
                    <td>Pasta</td>
                </tr>
                <tr>
                    <td>003</td>
                    <td>khyla</td>
                    <td>10px</td>
                    <td>Lobster Bisque</td>
                    <td> Creamy soup made with lobster stock, cream, and sherry, garnished with chopped lobster meat and chives.</td>
                    <td> $100</td>
                    <td> 50</td>
                    <td>soup</td>
                </tr>
                <tr>  <td>004</td>
                    <td>orlando</td>
                    <td>1px</td>
                    <td>Filet Mignon</td>
                    <td> 8 oz. center-cut filet mignon grilled to your preference and served with garlic mashed potatoes and grilled asparagus..</td>
                    <td> $32</td>
                    <td> $22</td>
                    <td>Entrees</td>
                </tr>
                <tr>  <td>005</td>
                    <td>powky</td>
                    <td>3px</td>
                    <td>Shrimp Scampi Linguine</td>
                    <td> Sautéed shrimp in a garlic butter sauce, tossed with linguine pasta, cherry tomatoes, and parsley..</td>
                    <td> $60</td>
                    <td> $30</td>
                    <td>seafood</td>
                </tr>
                <tr>  <td>006</td>
                    <td>melona</td>
                    <td>6px</td>
                    <td>chongke lava cake</td>
                    <td> Warm chocolate cake with a gooey chocolate center, served with vanilla ice cream and chocolate sauce..</td>
                    <td> $60</td>
                    <td> $24</td>
                    <td>dessert</td>
                </tr>
                <tr>  <td>007</td>
                    <td>jack</td>
                    <td>1px</td>
                    <td>House-made Lemonade</td>
                    <td> Freshly squeezed lemon juice sweetened with cane sugar and served over ice.</td>
                    <td> $4</td>
                    <td> $1.50</td>
                    <td>beverages</td>
                </tr>
                <tr>  <td>008</td>
                    <td>elezar</td>
                    <td>1px</td>
                    <td>Spinach and Artichoke Dip </td>
                    <td> Creamy blend of spinach, artichokes, and cheeses, served with crispy tortilla chips for dipping.</td>
                    <td> $10</td>
                    <td> $4</td>
                    <td>Appetizer</td>
                </tr>
                <tr>  <td>009</td>
                    <td>henry</td>
                    <td>5px</td>
                    <td>Stuffed Mushrooms</td>
                    <td> Button mushrooms stuffed with a savory mixture of Italian sausage, breadcrumbs, and Parmesan cheese, baked to perfection..</td>
                    <td> $45</td>
                    <td> $17.5</td>
                    <td>Appetizer</td>
                </tr>
                <tr>  <td>010</td>
                    <td>liza</td>
                    <td>1px</td>
                    <td>Classic Caesar Salad </td>
                    <td>Crisp romaine lettuce tossed in Caesar dressing with garlic croutons and grated Parmesan cheese. </td>
                    <td> $12</td>
                    <td> $5</td>
                    <td>Salad</td>
                </tr>
                <tr>  <td>011</td>
                    <td>adriane</td>
                    <td>2px</td>
                    <td>raft Beer (Bottle) </td>
                    <td> Selection of local and imported craft beers..</td>
                    <td> $12</td>
                    <td> $5.18</td>
                    <td>beverages</td>
                </tr>
                <tr>  <td>012</td>
                    <td>mella</td>
                    <td>2px</td>
                    <td>House Wine (Glass)</td>
                    <td> hoice of red or white wine by the glass.</td>
                    <td> $16</td>
                    <td> $8</td>
                    <td>beverages</td>
                </tr>
                <tr>  <td>013</td>
                    <td>johnny</td>
                    <td>2px</td>
                    <td>Pan-Seared Salmon</td>
                    <td>Fresh Atlantic salmon fillet seasoned with lemon herb butter and pan-seared until crispy on the outside and tender on the inside. Served with wild rice pilaf and grilled asparagus </td>
                    <td> $48</td>
                    <td> $28</td>
                    <td>seafood</td>
                </tr>
                <tr>  <td>014</td>
                    <td>elly</td>
                    <td>1px</td>
                    <td>Pesto Pasta Primavera</td>
                    <td> Linguine pasta tossed with a creamy basil pesto sauce, sautéed vegetables, and cherry tomatoes. Topped with grated Parmesan cheese.</td>
                    <td> $18</td>
                    <td> $5</td>
                    <td>main Courses</td>
                </tr>
                <tr>  <td>015</td>
                    <td>cleford</td>
                    <td>3px</td>
                    <td>Caprese Salad</td>
                    <td> Slices of fresh tomatoes, buffalo mozzarella cheese, and basil leaves drizzled with balsamic glaze and olive oil.</td>
                    <td> $30</td>
                    <td> $10.5</td>
                    <td>appetizer</td>
                </tr>
                <tr>  <td>016</td>
                    <td>liane</td>
                    <td>1px</td>
                    <td>Crispy Calamari</td>
                    <td> Lightly breaded and fried calamari rings served with marinara sauce and lemon wedges.</td>
                    <td> $10</td>
                    <td> $3.50</td>
                    <td>appetizer</td>
                </tr>
                <tr>  <td>017</td>
                    <td>jade</td>
                    <td>1px</td>
                    <td>Spinach Artichoke Dip</td>
                    <td>Creamy spinach and artichoke dip served with tortilla chips</td>
                    <td> $11.99</td>
                    <td>  $3.75</td>
                    <td>Appetizer</td>
                </tr>
                <tr>  <td>018</td>
                    <td>sharon</td>
                    <td>1px</td>
                    <td>Ribeye Steak </td>
                    <td> Juicy ribeye steak cooked to your preference and served with mashed potatoes and seasonal vegetables.</td>
                    <td> $24.99</td>
                    <td> $12.00</td>
                    <td>Main Courses</td>
                </tr>
                <tr>  <td>019</td>
                    <td>linda</td>
                    <td>1px</td>
                    <td>Grilled Salmon</td>
                    <td>  Fresh Atlantic salmon fillet seasoned and grilled to perfection.</td>
                    <td>  $18.99</td>
                    <td>  $7.50</td>
                    <td>Main Courses</td>
                </tr>
                <tr>  <td>020</td>
                    <td>caroline</td>
                    <td>1px</td>
                    <td>New York Cheesecake</td>
                    <td> Creamy cheesecake served with a raspberry coulis.</td>
                    <td> $8.99</td>
                    <td> $4.25</td>
                    <td>dessert</td>
                </tr>
                <tr>
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
                  
            </tbody>
                 </tr>
            </thead>
        </table>
    </div>
</body>

</html>
cdn.jsdelivr.net
                  
