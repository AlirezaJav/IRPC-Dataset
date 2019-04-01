# A Good Tiltle
<p>
In order to study the impact of rendering on perceived quality of a decoded point cloud, 6 different point clouds are decoded and encoded with 3 different codecs, namely, codec implemented in PCL, MPEG G-PCC codec and MPEG V-PCC codec. First one exploits octree pruning, the second perform trangulation coding after octree pruning and the last one is a 2D projection based metric which uses HEVC. All test materials are coded in three rates with these codecs.</br>
</p>
<p>
Three different rendering solutions are used to render the decoded PCs: </br>
•	<b>RPoint session:</b> The decoded PCs have uniform color and shading with a point-based representation.</br>
•	<b>RMesh session:</b> The decoded PCs have uniform color, surface shading and a mesh-based representation.</br>
•	<b>RColor session:</b> The decoded PCs have original texture, no shading and a point-based representation.</br>
</p>
<p>
Decoded PCs were evaluated by people through a subjective test in three different sessions for each rendering methods. More information is provided in this article (link to our paper)
</p>
<p>
In this repository all test materials and the associated MOS scores are provided for any further use. Please cite this paper (link) if you are using this data. 
</p>
