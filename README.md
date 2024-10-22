# IST Rendered Point Cloud Quality Assessment Dataset
<p>
Six different voxelized PCs from MPEG repository are compressed with three different codecs in three different rates representing low, medium and high quality. Octree-based compresseion scheme in PCL, MPEG G-PCC and MPEG V-PCC point cloud codecs have been used. Rates are selected based on the coding parameters suggested in MPEG Common Test Conditions(CTC). More details can be found in the article (will be updated soon)</br>
</p>
<p>
Three different rendering solutions are used to render the decoded PCs: </br>
•	<b>RPoint session:</b> The decoded PCs have uniform color and shading with a point-based representation.</br>
•	<b>RMesh session:</b> The decoded PCs have uniform color, surface shading and a mesh-based representation.</br>
•	<b>RColor session:</b> The decoded PCs have original texture, no shading and a point-based representation.</br>
</p>
<p>
Decoded PCs were evaluated by people through a subjective test in three different sessions for each rendering methods. Table of MOS for each test session is also provided. 
</p>
<p>
<b>Update:</b> MOS of 18 people that has participated in all three sessions are added. It is <strong>recommended</strong> to use this data in file "MOS_CommonSubjects.xlsx".
</p>
<p>
<b>Originals and Normals</b>
</p>
<p>
Original point clouds and normals are uploaded. For objective metric evaluations, normals provided in Normals folder have to be used. Only in case of 12 bit data, Since V-PCC only codes 10-bit data, original point clouds are voxelized to 10-bit and also added to repository to be used for V-PCC decoded data. Normals for these point clouds are estimated using Point Cloud Library (PCL) 16 nearest neighbors as suggested in MPEG N16716.

</p>
<p>
  Please cite the following <a href = "https://ieeexplore.ieee.org/document/9257015">paper</a> if you are using this database. If you are interested in rendered videos, please send an <a href = "mailto:joao.ascenso@lx.it.pt">email</a> to us.
</p>
