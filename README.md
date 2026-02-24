<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Super-Speed Combat Prototype | Unreal Engine</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background-color: #0b0c10;
    color: #e6e6e6;
    line-height: 1.7;
}

.container {
    max-width: 1000px;
    margin: auto;
    padding: 60px 20px;
}

a {
    color: #66c0ff;
    text-decoration: none;
}

a:hover {
    color: white;
}

.back {
    margin-bottom: 40px;
    display: inline-block;
}

.hero h1 {
    font-size: 40px;
    margin-bottom: 10px;
}

.subtitle {
    color: #9aa0a6;
    margin-bottom: 20px;
}

.video-container {
    margin-top: 30px;
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
}

.video-container iframe {
    position: absolute;
    width: 100%;
    height: 100%;
}

section {
    margin-top: 60px;
}

h2 {
    border-left: 4px solid #66c0ff;
    padding-left: 10px;
    margin-bottom: 20px;
}

ul {
    margin-left: 20px;
    margin-top: 10px;
}

.tech {
    margin-top: 20px;
}

.tech span {
    display: inline-block;
    background-color: #1f2230;
    padding: 6px 10px;
    margin: 5px 5px 0 0;
    border-radius: 4px;
    font-size: 13px;
}

.footer {
    margin-top: 100px;
    text-align: center;
    color: #777;
    font-size: 14px;
}
</style>
</head>

<body>

<div class="container">

<a class="back" href="https://mterrazi2.github.io/">← Back to Portfolio</a>

<div class="hero">
<h1>Super-Speed Combat Prototype</h1>
<div class="subtitle">
Third-Person Action Systems | Unreal Engine | C++
</div>

<p>
A third-person action prototype focused on engineering high-velocity movement,
free-flow combat logic, and a cinematic ultimate ability system. The project
explores how extreme speed mechanics can be implemented while maintaining
control precision and combat readability.
</p>

<div class="video-container">
<iframe src="YOUR_YOUTUBE_EMBED_LINK"
frameborder="0"
allowfullscreen>
</iframe>
</div>

<div class="tech">
<span>Unreal Engine</span>
<span>C++</span>
<span>Character Movement</span>
<span>Combat Systems</span>
<span>Ability Systems</span>
<span>Animation Blending</span>
</div>
</div>

<section>
<h2>Project Overview</h2>
<p>
This prototype was designed to explore advanced character mobility and
close-quarters combat responsiveness. The primary goal was to create a
system that supports extremely fast traversal while preserving player
control and environmental awareness.
</p>

<p>
The project emphasizes fluid input handling, momentum-based movement,
and scalable combat logic.
</p>
</section>

<section>
<h2>Core Gameplay Systems Implemented</h2>
<ul>
<li>Super-speed locomotion system with momentum scaling</li>
<li>Dynamic camera adjustments at high velocity</li>
<li>Free-flow combat targeting logic</li>
<li>Enemy auto-target prioritization system</li>
<li>Combo chaining framework</li>
<li>"Speed Force" ultimate ability with time-slow effects</li>
</ul>
</section>

<section>
<h2>Movement System Architecture</h2>
<p>
High-speed traversal required modifying character acceleration,
friction handling, and camera responsiveness. Special attention
was given to maintaining precision at extreme velocity.
</p>

<p>
Interpolation smoothing and directional prediction logic were
implemented to prevent disorientation during rapid movement shifts.
</p>
</section>

<section>
<h2>Combat System Design</h2>
<p>
The combat system utilizes a free-flow targeting approach,
allowing automatic enemy selection based on proximity and
player directional input.
</p>

<p>
Combo logic was structured modularly to allow future extension
into ability trees or skill progression systems.
</p>
</section>

<section>
<h2>Technical Challenges</h2>
<ul>
<li>Maintaining player control at high movement speeds</li>
<li>Ensuring camera stability during rapid traversal</li>
<li>Preventing combat targeting misalignment</li>
<li>Balancing spectacle with gameplay readability</li>
</ul>
</section>

<section>
<h2>Future Improvements</h2>
<ul>
<li>Advanced ability system integration</li>
<li>Enemy archetypes with counter mechanics</li>
<li>Environmental destruction interactions</li>
<li>Performance optimization for large-scale encounters</li>
</ul>
</section>

<div class="footer">
© 2026 Michael Terrazi
</div>

</div>

</body>
</html>
