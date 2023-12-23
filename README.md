# HomeBrew HomeAssistant



## Description

A collection of my Home Brew home assistant blueprints

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)



## Installation

<p>You can import my blueprints directly into your home assistant using the buttons below. </p>
<p>Updating blueprints to newer versions can be done by going to settings > automation & scenes > blueprints, then click on the 3 dots behind the blueprint and click re-import blueprint. </p>
<p>Please check the changelog to see if any changes might break existing automations. I will try to avoid it as much as possible but in some cases, I might need to make fundamental changes</p>
<br>
<h4>Ikea STYRBAR remote on-off v1.0:</h4>
<p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FxStacke%2Fhome-assistant-repo%2Fmain%2FIkea%2520STYRBAR%2520on-off%2520v1.0%2520-%2520by%2520xStacke.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a></p>

<h4>Ikea STYRBAR remote toggle v1.0:</h4>
<p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FxStacke%2Fhome-assistant-repo%2Fmain%2FIkea%2520STYRBAR%2520toggle%2520v1.0%2520-%2520by%2520xStacke.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a></p>

<h4>Ikea TRADFRI motion sensor v1.0:</h4>
<p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FxStacke%2Fhome-assistant-repo%2Fblob%2Fmain%2FIkea%2520TRADFRI%2520motion%2520sensor%2520v1.0%2520-%2520by%2520xStacke.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a></p>

## Usage

<p><i>Ikea STYRBAR remote on-off v1.0:</i></p>
<p>The on-off STYRBAR blueprint has the dim up and down buttons as on and off respectively. Holding the dim buttons up or down will increase or decrease brightness</p>
<br>
<p><i>Ikea STYRBAR remote toggle v1.0:</i></p>
<p>The toggle STYRBAR blueprint has the dim up button be a toggle, turning the lights on if they are off and off if on. Holding the dim buttons up or down will increase or decrease brightness</p>
<br>
<p><i>Ikea TRADFRI motion sensor v1.0:</i></p>
<p>Blueprint for motion sensors, should work with other brands as well. It has been tested with the Ikea TRADFRI and Silvercrest/Lidl motion sensors. The blueprint is mostly based on the default motion sensor blueprint that should come with your home assistant installation</p>
<p>For motion sensors, keep in mind most motion sensors have lockout timers. It seems to vary sometimes but from limited testing and some googling it seems the Ikea TRADFRI should have a 3 minute lockout window. This means if lights are turned off before this lockout window has passed it cannot detect motion and turn the lights back on until the lockout is lifted </p>





