<h2>Introduction</h2>
<p>SB2021 Docking Database is a molecular docking validation dataset released by Rizzo Lab<sup>1</sup> . However, the attached mol2 ligang files may cause many errors, therefore we used Flare V7<sup>2</sup> to check and fix the ligand structures.</p>
<h2>Mateials</h2>
<ol>
  <li>ligand.tar.gz: co-crystal ligand structure in SDF format </li>
  <li>prot.tar.gz: co-crystal protein structure in PDB format. Pyflare was used to prepare the protein and the co-crystal ligand was extracted:</li>
  <pre lang="shell">
  pyflare proteinprep.py -x 121p/121p_ref.sdf ../prot/121p.pdb  >> 121p/121p_prot.pdb
  </pre>
  <li>id.lst: list of all systems</li>
</ol>
<h2>History</h2>
<ol>
  <li>2024-01-22. Remove PDB 1ITV from data set because the ligand is a sulfate anion.</li>
  <li>2024-01-21. Release ligand data set in SDF format.</li>
</ol>
<h2>Reference</h2>
<ol>
  <li>SB2021 Docking Database. Rizzo Lab. (Jan 21, 2024 accessed). <a href="https://ringo.ams.stonybrook.edu/index.php/SB2021.v1">https://ringo.ams.stonybrook.edu/index.php/SB2021.v1</a></li>
  <li>Flare V7. <a href="https://www.cresset-group.com/softare/flare">https://www.cresset-group.com/software/flare</a></li>
</ol>
