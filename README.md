# Interactive Web Map with Python & Folium

Project #3 in the "Overly-Documented College Projects" series! (Yes, there's a PDF for this one too)

🎯 What does this do?
This Python script creates an interactive web map that shows:

Volcano locations in the US (with elevation data)

World population by country (color-coded so you can see which countries are packed)

All in one beautiful, zoomable, clickable map that opens in your browser!

🧠 What I learned building this
This was my "I can make maps with code?!" moment. I figured out:

Folium - Python library that builds on Leaflet.js to create interactive maps

GeoJSON - Working with actual geographical data files

Layering - Stacking different data types on the same map

Color mapping - Making population data visual with green → orange → red

More Pandas - Because data is everywhere

🗺️ Map Features
Two cool layers:
Volcanoes Layer (Circle markers)

Each volcano gets a colored circle based on elevation

Click any volcano to see exactly how high it is

Grey outline with colored fill (fancy, right?)

Population Layer (Country polygons)

Green - Countries with < 10 million people

Orange - Countries with 10-20 million people

Red - Countries with > 20 million people

Zoom in/out to explore any region

🚀 How to use
bash
# Install the magic ingredients
pip install pandas folium

# Run the map generator
python web_map.py

# An HTML file will pop up - open it in your browser and explore!
📂 Files you'll need
web_map.py - The main script

world.json - Population data for every country

Volcano data (loaded from somewhere in the code - honestly don't remember where I got it from 😅)

📸 The Snapshot
The PDF mentions a "Snapshot" - probably me being proud that the map actually rendered without errors! Those were the days...

💭 College Kid Thoughts
This project blew my mind because:

I could see MY CODE making REAL MAPS

The maps were INTERACTIVE (zoom? click? what sorcery is this?)

I felt like I was building something Google Maps-adjacent

Was it actually that impressive? Not really. Did I feel like a genius? ABSOLUTELY.
