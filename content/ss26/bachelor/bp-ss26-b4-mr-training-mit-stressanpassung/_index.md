+++


project_id = "B4"
title = "Mixed Reality Training"

# subtitle erscheint auf Übersichtsseite und Projektseite direkt unter dem Titel.
# kurzer 2. titel, der klar über den Inhalt des Projektes informiert
subtitle = "With real-time adaptive stress"

# der claim oder auch teaser erscheint auf Übersichtsseite und Projektseite nach Titel und Subtitle
claim = "Your state decides how the mission unfolds."

# Abstract - erscheint oberhalb der Sections auf der Projektseite. 
# *** KANN WEGGELASSEN WERDEN ***, hat in der früheren Gliederung mehr sinn gemacht,
# kann aber genutzt werden, um etwas vor die erste Section zu setzen.
# # # Zama de abstract = "Something goes wrong in a space station and you are sent outside to fix it."

# Properties for displaying the project in the project list
card_image = "logo_v.jpg"

# Names are optional, team size is sufficient
team = ["Tran An Brandl", "Mousa Homam", "Jasmin Bindemann", "Pauline Wölfel", "Mah Rukh Aman"]
# this can be just one or a list as with team:
supervisor = ["Alexander Kramer", "Selina Wernike"]
draft = false


# e.g. github
source_link = "https://code.fki.htw-berlin.de/cm/studierendenprojekte/bp-ss26-b4-mr-training-mit-stressanpassung.git"
# link to a demo site / where your project is available.
# it's ok if it's temporary / just for the showtime, 
# just send a pr when you take the demo site down.
demo_link = ""
# website: if you have another project website (not demo)
website_link = ""
+++


{{<image src="Model1.jpg" alt="Alt text for image">}}

{{<section title="The Mission">}}
A space station is damaged after a micrometeorite impact. Important systems stop working and communication is lost. The player is sent outside the station to find the damage and repair the systems.
{{</section>}}


{{<section title="Gameplay">}}
The player explores a damaged space station in VR and completes different repair tasks such as connecting cables, solving riddles and restoring navigation. While doing this, the player moves through a dangerous environment with limited oxygen and constant time pressure. Extra tasks can appear during the mission, so the player has to quickly decide what to focus on while everything feels unstable.
{{</section>}}
{{<image src="Riddle.jpg" alt="Alt text for image">}}

{{<section title="Adaptive Stress System">}}
The experience changes while the player is playing. A sensor called EmotiBit is used to track vital body signals and gives information about the player’s current state. Together with how the player performs in the game, the system adjusts things like puzzle difficulty, timers and environmental effects. The goal is to keep the game challenging but still playable and engaging.
{{</section>}}


{{<section title="Development & Challenges">}}
The main challenge was combining all parts of the game into one working VR experience, including movement in space, interaction and puzzle mechanics.
{{</section>}}


{{<section title="Team">}}
We are a team of five students. Each person worked on programming, design, 3D models and system integration. We had to work closely together because all parts of the project depend on each other.
{{</section>}}

{{<gallery>}}
{{<team-member image="tran.jpg" name="Tran An Brandl">}}
{{<team-member image="homam.jpg" name="Homam Mousa">}}
{{<team-member image="jasmine.jpg" name="Jasmin Bindemann">}}
{{<team-member image="pauline.jpg" name="Pauline Wölfel">}}
{{<team-member image="mahRukh.jpg" name="Mah Rukh Aman">}}
{{</gallery>}}


{{<section title="Special Thanks">}}
Thanks to Alexander Kramer and Selina Wernike for their strong support and guidance throughout the project. They helped us in every phase and provided valuable feedback that improved both the concept and implementation.
{{</section>}}