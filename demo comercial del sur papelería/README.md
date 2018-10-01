<h1>Demo de Código para Comercial del Sur Papelería </h1><br>

<p>
Los archivos contenidos en esta demo representan una muestra significativa el diferente tipo de codificación empleado en el desarrollo
de aplicaciones bajo el entorno <b>AS400 RPG</b>. 
</p>
<p>
Se ha desarrollado una aplicación CRUD para una tabla de <em>Contactos</em> así como para 2 tablas auxiliares: <em>Provincias</em> y <em>Códigos Postales</em>. 
</p>
<p>
Se ha habilitado también un <em>menú dinámico</em> en el cual es posible insertar opciones al mismo sin compilar. Tan solo modificando el contenido
de los miembros de tipo TXT.
</p>

<p>
Los miembros utilizados son los siguientes:
</p>
<table>
<tr><td><b>Miembro</b></td>     <td><b>Tipo</b></td>        <td><b>Texto</b></td>
<tr><td>CNTF01</td>      <td>PF</td>         <td> Provincias</td></tr>                                         
<tr><td>CNTF02</td>      <td>PF</td>         <td>Códigos Postales</td></tr>                                   
<tr><td>CNTF03</td>      <td>PF</td>          <td>Contactos</td></tr>   
<tr><td>CONTRO00</td>    <td>PF</td>          <td>Fichero control usuarios y programas</td></tr>               
<tr><td>CNTW01</td>      <td>DSPF</td>        <td>Mantenimiento de provincias</td></tr>                        
<tr><td>CNTW02</td>      <td>DSPF</td>        <td>Mantenimiento de códigos postales</td></tr>                  
<tr><td>CNTW03</td>      <td>DSPF</td>        <td>Mantenimiento de contactos</td></tr>                         
<tr><td>MENUWIN</td>     <td>DSPF</td>        <td>Presentación de menús</td></tr>                              
<tr><td>CNTC00</td>      <td>CLLE</td>        <td>Gestión de contactos</td></tr>                              
<tr><td>CNTC01</td>      <td>CLLE</td>        <td>Mantenimiento de provincias</td></tr>                        
<tr><td>CNTC02</td>      <td>CLLE</td>        <td>Mantenimiento de códigos postales</td></tr>                  
<tr><td>CNTC03</td>      <td>CLLE</td>        <td>Mantenimiento de contactos</td></tr>                         
<tr><td>MENUCIN</td>     <td>CLLE</td>        <td>Presentación de menús</td></tr>      
<tr><td>CNTR01</td>     <td>RPGLE</td>       <td>Mantenimiento de provincia</td></tr>                        
<tr><td>CNTR02</td>     <td>RPGLE</td>       <td>Mantenimiento de códigos postales </td></tr>                 
<tr><td>CNTR03</td>      <td>RPGLE</td>       <td>Mantenimiento de contactos</td></tr>                         
<tr><td>MANDATO</td>     <td>RPGLE</td>       <td>Para ejecutar mandatos dentro de un pgm rpg</td></tr>        
<tr><td>MENURIN</td>     <td>RPGLE</td>       <td>Presentación de menús</td></tr>                              
<tr><td>NIFCIF</td>      <td>RPGLE</td>       <td>Validar documento</td></tr>                                  
<tr><td>TECLAS</td>      <td>RPGLE</td>       <td>Control de teclas presionadas /copy</td></tr>  
<tr><td>MNDEMO00</td>    <td>TXT</td>        <td> Menú principal</td></tr>                                     
<tr><td>MNDEMO01</td>    <td>TXT</td>         <td>Menú tablas auxiliares</td></tr>                             

</table>
