# lab6web

# Nama : Taufilk Eka Albani
# Nim  : 312210347
# Kelas: TI.22.A3

1. Buatlah folder baru dengan nama lab6_css_framework
```py
<!DOCTYPE html>
<html lang="en" >
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>lab6_css_framework</title>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
```

2. Selanjutnya membuat navbar membuat komponen website yang berupa menu
```py
           <!--NAVBAR-->
            <div class="jumbotron jumbotron-fluid bg-light pb-2 mb-1">
              <div class="container">
                <h1 class="display-4">Layout Sederhana</h1>
              </div>
            </div>
            
            <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
              <a class="navbar-brand" href="#">Navbar</a>
              <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Article</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link">contact</a>
                  </li>
                </ul>
              </div>
            </nav>
```

## Tampilan



3. Jumbroton adalah satu element yang di buat untuk bertujuan membuat semacam pengumuman konten khusus atau informasi tentang halaman web
```py
        <!--JUMBOTRON-->
    <div class="jumbotron">
    <h1 class="display-4">Hello, world!</h1>
    <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat.</p>
    <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
    </div>
     <div class="d-flex p-2">
    <div class="p-2">

```
## Tampilan



4. Card 1 untuk membuat body konten menggunakan card
```py
    <!--CARDS-->
    <div class="row" >
      <div class="col">
      <div class="card pt-3">
        <img src="120px.png" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h5 class="card-title text-center">Heading</h5>
          <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-3">View Detail</a></p>
        </div>
      </div>
      </div>
      <div class="col">
      <div class="card pt-3">
        <img src="120px.png" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h5 class="card-title text-center">Heading</h5>
          <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-3">View Detail</a></p>
        </div>
      </div>
      </div>
      <div class="col">
      <div class="card pt-3">
        <img src="120px.png" class="card-img-top rounded-circle" alt="...">
        <div class="card-body">
          <h5 class="card-title text-center">Heading</h5>
          <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
          <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-3">View Detail</a></p>
        </div>
      </div>
      </div>
      </div>

<style css >
  .card-img-top{
  width: 120px;
  align-self: center;
}

footer {
    clear:both;
  background-color:#1d1d1d; 
  padding:20px;
  color:#eee;
}

</style>
<hr>
```
## Tampilan



6. List group menambahkan widget disamping kanan card 1
```py
<!--LIST GROUP-->
  <div class="col">
  <div class="list-group">
    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
      Widget Header
    </a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
  </div>
  <div class="list-group mt-3">
    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
      Widget Text
    </a>
    <span class="list-group-item list-group-item-action">Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu.
      Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</span>
  </div>
</div>  
</div>
</div>
```
7. Card 2
```py
<!--LIST GROUP-->
  <div class="col">
  <div class="list-group">
    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
      Widget Header
    </a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
  </div>
  <div class="list-group mt-3">
    <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
      Widget Text
    </a>
    <span class="list-group-item list-group-item-action">Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu.
      Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</span>
  </div>
</div>  
</div>
</div>
```
## Tampilan



8. Tampilan full
