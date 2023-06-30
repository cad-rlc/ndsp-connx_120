# Cadence NatureDSP Library for ConnX 120 DSP cores

<p>This NatureDSP Library for ConnX 120 DSP contains various optimized general purpose signal processing routines.</p>
 <h1> Version: v1.1.0 </h1>
<p> This patch release contains following changes compared to the previous release v1.0.0:</p>
  <h3> Changes:</h3>
        <p>
        <ol>
        <li>Replaced first step of Newton-Raphson based single precision floating point reciprocal
  operation & other sequence of instructions with a direct RECIP proto.</li>
        <li>Updated the code to use Quadratic Lagrange Interpolation(QLI) based single precision
  floating point reciprocal operation where ever applicable.</li>
        </ol>
        </p>
        <h3>Details:</h3>
       <p>
       <ol>
      <li>This version of library has been tested with RI-2023.11 Xtensa tools.</li>
      </ol>
      </p>
<h3> Known issues:</h3>
     <p>
     <ol>
    <li> None</li>
     </ol>
     </p>
<h1> Version: v1.0.0 </h1>
<p> 
<ol><li>This is the first version of the NatureDSP library on ConnX 120 DSP.</li>
</ol></p> 
 <h3> Details:</h3>
       <p>
       <ol>
      <li>This version of library has been optimized and tested with RI-2022.9 Xtensa tools.</li>
      </ol>
      </p>
<h3> Known issues:</h3>
     <p>
     <ol>
    <li> None</li>
     </ol>
     </p>



<h1>To use the library </h1>
<p>
<ol>
<li>Download the library & demo xws from the repository and import them into Xtensa Xplorer environment.</li>
<li>Upon importing, two directories i.e. connx120_library & connx120_demo  will be available in the Project Xplorer pane.</li>
<li>Refer to Chapter-3 of "NatureDSP_Baseband_ConnX_120_Library_Reference.pdf" document present inside the connx120_library/doc directory for details on build and run.</li>
<li>Detailed Release notes can be found at connx120_library/doc directory.</li>
</ol>
</p>

