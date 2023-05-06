Download Link: https://assignmentchef.com/product/solved-eece5639-computer-vision-i-homework-4-homographies
<br>
<ol>

 <li>(Old exam problem) The planar facade of a building is captured in an image taken by a camera. Assume this pane corresponds to the world coordinate frame’s <em>Z </em>= 0 plane, and scene point (<em>X,Y </em>) on the building projects to image pixel coordinates (<em>u,v</em>).

  <ul>

   <li>What is the planar projective transformation that describes the relationship between (<em>X,Y </em>) and (<em>u,v</em>)? Give your answer using homogeneous coordinates.</li>

   <li>How many degrees of freedom does this transformation have?</li>

   <li>How many point correspondences are required to determine this transformation?</li>

   <li>Would having more correspondences that your answer above be helpful in any way? If no, brieflyexplain why not. If yes, explain how they could be used.</li>

   <li>Give one invariant of a planar projective transformation.</li>

   <li>Give one invariant of a planar affine transformation that is not an invariant for a planar projectivetransformation.</li>

   <li>If the building has sets of lines on it running parallel to both the <em>X </em>and <em>Y </em>axes, how could we use the corresponding lines in the image to determine if the building plane is parallel to the image plane?</li>

  </ul></li>

 <li>A template g is matched against an image f, both shown below:</li>

</ol>

<table width="186">

 <tbody>

  <tr>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">2</td>

   <td width="23">4</td>

   <td width="23">2</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">2</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">2</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">2</td>

   <td width="23">0</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">2</td>

   <td width="23">0</td>

  </tr>

  <tr>

   <td width="23">1</td>

   <td width="23">2</td>

   <td width="23">1</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">2</td>

   <td width="23">4</td>

   <td width="23">2</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">1</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">1</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

   <td width="23">0</td>

  </tr>

 </tbody>

</table>

<table width="70">

 <tbody>

  <tr>

   <td width="23">1</td>

   <td width="23">2</td>

   <td width="23">1</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">1</td>

   <td width="23">0</td>

  </tr>

  <tr>

   <td width="23">0</td>

   <td width="23">1</td>

   <td width="23">0</td>

  </tr>

 </tbody>

</table>

f =g=

<ul>

 <li>Find the SSD between f and g .</li>

 <li>Find the Correlation between f and g .</li>

 <li>Find the Normalized Correlation between f and g</li>

</ul>

1