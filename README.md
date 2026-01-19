# water_meter
OCR de fotografias de contadores de água.  
## Procedimento:  
1. Fotografar o mostrador do contador de água;
2. Guardar as fotografias numa pasta \consumos;
3. Correr (Windows) o script Python meter.py;
4. O script cria dois ficheiros: um *.csv e um *.json

Exemplo de uma imagem:  
![Uma das fotografias da coleção jpg FALHA](./images/20250918_145357.jpg)  
![Uma das fotografias da coleção png OK](./images/20250918_145357_612x816.png)  
<p>Uma das fotografias da coleção png OK</p>

<picture>
  <img alt="Exemplo de uma foto NÃO É do mostrador" src="images/20250918_145357.jpg" width="188" height="263">
  <p>"Exemplo de uma foto NÃO É do mostrador"</p>
</picture>
  
<picture>
  <img alt="Aqui uma PNG com  width=188 height=263" src="images/OpenCV_Python.png" width="188" height="263">
  <p>"Aqui uma PNG com  width=188 height=263"</p>
</picture>

  <picture>
  <img alt="Uma PNG sem width, height" src="images/20250918_145357.png">
    <p>"Uma PNG sem width, height"</p>
</picture>
  
<picture>
  <img alt="Uma PNG 612x816." src="images/20250918_145357_612x816.png" width="188" height="263">
<p>"Uma PNG 612x816."</p>
</picture>

<picture>
  <source srcset="/path/to/image.webp" type="image/webp">
  <img src="/images/20250917_102601.webp" alt="">
  <p>"aqui uma webp com type"</p>
</picture>


