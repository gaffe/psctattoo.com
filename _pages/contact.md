---
layout: default
title: Contact
class: reverse
navigation: header
order: 5
---

<section class="hero is-page is-dark is-bold">
  <div class="hero-body">
    <div class="container has-text-centered">
      <h1 class="title">Contact Us</h1>
    </div>
  </div>
</section>
<section class="section">
  <div class="container">
    <div class="columns is-variable is-8">
      <div class="column">
        <div class="content">
          <h2>General Information</h2>
          <p>If you’d like to get in touch with us for a consultation, you can do so in person at the shop or by phone. We recommend having an appointment but walk-ins are certainly welcome.</p>
          <p>Before getting in touch, here are a couple of things to note so you don’t waste your time:</p>
          <ul>
            <li>We don’t offer any piercing services</li>
            <li>We don’t tattoo minors under any circumstances</li>
            <li>We accept cash only</li>
            <li>Deposits are non-refundable</li>
          </ul>
        </div>
      </div>
      <div class="column">
        <div class="content">
          <h2>Address and Contact</h2>
          <p>
            1925 rue Centre<br>
            Montréal, Québec<br>
            H3K 1J1<br>
            Email: <a href="mailto:info@psctattoo.com" class="has-text-weight-bold">info@psctattoo.com</a><br>
            Telephone: <a href="tel:+15149312325" class="has-text-weight-bold">+1 514 931 2325</a>
          </p>
          <h2>Hours of Operation</h2>
          <p>
            Open: <strong>Tuesday to Saturday</strong><br>
            Hours: <strong>10:30am to 5:30pm</strong>
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
<section class="section">
  <div style="height: 500px;" class="12u" id="map"></div>
</section>




<script type="text/javascript">
            function init() {
                var mapOptions = {
                    zoom: 12,
                    center: new google.maps.LatLng(45.4824635, -73.5652401), // New York
                    styles: [{"featureType":"water","elementType":"geometry.fill","stylers":[{"color":"#d3d3d3"}]},{"featureType":"transit","stylers":[{"color":"#808080"},{"visibility":"off"}]},{"featureType":"road.highway","elementType":"geometry.stroke","stylers":[{"visibility":"on"},{"color":"#b3b3b3"}]},{"featureType":"road.highway","elementType":"geometry.fill","stylers":[{"color":"#ffffff"}]},{"featureType":"road.local","elementType":"geometry.fill","stylers":[{"visibility":"on"},{"color":"#ffffff"},{"weight":1.8}]},{"featureType":"road.local","elementType":"geometry.stroke","stylers":[{"color":"#d7d7d7"}]},{"featureType":"poi","elementType":"geometry.fill","stylers":[{"visibility":"on"},{"color":"#ebebeb"}]},{"featureType":"administrative","elementType":"geometry","stylers":[{"color":"#a7a7a7"}]},{"featureType":"road.arterial","elementType":"geometry.fill","stylers":[{"color":"#ffffff"}]},{"featureType":"road.arterial","elementType":"geometry.fill","stylers":[{"color":"#ffffff"}]},{"featureType":"landscape","elementType":"geometry.fill","stylers":[{"visibility":"on"},{"color":"#efefef"}]},{"featureType":"road","elementType":"labels.text.fill","stylers":[{"color":"#696969"}]},{"featureType":"administrative","elementType":"labels.text.fill","stylers":[{"visibility":"on"},{"color":"#737373"}]},{"featureType":"poi","elementType":"labels.icon","stylers":[{"visibility":"off"}]},{"featureType":"poi","elementType":"labels","stylers":[{"visibility":"off"}]},{"featureType":"road.arterial","elementType":"geometry.stroke","stylers":[{"color":"#d6d6d6"}]},{"featureType":"road","elementType":"labels.icon","stylers":[{"visibility":"off"}]},{},{"featureType":"poi","elementType":"geometry.fill","stylers":[{"color":"#dadada"}]}]
                };

                var mapElement = document.getElementById('map');

                var map = new google.maps.Map(mapElement, mapOptions);

                var marker = new google.maps.Marker({
                    position: new google.maps.LatLng(45.4824635, -73.5652401),
                    map: map,
                    title: 'PSC Tattoo'
                });
            }
</script>
<script async defer src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDOUnyHLomgcN5E5j9JCm-eZHOiqvVOjYA&callback=init" type="text/javascript"></script>
