---
layout: page
title : Contributors
team:
  - name: Gal Azencot
    image_path: assets/images/gal_a.jpg
    position: Co-founder
    soundcloud: galaznct
    twitter_username:
    google_plus_link: https://plus.google.com/+GalAzencot
    instagram_username:
    site_link: https://dng.io/
  - name: Nicholas Byron
    image_path: assets/images/nick_b.jpg
    position: Co-founder
    soundcloud: nbyronn
    twitter_username:
    google_plus_link:
    instagram_username: byrons_life
    site_link:
  - name: Mauricio Medina
    image_path: assets/images/mauricio_m.jpg
    position: Co-founder
    soundcloud: mauricemedina-1
    twitter_username:
    google_plus_link:
    instagram_username:
    site_link:
  - name: Sebastian Medina
    image_path: assets/images/seb_m.jpg
    position: Contributor
    soundcloud: sebastian-medina-33
    twitter_username: sebocuban09
    google_plus_link:
    instagram_username:
    site_link:  
---
That Never Fading Smile is a collaboration between some of Lev’s closest friends. We are music lovers inspired by songs, riffs and lyrics of various genres from all around the world. Each contributor brings their own unique influence to the mix, See below for more information on each of us

<section class="alternate">
		{% for team_member in page.team %}
		<div class="tprofile">
			<img src="{{team_member.image_path}}" width="200" height="200" alt="{{team_member.name}}">
			<h3>{{team_member.name}}</h3>
			<p>{{team_member.position}}</p>
      <p id="icons">
        {% if team_member.soundcloud %}<a href="https://soundcloud.com/{{team_member.soundcloud}}" target="_new"><i class="fa fa-soundcloud"></i></a>{% endif %}
        {% if team_member.instagram_username %}<a href="https://instagram.com/{{ team_member.instagram_username }}" target="_new"><i class="fa fa-instagram"></i></a>{% endif %}
        {% if team_member.twitter_username %}<a href="https://www.twitter.com/{{ team_member.twitter_username }}" target="_new"><i class="fa fa-twitter"></i></a>{% endif %}
        {% if team_member.google_plus_link %}<a href="{{ team_member.google_plus_link }}" target="_new"><i class="fa fa-google-plus"></i></a>{% endif %}
        {% if team_member.site_link %}<a href="{{ team_member.site_link }}" target="_new"><i class="fa fa-link"></i></a>{% endif %}
      </p>
		</div>
		{% endfor %}
</section>
