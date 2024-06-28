<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>

<body>
  <div class="container mt-5">
    <!-- Nav tabs -->
    <ul class="nav nav-tabs" id="myTab" role="tablist">
      <li class="nav-item">
        <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-selected="true">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" id="profile-tab" data-toggle="tab" href="#profile" role="tab" aria-controls="profile" aria-selected="false">Profile</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" id="contact-tab" data-toggle="tab" href="#contact" role="tab" aria-controls="contact" aria-selected="false">Contact</a>
      </li>
    </ul>
    <!-- Tab panes -->
    <div class="tab-content mt-3">
      <div class="tab-pane fade show active" id="home" role="tabpanel" aria-labelledby="home-tab">
        <h3>Home Content</h3>
        <p>This is the content of the Home tab.</p>
      </div>
      <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">
        <h3>Profile Content</h3>
        <p>This is the content of the Profile tab.</p>
      </div>
      <div class="tab-pane fade" id="contact" role="tabpanel" aria-labelledby="contact-tab">
        <h3>Contact Content</h3>
        <p>This is the content of the Contact tab.</p>
      </div>
    </div>
  </div>
</body>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
