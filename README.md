<h1 align="center">RHYTHMSHIFT</h1>
<p>RhythmShift is a console-based, portable, and single-file program that allows the conversion of Quaver song folders to <a href="https://ninja-muffin24.itch.io/funkin">Friday Night Funkin'</a> mods.<br>However, due to this program being in its infancy, it only supports <b>three</b> engines at the moment. those being:</p>
<l>
  <li><a href="https://codename-engine.com">Codename Engine</a></li>
  <li><a href="https://gamebanana.com/mods/309789">Psych Engine</a> {TBI}</li>
  <li><a href="https://ninja-muffin24.itch.io/funkin">V-Slice</a><sup>base funkin</sup> {TBI}</li>
  <li><s>Kade Engine</s><sup>not happening</sup></li>
</l>

<p>Currently, the converter supports:</p>
<l>
  <li>Converting images</li>
  <li>Converting audio*</li>
  <li>Full mod folder cretaion</li>
  <li>Chart conversion</li>
</l>
<p>* = You must have ffmpeg installed.</p>

<p>And I am currently working to implement:</p>
<l>
  <li>Support for timing points</li>
  <li>Support for scroll velocities</li>
  <li>Support for custom sound effects</li>
</l>

<h2>BUILDING</h2>
<l>
  <li>install haxe</li>
  <li><code>haxe -main Main -neko RhythmShift.n</code> (for multiplatform? idrk what neko is, but it gets installed with haxe, so idk.)</li>
  <li><code>haxe -main Main -cpp cpp/bin</code> (for Windows)</li>
  <li>run program. simple as that</li>
</l>
