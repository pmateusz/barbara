---
layout: page
title: pages.about

namespace: about
permalink: /about-me/
permalink_pl: /o-mnie/
permalink_de: /ueber-mich/
---
<div class="container main-content blog-post">
  <h1>{% t pages.about %}</h1>
  <p class="post-details"></p>
  <div class="container-fluid">
    <div class="row">  
      <div class="col-md-4">
        <img src="/assets/images/barbara-e041824e4952149bad22fe28dc60cfdaf11a04bfc315c8d08e33539173901b90.jpg" alt="Barbara Piesowicz" class="img-thumbnail center-block" width="312" height="450">
      </div>
      <div class="blog-post col-md-8">
        <h1>Barbara Piesowicz</h1> 
        <h2>Adwokat, LL.M.</h2>
        <h3 class="text-muted">Wykształcenie</h3>
        <ul class="list-unstyled">
          <li>
            <p>Uniwersytet Jagielloński w Krakowie
            <br>
            <small>kierunek – prawo</small>
            </p>
          </li>
          <li>
            <p>Uniwersytet Jana Gutenberga w Moguncji, Niemcy
            <br>
            <small>studia LL.M.</small>
            </p>
          </li>
          <li>
            <p>Ochrona środowiska w prawie Unii Europejskiej i w prawie polskim
            <br>
            <small>studia podyplomowe</small>
            </p>
          </li>
        </ul>
        <h3 class="text-muted">Kontakt</h3>
        <ul class="fa-ul">
          <li><i class="fa-li fa fa-phone"></i>+48 795494729</li>
          <li><i class="fa-li fa fa-envelope-o"></i>barbara.piesowicz at adwokatura.pl</li>
        </ul>
      </div>
    </div>
    <div class="row">

      <blockquote class="blockquote">
        {% translate_file about/about.md %}
      </blockquote>
    </div>
  </div>
</div>