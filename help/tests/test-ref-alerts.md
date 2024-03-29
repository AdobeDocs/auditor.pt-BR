---
description: Esta referência fornece mais informações sobre os alertas que o Adobe Experience Platform Auditor exibe para testes.
seo-description: This reference provides more information about the alerts Adobe Experience Platform Auditor displays for tests.
seo-title: Alerts
title: Alertas
uuid: 8f05b3c1-2427-4691-a88f-1de98f120a02
exl-id: 9e7ade9b-6f3c-4f1f-87b1-5dbaed63ae36
source-git-commit: 286a857b2ff08345499edca2e0eb6b35ecf02332
workflow-type: tm+mt
source-wordcount: '920'
ht-degree: 100%

---

# Alertas{#alerts}

Esta referência fornece mais informações sobre os alertas que o Adobe Experience Platform Auditor exibe para testes.

Os alertas mostram problemas que você deve estar ciente, mas que não afetam sua pontuação. Essas são recomendações de práticas recomendadas que, em alguns casos, podem não se aplicar à sua implementação.

<table id="table_031432C9BB804A6F90E7FF572739E169"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Teste </th> 
   <th colname="col2" class="entry"> Critérios </th> 
   <th colname="col3" class="entry"> Recomendação </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>Advertising Cloud - Tag de conversão correta implementada</b> </p> <p>Peso: 0 </p> </td> 
   <td colname="col2"> <p>Verifique se a tag de conversão correta é usada. </p> <p> <p>Aviso:  O uso das tags de conversão TubeMogul obsoletas pode resultar em perda de dados. </p> </p> </td> 
   <td colname="col3"> <p>Atualize seus pixels de conversão para as novas tags de conversão somente de imagem da Advertising Cloud. </p> <p>Isso pode ser feito com mais facilidade com a extensão Advertising Cloud para Adobe Experience Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>Advertising Cloud - Tag JS correta usada</b> </p> <p>Peso: 0 </p> </td> 
   <td colname="col2"> <p>A Advertising Cloud deve usar as tags mais recentes do JavaScript. </p> </td> 
   <td colname="col3"> <p>Atualize seu JavaScript da Advertising Cloud para a versão mais recente. Usar as versões obsoletas do JavaScript pode resultar em perda de funcionalidade. </p> <p>Isso pode ser feito mais facilmente usando a extensão Advertising Cloud para o Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>Advertising Cloud - tag somente imagem</b> </p> <p>Peso: 0 </p> </td> 
   <td colname="col2"> <p>O formato de pixel de imagem da Advertising Cloud deve corresponder a um dos seguintes formatos recomendados: </p> <p> 
     <ul id="ul_D85BE9C8A8654DE890E1A814E3573D86"> 
      <li id="li_E2AEDD76AC7044E8AD6AE8375858D198"> <p><span class="codeph">http(s)://rtd.tubemogul.com/upi/?sid=&lt;HASH_VALUE&gt;</span> </p> </li> 
      <li id="li_1EEFA03516BF445294B5EC5DED891758"> <p><span class="codeph">http(s)://rtd-tm.everesttech.net/upi/?sid=&lt;HASH_VALUE&gt;</span> </p> </li> 
      <li id="li_F72206B142214217BDD34356D2F3D8AD"> <p><span class="codeph">http(s)://pixel.everesttech.net/px2/&lt;NUMERIC_ID&gt;?</span> </p> </li> 
     </ul> </p> </td> 
   <td colname="col3"> <p>Atualize seus pixels da Advertising Cloud para as novas tags somente de imagem da Advertising Cloud, que garantem que você esteja aproveitando toda a funcionalidade da Advertising Cloud. </p> <p>Isso pode ser feito com mais facilidade com a extensão Advertising Cloud para o Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>Advertising Cloud - Sincronização DSP de pixels de segmento ativada</b> </p> <p>Peso: 0 </p> </td> 
   <td colname="col2"> <p>Verifique se o pixel do segmento TubeMogul contém uma configuração de sincronização DSP e recomende que a configuração seja adicionada ao pixel. </p> <p>A configuração de Sincronização do DSP é determinada pelo uso de um parâmetro da string de consulta, portanto </p> <p>SE a tag estiver sendo acionada<span class="codeph"> ("https://rtd.tubemogul.com/upi/?sid=&lt;HASH_VALUE&gt;")</span> </p> <p> OU <span class="codeph"> "http(s)://rtd-tm.everesttech.net/upi/?sid=&lt;HASH_VALUE&gt;"</span> </p> <p> OU <span class="codeph"> "http(s)://pixel.everesttech.net/px2/&lt;NUMERIC_ID&gt;?"</span> </p> <p>E a tag contém o parâmetro de URL <span class="codeph"> "sid=")</span> </p> <p>EM SEGUIDA, verifique se o parâmetro de URL <span class="codeph"> "cs=0"</span> ou<span class="codeph"> "cs=1"</span> existe e, se não for recomendado, adicione <span class="codeph"> "cs=1"</span> a esses pixels para que as taxas de correspondência do público-alvo possam melhorar. </p> </td> 
   <td colname="col3"> <p> Adicione o parâmetro de URL <span class="codeph"> "cs=1"</span> aos pixels da Advertising Cloud para que a sincronização DSP possa ocorrer, o que aumenta as taxas de correspondência do público-alvo. </p> <p>Isso pode ser feito com mais facilidade com a extensão Advertising Cloud para o Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      CAce6db25bc8c443409f0fcc5ac9d622c3 
    --> <p><b>DTM - posição de retorno de chamada pageBottom</b> </p> <p>Peso: 0 </p> <p><a href="https://docs.adobe.com/content/help/pt-BR/dtm/using/client-side/t-add-header-fooder-code.html" format="html" scope="external"> Informações adicionais</a> </p> 
    <!--
      TEa9df69942f404055a64262889c8b21d3 
    --> </td> 
   <td colname="col2"> <p>O Dynamic Tag Management exige a função <span class="codeph">_satellite.pageBottom()</span>. Adicione o script em linha imediatamente antes da tag de fechamento <span class="codeph"> &lt;/body&gt;</span> para garantir a funcionalidade adequada do DTM. </p> <p> <p>Observação: É prática recomendada que a tag seja a <i>última</i> tag no <span class="codeph"> &lt;body&gt;</span>. Se for encontrada dentro da tag <span class="codeph"> &lt;body&gt;</span>, ela tem uma chance de funcionar, mas como não é a prática recomendada, ela pode funcionar incorretamente ou com resultados inesperados ou indesejados. </p> </p> </td> 
   <td colname="col3"> <p>Adicione o script em linha imediatamente antes da tag de fechamento <span class="codeph"> &lt;/body&gt;</span> para garantir a funcionalidade adequada do DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>DTM - Auto-hospedado</b> </p> <p>Peso: 0 </p> <p><a href="https://docs.adobe.com/content/help/pt-BR/dtm/using/client-side/client-side-information.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> A biblioteca do DTM está sendo hospedada na instância Akamai da Adobe em <span class="filepath"> assets.adobedtm.com</span>. </p> <p> A hospedagem própria é a abordagem recomendada para carregar o DTM, pois oferece maior controle do desempenho do site por meio do controle de cache, reduzindo as dependências de scripts de terceiros e maior controle do processo de publicação. As bibliotecas do DTM podem ser hospedadas e gerenciadas por meio de sua própria hospedagem na Web ou CDN. </p> </td> 
   <td colname="col3"> <p>Auto-hospedagem é a abordagem recomendada para carregar o DTM em uma página. Embora a hospedagem do DTM por meio do Akamai CDN funcione na maioria dos casos, a hospedagem própria melhora o desempenho da página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b> Serviço da Experience Cloud ID - Use apenas uma AdobeOrg</b> </p> <p>Peso: 0 </p> <p><a href="https://docs.adobe.com/content/help/pt-BR/id-service/using/intro/id-request.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>Em uma implementação MCID normal, uma única AdobeOrg deve ser usada. </p> </td> 
   <td colname="col3"> <p>Valide se existem várias AdobeOrg IDs para essa implementação. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.5 
    --> <p><b>Launch - posição de retorno de chamada pageBottom</b> </p> <p>Peso: 0 </p> <p><a href="https://docs.adobe.com/content/help/pt-BR/launch/using/intro/get-started/quick-start.html" format="https" scope="external"> Informações adicionais</a> </p> 
    <!--
      TE48c499b022f545c5bccc6f8bde169685 
    --> </td> 
   <td colname="col2"> <p>O Platform Launch deve ter uma função de retorno de chamada <span class="codeph">pageBottom</span> definida por último no corpo da página se implantada de forma síncrona. </p> <p> <p>Observação: É prática recomendada que a tag seja a <i>última</i> tag no <span class="codeph"> &lt;body&gt;</span>. Se for encontrada dentro da tag <span class="codeph"> &lt;body&gt;</span>, ela tem uma chance de funcionar, mas como não é a prática recomendada, ela pode funcionar incorretamente ou com resultados inesperados ou indesejados. </p> </p> </td> 
   <td colname="col3"> <p>O Platform Launch exige a função <span class="codeph"> _satellite.pageBottom()</span> para implantações síncronas. Adicione o script em linha imediatamente antes da tag de fechamento <span class="codeph"> &lt;/body&gt;</span> para garantir a funcionalidade correta do Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>Launch - Auto-Hospedado</b> </p> <p>Peso: 0 </p> <p><a href="https://docs.adobe.com/content/help/pt-BR/launch/using/intro/get-started/quick-start.html" format="https" scope="external"> Introdução ao Adobe Experience Platform Launch</a> </p> <p><a href="https://docs.adobe.com/content/help/pt-BR/launch/using/reference/client-side-info/asynchronous-deployment.html" format="https" scope="external"> Implantação assíncrona do Platform Launch</a> </p> </td> 
   <td colname="col2"> <p>A biblioteca do Platform Launch está sendo hospedada na instância Akamai da Adobe em <span class="filepath"> assets.adobedtm.com</span>. </p> <p>A hospedagem própria é a abordagem recomendada para o carregamento do Platform Launch, pois oferece maior controle do desempenho do site por meio do controle de cache, reduzindo as dependências de scripts de terceiros e maior controle do processo de publicação. As bibliotecas do Platform Launch podem ser hospedadas e gerenciadas por meio de sua própria hospedagem na Web ou CDN. </p> </td> 
   <td colname="col3"> <p>Embora a hospedagem do Platform Launch via Akamai CDN funcione na maioria dos casos, recomenda-se que a hospedagem automática seja implementada como a primeira etapa para melhorar o desempenho da página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>Launch - deve ser implantado de forma assíncrona</b> </p> <p>Peso: 0 </p> <p><a href="https://docs.adobe.com/content/help/pt-BR/launch/using/intro/get-started/quick-start.html" format="https" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>O Platform Launch deve ser implantado de forma assíncrona para obter o desempenho ideal. </p> </td> 
   <td colname="col3"> <p>Inclua o parâmetro async no script em linha para garantir a funcionalidade assíncrona correta do Platform Launch </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b> Target - Conteúdo em mboxDefault</b> </p> <p>Peso: 0 </p> <p><a href="https://docs.adobe.com/content/help/pt-BR/target/using/implement-target/implementing-target.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> O conteúdo deve existir em mboxDefault ao usar o at.js. </p> </td> 
   <td colname="col3"> <p>Verifique se o conteúdo está disponível. </p> </td> 
  </tr> 
 </tbody> 
</table>
