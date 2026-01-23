# Water_meter
OCR de fotografias de contadores de água.  
## Procedimento:  
1. Fotografar o mostrador do contador de água;  
   <picture>
      <source srcset="/res/20250917_102601.webp" type="image/webp">
      <img src="/res/20250917_102601.webp" alt="Foto mostrador" width="120">
   </picture>  

2. Guardar as fotografias numa pasta \consumos;  
   <picture>
    <source srcset="/res/Captura de ecrã 2026-01-20 113706.png" type="image/ong">
    <img src="/res/Captura de ecrã 2026-01-20 113706.png" alt="Fotos no folder" width="188">
  </picture>  

4. Correr (Windows) o script Python wmeter.py;
5. O script cria dois ficheiros: um *.csv e um *.json;
6.  Também gera ficheiros auxiliares log.txt e report.txt.
7.  Os ficheiros *.csv e *.json podem ser vistos como gráficos via Excel ou Python.

## Sobre as fotografias
Para este exemplo selecionei 10 fotos.  
Foram tiradas com telemóvel seguuro manualmente, em más condições de luz, e nal enquadradas.  
Idealmente deve ser usada uma câmara estável, sempre na mesma posição e com iluminação decente.  
As fotos devem ser feitas a intervalos regulares.

## Sobre o OCR
O Windows tem uma ferramenta nativa que faz um bom OCR.  
No meu caso, a ferramenta está aqui:  
```python
p1 = subprocess.Popen(
  "C:\\Program Files\\WindowsApps\\
Microsoft.ScreenSketch_11.2510.31.0_x64__8wekyb3d8bbwe\\  
SnippingTool\\SnippingTool.exe"
)
``` 
Se a localização mudar, é necessário mudar manualmente no código!  

Quando aberta, a janela da app mostra o longo título:  
"Ferramenta de recorte de fotografias" 
   <picture>
    <source srcset="/res/s_and_s_25.png" type="image/ong">
    <img src="/res/s_and_s_25.png" alt="Ferramenta de recorte" width="188">
  </picture> 
(a app "Fotos" também faz OCR mas por enquanto muito inferior)  

