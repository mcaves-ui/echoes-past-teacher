---
title: Includes Guide
nav: Includes Guide
gallery: true
---

<br>

{% include feature/nav-menu.html sections="Images;Audio;Video;PDF;Accordions for Simple Question and Answer;Alert;Button;Card;Modal;Timeline" %}

## Images

<br>

{% include gallery-figure.html img="example_banner.jpg" alt="some houses and a barn" caption="Echo!" width="100%" %}

<hr>

## Audio

<br>

{% include feature/audio.html objectid="/images/field_recording.mp3" caption="Field Recording" %}

<hr>

## Video

<br>


{% include feature/video.html objectid="https://www.youtube.com/watch?v=N72C0o78UKc" caption="My two new favorite people." %}

<hr>

## PDF

<br>

{% include feature/pdf.html objectid="/images/tribes.pdf" caption="FEDERALLY-RECOGNIZED TRIBES
 OF THE COLUMBIA-SNAKE BASIN" %}

 <hr>

## Accordions for Simple Question and Answer

<br>

{% include accordion.html title1="Where is Echo, Oregon?" text1="It's over there." title2="Hi there" text2="Hello." title3="Good-bye" text3="See ya later." %}

<hr>

## Alert

<br>

{% include feature/alert.html text="Alerts can serve as helpful callout boxes to break up text" color="warning" align="left" %}

Follows Bootstrap colors: (primary, secondary, success, danger, warning, info, light, dark)

<hr>

## Button

{% include feature/button.html text="To highlight external links
" link="https://en.wikipedia.org/wiki/Lorem_ipsum#:~:text=Its%20purpose%20is%20to%20permit,libraries%20such%20as%20Semantic%20UI." color="success" %}

<hr>

## Card

<br>

{% include feature/card.html text="but with a header hierarchy and the ability to add images" header="Similar to an alert" objectid="/images/example_banner.jpg" %}

<hr>

## Modal

<br>

{% include feature/modal.html button="More Info" color="info" title="Information" text="Example text" %}

<hr>

## Timeline

{% include feature/timelinejs.html json="/assets/data/echo_inter_image.json" %}



