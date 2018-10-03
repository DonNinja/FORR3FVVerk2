# FORR3FVVerk2
<ol>
  <p>
    <li>
      <p> a) GPU (Graphics Processing Unit) er notað til að reikna marga hluti í einu, oftast fyrir texture reikninga.  </p>
      <p>b) Pixel er pínkulítill punktur á skjá sem gefur frá sér ljós og þegar allir pixels á skjá eru settir saman þá sýna þeir einhverja mynd.  </p>
      <p>c.1) Frame buffer   </p>
      <p>c.2) Raster-scan skjáir uppfæra myndina eina línu í einu í kassalaga röð  </p>
      <p>c.3) Refresh rate er hversu oft á sekúndu skjár uppfærir myndina sem tölvan gefur honum, skjár getur farið undir refresh rate-ið en ekki yfir.  </p>
      <p>d.1) WebGL er javascript API sem er notað til að búa til 2D og 3D graphics í vef án plug-ins  </p>
      <p>d.2) OpenGL er almennt API sem er notað fyrir 2D og 3D vector graphics í alls konar forritum með alls konar tungumálum    </p>
      </li>
    </p>
  <p>  
  <li>
    3D objectar eru búnir til úr þríhyrningum af því að þeir þurfa alltaf að vera beinir og geta ekki verið bognir, það er ekki hægt að generatea bogna 3D objecta.
  </li>
  </p>

  <li>
    <div>
      Pipeline byrjar á því að setja upp vertex og fragment shader og gefur síðan WebGL allt data sem shaders þurfa að nota. Það data er vertex data, sem útskýrir hvernig þríhyrningarnir fyrir objectið eiga að vera teiknaðir, og bitmap data sem fragment shader notar. Eftir að það er komið þá byrjar það að rendera hvert vertice í gegnum vertex shader sem ákveður canvas stöðurnar á þríhyrningunum. Síðan ákveður fragment shader basic litinn fyrir hvern og einn pixel. Að lokum fer framebuffer yfir hvern pixel og ákveður nákvæmlega hvaða lit hver pixel fær.
      <p></p>
      <img src="http://blog.mozilla.org/hacks/files/2013/04/webgl-pipeline.png">
    </div>
  </li>
    
  <li>   
    <p>
      test
    </p>
  </li>

  <li>
    <p>
      WebGL Shaders eru gerðir úr tvemur shaders, vertex shader og fragment shaders. Vertex shader sér um að blanda öllum vertices sem þú gefur því saman til að búa til object með þeim, properties sem þú setur upp í shaderinum ákveða hvernig objectið verður þegar það kemur að sameina vertice-in. Fragment shaders sjá um að lita object og gefa því sérstakt lighting eftir þeim properties sem maður gefur því. GLSL er tungumálið sem shaders eru í.
    </p>
  </li>
  
  <li>
    <p>
      <a href="https://donninja.github.io/FORR3FVVerk2/" target="_blank">Rotating triangle (not done)</a>
    </p>
  </li>
</ol>
