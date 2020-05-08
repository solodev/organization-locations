# organization-locations
Most end users will want to see a list of all of your locations so that they can best find one that meets their needs. You can show this list with some pertinent information to help end users find an appropriate match.

## Tutorial
For detailed instruction's, view Solodev's [How to List Your Organization’s Locations On A Single Page](http://www.solodev.com/blog/web-design/how-to-list-your-organizations-locations-on-a-single-page-.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/9wj4ret6/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="container mt-5 mb-lg-5 pb-5">
  <h1 class="text-center text-lg-left h2">Locations</h1>
  <div class="mt-4 location_listings">
    <div class="row py-3 bg-light-gray-even">
      <div class="col-lg-2 col-md-6 text-center mx-auto image">
        <img src="https://raw.githubusercontent.com/solodev/organization-locations/master/images/kennedy_space_center.jpg" alt="Kennedy Space Center" class="img-fluid">
      </div>
      <div class="col-lg-8 mt-4 mt-lg-0">
        <h2 class="h5">Kennedy Space Center</h2>
        <div class="d-md-flex">
          <p class="mb-1 pr-md-2 border-black border-md-right">Kennedy Space Center</p>
          <p class="mb-1 px-md-2 border-black border-md-right">Florida, 32899</p>
          <a href="tel:(321) 867-5000" class="mb-1 px-md-2 text-black"><strong>(321) 867-5000</strong></a>
        </div>
        <ul class="pl-3">
          <li class="mb-0">Mon-Fri 9am-6pm</li>
          <li class="mb-0">Sat 9am-6pm</li>
          <li class="mb-0">Sun 11am-4pm</li>
        </ul>
      </div>
      <div class="col-lg-2 align-self-center text-center p-0">
        <a href="#" class="btn btn-outline-dark px-5 py-2 rounded-0">Select</a>
      </div>
    </div>

    <div class="row py-3 bg-light-gray-even">
      <div class="col-lg-2 col-md-6 text-center mx-auto image">
        <img src="https://raw.githubusercontent.com/solodev/organization-locations/master/images/Goddard_Space_Flight_Center.jpg" alt="Goddard Space Flight Center" class="img-fluid">
      </div>
      <div class="col-lg-8 mt-4 mt-lg-0">
        <h2 class="h5">Goddard Space Flight Center</h2>
        <div class="d-md-flex">
          <p class="mb-1 pr-md-2 border-black border-md-right">8800 Greenbelt Rd</p>
          <p class="mb-1 px-md-2 border-black border-md-right">Greenbelt, MD 20771</p>
          <a href="tel:(301) 286-2000" class="mb-1 px-md-2 text-black"><strong>(301) 286-2000</strong></a>
        </div>
        <ul class="pl-3">
          <li class="mb-0">Mon-Fri 9am-7pm</li>
          <li class="mb-0">Sat 9am-6pm</li>
          <li class="mb-0">Sun 11am-4pm</li>
        </ul>
      </div>
      <div class="col-lg-2 align-self-center text-center p-0">
        <a href="#" class="btn btn-outline-dark px-5 py-2 rounded-0">Select</a>
      </div>
    </div>

    <div class="row py-3 bg-light-gray-even">
      <div class="col-lg-2 col-md-6 text-center mx-auto image">
        <img src="https://raw.githubusercontent.com/solodev/organization-locations/master/images/Saturn_V_building_Johnson_Space_Center.jpg" alt="Johnson Space Center" class="img-fluid">
      </div>
      <div class="col-lg-8 mt-4 mt-lg-0">
        <h2 class="h5">Johnson Space Center</h2>
        <div class="d-md-flex">
          <p class="mb-1 pr-md-2 border-black border-md-right">2101 E NASA Pkwy</p>
          <p class="mb-1 px-md-2 border-black border-md-right">Houston, TX 77058</p>
          <a href="tel:(281) 483-0123" class="mb-1 px-md-2 text-black"><strong>(281) 483-0123</strong></a>
        </div>
        <ul class="pl-3">
          <li class="mb-0">Mon-Fri 9am-7pm</li>
          <li class="mb-0">Sat 9am-6pm</li>
          <li class="mb-0">Sun 11am-4pm</li>
        </ul>
      </div>
      <div class="col-lg-2 align-self-center text-center p-0">
        <a href="#" class="btn btn-outline-dark px-5 py-2 rounded-0">Select</a>
      </div>
    </div>
  </div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```

