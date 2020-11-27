---
layout: page
permalink: /resume
theme: yellow-candy
---

<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="assets/resume.css">

<div style="display: flex; justify-content: space-between;">
<div><h2 style="margin-top: 0">John Wigg</h2><br>Hobbyist Gamedev // Sci. Comp. Student</div>
<div><a href="mailto:john.wigg@gmx.net"><div class="contact-box"> <i class="material-icons">email</i> john.wigg@gmx.net</div></a></div>
</div>

#### Education

<div class="group" markdown='1'>
<div class="header">
<div>M.Sc. Computational and Data Science</div><div>since 2019 (FSU Jena, Germany)</div>
</div>

Planned graduation in 2021.

</div>

<div class="group" markdown='1'>
<div class="header">
<div>B.Sc. Physics</div><div>2016–2019 (FSU Jena, Germany)</div>
</div>

Bachelor thesis on the topic *The dynamics of circumstellar dust grains under consideration of the radiative forces* received best grade 1.0

Graduation with final grade 1.6 (ECTS Grade B).
</div>

<div class="group" markdown='1'>
<div class="header">
<div>School</div><div>until 2016 (Kiel, Germany)</div>
</div>

Graduation from high school with major subject physics. *DMV-Abiturpreis 2016* for outstanding performance in the high school subject mathematics.
</div>

#### Skills

<div class="center-align">
<span class="basic">Basic</span>
<span class="advanced">Advanced</span>
<span class="proficient">Proficient</span>
</div>

<div class="group">
    <div class="header">Programming Languages</div>
    
    <span class="proficient">C</span>
    <span class="proficient">Python</span>
    <span class="advanced">C++</span>
    <span class="advanced">CUDA</span>
    <span class="basic">GLSL</span>
    <span class="basic">JavaScript</span>
    <span class="basic">C#</span>
    <span class="basic">Julia</span>
    <span class="basic">R</span>
    <span class="basic">Matlab</span>
</div>

<div class="group">
    <div class="header">IDEs and Editors</div>
    
    <span class="proficient">VS Code</span>
    <span class="basic">Visual Studio</span>
    <span class="basic">Eclipse</span>
</div>
    
<div class="group">
    <div class="header">Game Engines</div>

    <span class="proficient">Godot</span>
    <span class="basic">Unity</span>
</div>

<div class="pagebreak"></div>

<div class="group">
    <div class="header">Asset Creation</div>

    <span class="proficient">Inkscape</span>
    <span class="advanced">Paint Tool SAI</span>
    <span class="basic">Blender</span>
    <span class="basic">Audacity</span>
</div>
  
<div class="group">
    <div class="header">Tools</div>

    <span class="advanced">Git</span>
    <span class="advanced">CMake</span>
    <span class="basic">Catch2</span>
</div>

<div class="group">
    <div class="header">Misc</div>

    <span class="proficient">LaTeX</span>
    <span class="advanced">HTML</span>
    <span class="advanced">CSS</span>
    <span class="basic">Sass</span>
</div>

#### Notable Student Projects

<div class="group" markdown='1'>
<div class="header">
<div>Implementing a Finite Element Method to Simulate Elastic Deformation in a Game Engine</div><div>2020</div>
</div>
Project work done for a Computational Physics university course. I implemented a Delaunay triangulator using the *Bowyer-Watson algorithm* as well as *Ruppert's algorithm* as well as a finite element method to triangulate and elastically deform arbitrary, non self-intersecting polygons in the Godot Engine. The implementation adds a new node, *ElasticBody2D*, which can be attached to the already built-in *Polygon2D* or *CollisionPolygon2D* nodes. The completed project also contains a small example game utilizing *ElasticBody2D* for its gameplay. The C++ source can be added to the Godot engine as a module or prebuilt binary downloaded from the project page.
<div class="footing">
<div>Languages: C++, GDScript</div><div>Project source: <a href="https://github.com/cp3-ws1920/elastic_body_2d">https://https://github.com/cp3-ws1920/elastic_body_2d</a></div>
</div>
</div>

<div class="group" markdown='1'>
<div class="header">
<div>Bachelor Thesis</div><div>2019</div>
</div>
Numerical simulation of the dynamics of circumstellar dust around a center starunder the influence of its radiation. Main goal of the thesis was to find out whethera notable influence of the so-called Differential Doppler Effect, a force which had not been taken into account on most previous publications, has a notable influence on dust grain trajectories. Few other newer publications on this topic where available but yielded conflicting results. The thesis backed one of those publications, whilst conflicting with another by determining that the influence was negligible for most stars.
<div class="footing">
<div>Languages: C</div>
</div>
</div>

<div class="group" markdown='1'>
<div class="header">
<div>Solving the Navier Stokes equations using finite differences</div><div>2019</div>
</div>
Project done for a lab work course. Implementation of a finite differencing method in order to solve the Navier-Stokes equations and simulation of a lid-driven cavity.
<div class="footing">
<div>Languages: C</div><div>Project source: <a href="https://github.com/CaptainProton42/NavierStokes">https://github.com/CaptainProton42/NavierStokes</a></div>
</div>
</div>

<div class="pagebreak"></div>

<div class="group" markdown='1'>
<div class="header">
<div>MNIST from scratch</div><div>2019</div>
</div>
Project work for the university course *Computational Physics III*. Programming of a neural network without using external libraries and training it using the MNIST dataset. I expanded the project by creating a Python module from the C++ source as well as collecting handwritten data from students on basic mathematical operators and implementing a calculator with handwriting recognition.
<div class="footing">
<div>Languages: C, Python</div><div>Project source: <a href="https://github.com/CaptainProton42/MNISTFromScratch">https://github.com/CaptainProton42/MNISTFromScratch</a></div>
</div>
</div>

#### Notable Personal Projects

A complete portfolio of all my personal projects is available at <a href="https://captainproton42.github.io">https://captainproton42.github.io</a>.

<div class="group" markdown='1'>
<div class="header">
<div>Godot Demos and Tutorials</div><div>since 2020</div>
</div>
After I had gotten a bit more comfortable using the Godot Engine, I started working on a series of open-source demos and tutorials made in the Godot Engine. Until now, I've done a **Bottled Liquid Shader**, **Dynamic Water** using finite differences and a fragment shader, a simple dynamic **2D Grass Shader**, a **Sky Aquarium** using dynamic water mapped to a sphere and a small tutorial on **2D Metaballs**. All of these have the source code openly available under the MIT license at my GitHub and most of these come with a detailed explanation of the implementation.
<div class="footing">
<div>Languages: GDScript</div>
<div>Project source: <a href="https://github.com/CaptainProton42">https://github.com/CaptainProton42</a></div>
</div>
</div>

<div class="group" markdown='1'>
<div class="header">
<div>Game Jam Participation</div><div>since 2020</div>
</div>
To hone my (game) programming skills, I decided to start participating in game jams. So far, I've participated in 4 different jams: *Quarantine Jam*, *Ludum Dare 46*, *Godot Wild Jam #25*, and *Ludum Dare 47* with very encouraging results. Most jam entries are open source and can be played at my itch.io page.
<div class="footing">
<div>Languages: GDScript</div>
<div>Project link: <a href="https://captainproton42.itch.io/">https://captainproton42.itch.io/</a></div>
</div>
</div>

<div class="group" markdown='1'>
<div class="header">
<div>Pocket Operators</div><div>2019–2020</div>
</div>
My most successfull and larget game project to date. Inspired by *Rainbow Six: Siege* fanart that I had mostly done until this point, I decided to create a heavily *Pokémon*-inspired in which the player could let operators (the characters in *Rainbow Six: Siege*) battle against each other. After very positive feedback (and even a retweet by the official *Rainbow Six: Siege* account) I added more operators, attacks, and a single-device versus mode. A online multiplayer version is mostly finished but on hold currently, mainly due to time contraints and hosting concerns.
<div class="footing">
<div>Languages: GDScript (Server: C++)</div>
<div>Project link: <a href="https://captainproton42.itch.io/pocket-operators">https://captainproton42.itch.io/pocket-operators</a></div>
</div>
</div>

<div class="group" markdown='1'>
<div class="header">
<div>TESSA</div><div>2019</div>
</div>
TESSA is short for *The Expanse Solar System Astrometrics* and a web application I created for GMing the *The Expanse* pen-and-paper RPG. It displays a map of the solar system based on orbital data from NASA JPL's HORIZONS system and allows the game master to plot routes between different planets and settings of *The Expanse*.
<div class="footing">
<div>Languages: JavaScript</div>
<div>Project link: <a href="https://github.com/CaptainProton42/TESSA">https://github.com/CaptainProton42/TESSA</a></div>
</div>
</div>

<div class="pagebreak"></div>

<div class="group" markdown='1'>
<div class="header">
<div>SlowMoMod (+ Flash Mode)</div><div>2015</div>
</div>
One of my earliest full programming projects and probably my first successfull one. At first, the *SlowMoMod* allowed adjustable slow motion although it saw its peak in popularity when I added the *Flash Mode* which added sped-up movement even while in slow motion. With over 60,000 downloads, I am still very proud of this project, especially since it got featured in a small video showcase by IGN once! 
<div class="footing">
<div>Languages: C++</div>
<div>Project Link: <a href="https://www.gta5-mods.com/scripts/slowmomod">https://www.gta5-mods.com/scripts/slowmomod</a></div>
</div>
</div>
