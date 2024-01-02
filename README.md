# HomeBrew HomeAssistant



## Description

A collection of my Home Brew home assistant blueprints. Blueprints are worked on in free time. If you encounter any issues please let me know if there's any issues or if you have any features you'd like to see added in the future!

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#Roadmap)



## Installation

<p>You can import my blueprints directly into your home assistant using the buttons below. </p>
<p>Updating blueprints to newer versions can be done by going to settings > automation & scenes > blueprints, then click on the 3 dots behind the blueprint and click re-import blueprint. </p>
<p>Please check the changelog to see if any changes might break existing automations. I will try to avoid it as much as possible but in some cases, I might need to make fundamental changes</p>
<br>
<h4>Ikea STYRBAR remote on-off v1.1:</h4>
<p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FxStacke%2Fhome-assistant-repo%2Fblob%2Fmain%2FBlueprints%2FIkea%2520blueprints%2FIkea%2520STYRBAR%2520on-off%2520v1.0%2520-%2520by%2520xStacke.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a></p>

<h4>Ikea STYRBAR remote toggle v1.1:</h4>
<p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FxStacke%2Fhome-assistant-repo%2Fblob%2Fmain%2FBlueprints%2FIkea%2520blueprints%2FIkea%2520STYRBAR%2520toggle%2520v1.0%2520-%2520by%2520xStacke.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a></p>

<h4>Ikea TRADFRI motion sensor v1.0:</h4>
<p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FxStacke%2Fhome-assistant-repo%2Fblob%2Fmain%2FBlueprints%2FIkea%2520blueprints%2FIkea%2520TRADFRI%2520motion%2520sensor%2520v1.0%2520-%2520by%2520xStacke.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a></p>

<h4>Ikea TRADFRI ON/OFF Switch v1.0:</h4>
<p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FxStacke%2Fhome-assistant-repo%2Fblob%2Fmain%2FBlueprints%2FIkea%2520blueprints%2FIkea%2520TRADFRI%2520ON-OFF%2520Switch%2520-%2520by%2520xStacke.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a></p>

<h4>Turn off lights when nobody is home v1.0:</h4>
<p><a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FxStacke%2Fhome-assistant-repo%2Fblob%2Fmain%2FBlueprints%2FGeneric%2520blueprints%2FTurn%2520off%2520lights%2520when%2520nobody%2520is%2520home%2520v1.0%2520-%2520by%2520xStacke.yaml" target="_blank" rel="noreferrer noopener"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a></p>

## Usage

<p><i>Ikea STYRBAR remote on-off v1.1:</i></p>
<p>The on-off STYRBAR blueprint has the dim up and down buttons as on and off respectively. Holding the dim buttons up or down will increase or decrease brightness. The left and right button has an input which can be costumized to your liking. The blueprint only supports a short press for left and right currently.</p>
<br>
<p><i>Ikea STYRBAR remote toggle v1.1:</i></p>
<p>The toggle STYRBAR blueprint has the dim up button be a toggle, turning the lights on if they are off and off if on. Holding the dim buttons up or down will increase or decrease brightness. The left and right button has an input which can be costumized to your liking. The blueprint only supports a short press for left and right currently.</p>
<br>
<p><i>Ikea TRADFRI motion sensor v1.0:</i></p>
<p>Blueprint for motion sensors, should work with other brands as well. It has been tested with the Ikea TRADFRI and Silvercrest/Lidl motion sensors. The blueprint is mostly based on the default motion sensor blueprint that should come with your home assistant installation.</p>
<p>For motion sensors, keep in mind most motion sensors have lockout timers. It seems to vary sometimes but from limited testing and some googling it seems the Ikea TRADFRI should have a 3 minute lockout window. This means if lights are turned off before this lockout window has passed it cannot detect motion and turn the lights back on until the lockout is lifted.</p>
<br>
<p><i>Ikea TRADFRI ON/OFF Switch v1.0:</i></p>
<p>TRADFRI on/off switch & dimmer blueprint. Works the same as the STYRBAR blueprint. It has an on and off button, and by holding dim up or down you can dim lights. Blueprint could work for STYRBAR remotes as well but it does not include options for the left and right button, if you want full functionality of the STYRBAR remotes use the STYRBAR blueprint.</p>
<br>
<p><i>Turn off lights when nobody is home v1.0:</i></p>
<p>Turns off lights when all phones with the home assistant app leave the home zone.</p>

## Roadmap

<p>Below is a short and to the point roadmap for planned features in no particular order</p>
 <ul>
  <li>Blueprint for door sensors (once I get mine installed on the wall/door)</li>
  <li><s>Adding inputs for the left and right buttons on the Ikea STYRBAR remotes</s></li>
  <li>Add inputs for long press left and right on the Ikea STYRBAR remotes</li>
  <li><s>Blueprint for the Ikea TRADFRI ON/OFF Switch</s></li>
  <li>Basic Dashboard template?</li>
</ul> 



