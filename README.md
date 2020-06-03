<p>Cliniface is an application for interactively visualising, analysing, investigating anthropometrics, and detecting dysmorphological traits from 3D facial images. These traits are identified as Human Phenotype Ontology (HPO) terms which have disease/gene associations. By combining the HPO terms discovered by Cliniface with other phenotypic information (as well as medical/family histories etc), a clinician can more effectively arrive at a possible diagnosis.
</p>
<p>Cliniface works by fitting standard anthropometric landmarks to the 3D facial image and then taking measurements defined by the landmark positions. The measurements are compared to demographically matched statistics describing normal growth. Typically, if measurements are found to be outside of normal variation, this contributes to the flagging of an associated HPO term.
The facial landmarks are found using a template anthropometric mask (AM) which is non-rigidly deformed to map to the subject's face. The facial landmarks are transferred from the mask to the subject's face providing the anthropometric correspondence. Landmark placement can be refined manually if required. Demographic data about the subject (date of birth, sex, maternal and paternal ethnicity) must be entered in order to allow matching of growth curve statistics and automatic detection of atypical facial traits. Cliniface also includes visualisations of asymmetry and curvature, and "virtual callipers" to allow ad hoc measurements of surface and straight line distance, depth, and angles.
</p>
<p>Cliniface accepts 3D files in a variety of standard formats, and its analysis is saved into the 3DF file format which embeds metadata and analytic results as structured plain text alongside the original model data saved in Wavefront OBJ format. Measurements and other metadata can also be exported as structured data in XML and JSON formats so that users can undertake further analysis outside of Cliniface.
</p>
<p>Cliniface is free and open source and all analysis is performed locally to protect you and your patients' privacy.
If you would like to help in the ongoing development of Cliniface or want to use it as part of your research,
please contact us directly.
</p>

<h3>License</h3>
<p>Cliniface is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. Cliniface is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.<br>
See the GNU General Public License for more details.
</p>
<p>You should have received a copy of the GNU General Public License along with this program.<br>
If not, see <a href="http://www.gnu.org/licenses/" class="uri">http://www.gnu.org/licenses/</a>.
</p>

<h3>Support</h3>
<p>Cliniface's development is supported mainly through research grants and from contributions
by partner organisations. The following organisations have helped in Cliniface's development:
<ul>
<li>Angela Wright Bennet Foundation</li>
<li>Curtin University</li>
<li>FASD Research Australia Centre for Research Excellence</li>
<li>FrontierSI (formerly Cooperative Research Centre for Spatial Information)</li>
<li>Genetic Services of Western Australia</li>
<li>Genome.One</li>
<li>Linear Clinical Research</li>
<li>McCusker Charitable Foundation</li>
<li>Murdoch Children's Research Institute</li>
<li>Patches Paediatric Clinics</li>
<li>Perth Children's Hospital Foundation</li>
<li>RD-Connect</li>
<li>Roy Hill Community Foundation</li>
<li>Telethon Kids Institute, Genetic and Rare Diseases Program</li>
<li>The Western Australian Register of Developmental Anomalies</li>
<li>The Western Australian Department of Health</li>
</ul>
</p>

<p>Special thanks to the rest of the Cliniface team, past and present including:
Petra Helmholz, Paula Fievez, Lyn Schofield, Dylan Gration, Cathryn Poulton, Yarlalu Thomas,
Stefanie Kung, Tracey Tsang, and Hedwig Verhoef. Very special thanks to clinical geneticist
Gareth Baynam whose vision, passion, and humility is key to Cliniface's ongoing success.
</p>

<h3>Feedback</h3>
<p>Cliniface is an open source project and having the time and money to keep on developing it is hard.
There's no such thing as funding to fix bugs or carry out boring efficiency improvements either,
so if you'd like to show some love, leave a message and help indulge my
<a href='https://ko-fi.com/V7V11MGQH' target='_blank'>coffee habit</a> or
chuck a few bucks at my <a href="https://paypal.me/richeytastic" class="uri">PayPal</a> wallet.
</p>
<p>Feedback is very important and helps to improve Cliniface for everyone. Got an idea for a
new feature? Think you've found a bug or that Cliniface is doing something weird?
Email me directly by clicking my name at the top of this page and I'll be pleased to hear from you.
If you want to get involved in an official capacity (research or development) or would like
to fund the development of specific features in Cliniface, then great! Email me and let's work
something out.
</p>

<h3>How to cite</h3>
<p>As well as developing Cliniface, we also use it conduct research.
If you use Cliniface for research, it's important to give due citations.
Cliniface uses a custom implementation of a third-party non-rigid registration algorithm and
also comes with a copy of the anthropometric mask created by that algorithm's authors (supplied with
permission), so please cite the following works:<br>
<a href="https://doi.org/10.1038/s41598-019-42533-y" class="uri">https://doi.org/10.1038/s41598-019-42533-y</a><br>
<a href="https://doi.org/10.1371/journal.pone.0207895" class="uri">https://doi.org/10.1371/journal.pone.0207895</a>
</p>
<p>Please also ensure that you reference Cliniface itself:<br>
Palmer, R.L., Helmholz, P., Baynam, G., 2020. <em>Cliniface: Phenotypic visualisation and analysis using non-rigid registration of 3d facial images.</em> IntArchPhRS Proceedings of the ISPRS congress 2020. in press.
</p>

<h3>Third-Party Software</h3>
<p>Cliniface is free and open source software. It depends upon the innovations and efforts of the many
researchers, developers, and maintainers of the following open source software products and technologies.
We salute your benevolence.
<ul>
<li>rlib (<a href="https://github.com/richeytastic/rlib" class="uri">https://github.com/richeytastic/rlib</a>)</li>
<li>rimg (<a href="https://github.com/richeytastic/rimg" class="uri">https://github.com/richeytastic/rimg</a>)</li>
<li>r3d (<a href="https://github.com/richeytastic/r3d" class="uri">https://github.com/richeytastic/r3d</a>)</li>
<li>r3dio (<a href="https://github.com/richeytastic/r3dio" class="uri">https://github.com/richeytastic/r3dio</a>)</li>
<li>r3dvis (<a href="https://github.com/richeytastic/r3dvis" class="uri">https://github.com/richeytastic/r3dvis</a>)</li>
<li>rNonRigid (<a href="https://github.com/richeytastic/rNonRigid" class="uri">https://github.com/richeytastic/rNonRigid</a>)</li>
<li>QTools (<a href="https://github.com/richeytastic/QTools" class="uri">https://github.com/richeytastic/QTools</a>)</li>
<li>nanoflann (<a href="https://github.com/jlblancoc/nanoflann" class="uri">https://github.com/jlblancoc/nanoflann</a>)</li>
<li>IDTF to U3D converter (<a href="http://www2.iaas.msu.ru/tmp/u3d" class="uri">http://www2.iaas.msu.ru/tmp/u3d</a>)</li>
<li>Open Asset Import Library (<a href="http://assimp.sourceforge.net" class="uri">http://assimp.sourceforge.net</a>)</li>
<li>libbuild (<a href="https://github.com/richeytastic/libbuild" class="uri">https://github.com/richeytastic/libbuild</a>)</li>
<li>QuaZip (<a href="https://github.com/stachenov/quazip" class="uri">https://github.com/stachenov/quazip</a>)</li>
<li>Sol2 (<a href="https://github.com/ThePhD/sol2" class="uri">https://github.com/ThePhD/sol2</a>)</li>
<li>MiKTeX (<a href="https://miktex.org/portable" class="uri">https://miktex.org/portable</a>)</li>
<li>Eigen3 (<a href="http://eigen.tuxfamily.org" class="uri">http://eigen.tuxfamily.org</a>)</li>
<li>Boost (<a href="http://www.boost.org" class="uri">http://www.boost.org</a>)</li>
<li>OpenCV (<a href="https://opencv.org" class="uri">https://opencv.org</a>)</li>
<li>Icons8 (<a href="https://icons8.com" class="uri">https://icons8.com</a>)</li>
<li>VTK (<a href="https://www.vtk.org" class="uri">https://www.vtk.org</a>)</li>
<li>Lua (<a href="http://www.lua.org" class="uri">http://www.lua.org</a>)</li>
<li>Qt (<a href="https://www.qt.io" class="uri">https://www.qt.io</a>)</li>
</ul>
</p>
