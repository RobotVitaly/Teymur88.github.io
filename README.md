# Teymur88.github.io
Наш Супер-Сайт
<?php session_start();?>
<!DOCTYPE html>
<html lang="ru">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!--User CSS-->
    <link rel="stylesheet" href="style.css">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <title><?php echo $title?></title>
    </head>
    <body>
        <nav class="navbar navbar-light bg-light">
          </div>          
              <div class="row">
            <div class="header__inner">
              <div class="header__logo">
                <img src="/img/bender.png" width="80" alt="Logo">
              </div>
              <a class="navbar-brand">LifeBlog</a>
            </div>
          </div>
          <nav class="nav nav-pills flex-column flex-sm-row">
              <a class="flex-sm-fill text-sm-center nav-link active" href="#">Active</a>
              <a class="flex-sm-fill text-sm-center nav-link" href="#">Longer nav link</a>
              <a class="flex-sm-fill text-sm-center nav-link" href="#">Link</a>
              <a class="flex-sm-fill text-sm-center nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
            </nav>
          
          <form class="form-inline">
            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success mr-2 my-2 my-sm-0" type="submit">
              Search
            </button>
            <?php if (empty($_SESSION['id'])): ?>
                <a class="btn btn-success mr-1" href="auth.php">Вход</a>    
                <a class="btn btn-success" href="reg.php">Регистрация</a>
            <?php else: ?>
                <a class="btn btn-success" href="exit.php">Выход</a>
            <?php endif?>
          </form>
        </nav>
        </div>
        
        <!-- FOOTER.begin -->
    <footer class="bd-footer text-muted" style="position: fixed; left: 0; bottom: 0; background:#ecf4ef; width: 100%;">
      <div class="container-fluid p-3 p-md-10">
        <div class="footer"></div>
        <div class="row">
          <div class="nav">
            <ul class="nav flex-column">
                <li class="nav-item">
                  <a class="nav-link active" href="#">Active</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link disabled" href="#">Disabled</a>
                </li>
              </ul>
            </div>
        </div>
      </div>
    </footer>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  </body>
</html>
      
