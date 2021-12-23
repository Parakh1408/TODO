# TODO
Todo Webpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Monoton&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <link rel="stylesheet" href="style1.css">
    <title>TODO List</title>
</head>
<body>
    <div class="app">
        <div class="heading">
            <div class="heading__title">TODO</div>
            <div class="heading__sub-title">make my day</div>
        </div>
        <div class="todo">
            <ul class="todo__list">
                <li class="todo__item">
                    <span class="todo__icon-tick material-icons">check_box_outline_blank</span>
                    <span class="todo__text todo__text">Sleep</span>
                    <span class="todo__icon-delete material-icons">delete_outline</span>
                </li>                
            </ul>
        </div>
        <div class="new">
            <form class="new__form">
                <input class="new__input" type="text" name="new_text" placeholder="Add item ...">
            </form>
            <span class="new__submit material-icons">control_point</span>
        </div>
    </div>
    <script src="app.js"></script>
</body>
</html>
