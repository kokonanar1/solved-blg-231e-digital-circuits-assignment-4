Download Link: https://assignmentchef.com/product/solved-blg-231e-digital-circuits-assignment-4
<br>
<strong> </strong>







<ol>

 <li>The combinational circuit ARITHMETIC/LOGIC <strong>(A/L)</strong> performs the following operations depending on the value of the control inputs X, Y, and Z.</li>

</ol>

<table width="540">

 <tbody>

  <tr>

   <td width="284">


    <table width="232">

     <tbody>

      <tr>

       <td width="26"><strong>X </strong></td>

       <td width="26"><strong>Y </strong></td>

       <td width="25"><strong>Z </strong></td>

       <td width="88"><strong>Result (O) </strong></td>

       <td width="67"><strong>Cout </strong></td>

      </tr>

      <tr>

       <td width="26">0</td>

       <td width="26">0</td>

       <td width="25">0</td>

       <td width="88">B – A</td>

       <td width="67"> </td>

      </tr>

      <tr>

       <td width="26">0</td>

       <td width="26">0</td>

       <td width="25">1</td>

       <td width="88">A + B</td>

       <td width="67">Carry</td>

      </tr>

      <tr>

       <td width="26">0</td>

       <td width="26">1</td>

       <td width="25">0</td>

       <td width="88">A –</td>

       <td width="67">Borrow</td>

      </tr>

      <tr>

       <td width="26">0</td>

       <td width="26">1</td>

       <td width="25">1</td>

       <td width="88"> Φ</td>

       <td width="67">Φ</td>

      </tr>

      <tr>

       <td width="26">1</td>

       <td width="26">0</td>

       <td width="25">0</td>

       <td width="88">A  B</td>

       <td width="67">Φ</td>

      </tr>

      <tr>

       <td width="26">1</td>

       <td width="26">0</td>

       <td width="25">1</td>

       <td width="88">Φ</td>

       <td width="67">Φ</td>

      </tr>

      <tr>

       <td width="26">1</td>

       <td width="26">1</td>

       <td width="25">0</td>

       <td width="88"> </td>

       <td width="67">Φ</td>

      </tr>

      <tr>

       <td width="26">1</td>

       <td width="26">1</td>

       <td width="25">1</td>

       <td width="88">Φ</td>

       <td width="67">Φ</td>

      </tr>

     </tbody>

    </table></td>

   <td width="257"></td>

  </tr>

 </tbody>

</table>

The meanings of symbols are given below:

<table width="605">

 <tbody>

  <tr>

   <td width="66"><strong>Symbol </strong></td>

   <td width="539"><strong>Meaning </strong></td>

  </tr>

  <tr>

   <td width="66">+</td>

   <td width="539">Arithmetic addition</td>

  </tr>

  <tr>

   <td width="66">–</td>

   <td width="539">Arithmetic subtraction</td>

  </tr>

  <tr>

   <td width="66"> </td>

   <td width="539">4-bit logic AND between corresponding bits of A and B: A<sub>3</sub>B<sub>3</sub>, …, A<sub>0</sub>B<sub>0</sub>.</td>

  </tr>

  <tr>

   <td width="66"> </td>

   <td width="539">4-bit logic XOR between corresponding bits of A and B: A<sub>3</sub> B<sub>3</sub>, …, A<sub>0</sub> B<sub>0</sub>.</td>

  </tr>

  <tr>

   <td width="66">Φ</td>

   <td width="539">Don’t care</td>

  </tr>

 </tbody>

</table>




Page <strong>1</strong> of <strong>2</strong>




Design and draw this circuit using <strong>only </strong>the standard components and logic gates given below, <u>paying attention to the maximum number</u> allowed for the first three:

<table width="359">

 <tbody>

  <tr>

   <td width="151"><strong>Type </strong></td>

   <td width="208"><strong>Maximum number allowed </strong></td>

  </tr>

  <tr>

   <td width="151">4-bit parallel adders</td>

   <td width="208">2</td>

  </tr>

  <tr>

   <td width="151">8:1 multiplexer</td>

   <td width="208">1</td>

  </tr>

  <tr>

   <td width="151">2:4 decoder</td>

   <td width="208">1</td>

  </tr>

  <tr>

   <td width="151">XOR gates</td>

   <td width="208">No restriction</td>

  </tr>

  <tr>

   <td width="151">NOT gates</td>

   <td width="208">No restriction</td>

  </tr>

  <tr>

   <td width="151">OR gates</td>

   <td width="208">No restriction</td>

  </tr>

  <tr>

   <td width="151">AND gates</td>

   <td width="208">No restriction</td>

  </tr>

 </tbody>

</table>





