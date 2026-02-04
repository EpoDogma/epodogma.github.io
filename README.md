<!doctype html>
<html>

<head>
  <title>Safe and Well</title>

  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <!-- Latest compiled and minified CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

  <!-- Custom CSS -->
  <link rel="stylesheet" href="/css/app.css">
</head>

<body>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="/">Safe and Well</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
  <!-- Latest compiled and minified JavaScript -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>

</html>

<div class="container">
  <div class="mt-6 row">
    <div class="col-md-12">
      <div class="row d-flex justify-content-center mt-5">
        <div class="col-md-12">
          <div class="card">
            <div class="card-body">
              <h1 class="card-title">Welcome to the safe and well app</h1>
              <div class="d-flex justify-content-center">
                <a href="/search" class="btn btn-primary btn-lg my-3 me-3">Search for a loved one</a>
                <a href="/report" class="btn btn-primary btn-lg my-3 me-3">Report your status</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="row d-flex justify-content-center mt-5">
    <div class="col-md-12">
      {{#if reports}}
      <hr />
      <div class="row">
        <div class="col-md-12 card">
          <div class="card-body">
            <h2 class="card-title">Current Reports</h2>
            {{!-- This is a partial --}}
            {{> reports }}
          </div>
        </div>
      </div>
      {{/if}}
    </div>
  </div>
</div>
