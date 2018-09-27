# LayoutSizes
Размеры рабочих областей и переломных точек для вёрстки при определенных размерах экрана


<table>
 <thead>
    <th>#</th>
    <th>Размер экрана </th>
    <th>Устройство</th>
     <th>Рабочая область</th>
  </thead>
  <tr>
   <td>
1
   </td>
   <td>
320px - 479px
   </td>
   <td>
 <b>Mobile</b> 
   </td>
   <td>
Workarea: 100% + 10px padding
   </td>
   </tr>
     <tr>
   <td>
2
   </td>
   <td>
480px - 767px
   </td>
   <td>
Mobile M, Mobile L
   </td>
   <td>
Workarea: 100% + 10px padding
   </td>
   </tr>
     <tr>
   <td>
3
   </td>
   <td>
768px - 1023px
   </td>
   <td>
<b>Netbook, Tablet</b>
   </td>
   <td>
Workarea: 750px + 15px padding
   </td>
   </tr>
     <tr>
   <td>
4
   </td>
   <td>
1024px - 1199px
   </td>
   <td>
<b>Netbook, Tablet</b>
   </td>
   <td>
Workarea: 960px + 15px padding
   </td>
   </tr>
     <tr>
    <td>
5
   </td>
   <td>
    больше 1200px
   </td>
   <td>
    <b>Desktop</b>
   </td>
Workarea: 1170px + 15px padding
   <td>

   </td>
   </tr>
 </table>



 
 1ый и 2ой размер в основном объединяется.<br>
 3ий и 4ый размер тоже можно объеденить<br>
 Тогда получится:<br>
 
 <table>
 <thead>
    <th>#</th>
    <th>Размер экрана </th>
    <th>Устройство</th>
     <th>Рабочая область</th>
  </thead>
  <tr>
   <td>
1
   </td>
   <td>
320px - 767px
   </td>
   <td>
 <b>Mobile</b> 
   </td>
   <td>
Workarea: 100% + 10px padding
   </td>
   </tr>
     <tr>
   <td>
2
   </td>
   <td>
768px - 1199px
   </td>
   <td>
<b>Tablet</b>
   </td>
   <td>
Workarea: 750px + 15px padding
   </td>
   </tr>
     <tr>
   <td>
3
   </td>
   <td>
больше 1200px
   </td>
   <td>
<b>Desktop</b>
   </td>
   <td>
Workarea: 1170px + 15px padding
   </td>
   </tr>

 </table>
 
 
