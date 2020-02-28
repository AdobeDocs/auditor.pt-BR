---
description: 'null'
seo-description: 'null'
seo-title: Testar rubric 1.0.1
title: Testar rubric 1.0.1
uuid: 2ed2572e-ddb8-4899-b3a9-1329afdd7905
translation-type: tm+mt
source-git-commit: 712d0768e5e5394372293bf8231c91489519bcd1

---


# Testar rubric 1.0.1{#test-rubric}

## Testar rubric 1.0.1 {#topic-25ed23afdfaf4a12b149ff276965b043}

## Alertas {#alerts}

Esta referência fornece mais informações sobre os alertas que o Auditor exibe para testes.

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
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Advertising Cloud - Tag de conversão correta implementada</b> </p> <p>Peso: 0 </p> </td> 
   <td colname="col2"> <p>Verifique se a tag de conversão correta é usada. </p> <p> <p>Aviso:  O uso das tags de conversão TubeMogul obsoletas pode resultar em perda de dados. </p> </p> </td> 
   <td colname="col3"> <p>Atualize seus pixels de conversão para as novas tags de conversão somente de imagem da Advertising Cloud. </p> <p>Isso pode ser feito com mais facilidade com a Extensão de lançamento da Advertising Cloud. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Advertising Cloud - Etiqueta JS correta usada</b> </p> <p>Peso: 0 </p> </td> 
   <td colname="col2"> <p>A Advertising Cloud deve usar as tags mais recentes do JavaScript. </p> </td> 
   <td colname="col3"> <p>Atualize seu JavaScript da Advertising Cloud para a versão mais recente. Usar as versões obsoletas do JavaScript pode resultar em perda de funcionalidade. </p> <p>Isso pode ser feito mais facilmente usando a Extensão de lançamento da Advertising Cloud. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Advertising Cloud - tag somente imagem</b> </p> <p>Peso: 0 </p> </td> 
   <td colname="col2"> <p>O formato de pixel de imagem da Advertising Cloud deve corresponder a um dos seguintes formatos recomendados: </p> <p> 
     <ul id="ul_D85BE9C8A8654DE890E1A814E3573D86"> 
      <li id="li_E2AEDD76AC7044E8AD6AE8375858D198"> <p><span class="codeph"> http(s)://rtd.tubemogul.com/upi/?sid=&lt;HASH_VALUE&gt;</span> </p> </li> 
      <li id="li_1EEFA03516BF445294B5EC5DED891758"> <p><span class="codeph"> http(s)://rtd-tm.everesttech.net/upi/?sid=&lt;HASH_VALUE&gt;</span> </p> </li> 
      <li id="li_F72206B142214217BDD34356D2F3D8AD"> <p><span class="codeph"> http(s)://pixel.everesttech.net/px2/&lt;NUMERIC_ID&gt;?</span> </p> </li> 
     </ul> </p> </td> 
   <td colname="col3"> <p>Atualize seus pixels da Advertising Cloud para as novas tags somente de imagem da Advertising Cloud, que garantem que você esteja aproveitando toda a funcionalidade da Advertising Cloud. </p> <p>Isso pode ser feito com mais facilidade com a Extensão de lançamento da Advertising Cloud. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Advertising Cloud - Sincronização DSP de pixels de segmento ativada</b> </p> <p>Peso: 0 </p> </td> 
   <td colname="col2"> <p>Verifique se o pixel do segmento TubeMogul contém uma configuração de sincronização DSP e recomende que a configuração seja adicionada ao pixel. </p> <p>A configuração de Sincronização do DSP é determinada pelo uso de um parâmetro da string de consulta, portanto </p> <p>SE a tag estiver sendo acionada<span class="codeph"> ("https://rtd.tubemogul.com/upi/?sid=&lt;HASH_VALUE&gt;")</span> </p> <p> OU <span class="codeph"> "http(s)://rtd-tm.everesttech.net/upi/?sid=&lt;HASH_VALUE&gt;"</span> </p> <p> OU <span class="codeph"> "http(s)://pixel.everesttech.net/px2/&lt;NUMERIC_ID&gt;?"</span> </p> <p>E a tag contém o parâmetro de URL <span class="codeph"> "sid=")</span> </p> <p>EM SEGUIDA, verifique se o parâmetro de URL <span class="codeph"> "cs=0"</span> ou<span class="codeph"> "cs=1"</span> existe e, se não for recomendado, adicione <span class="codeph"> "cs=1"</span> a esses pixels para que as taxas de correspondência do público-alvo possam melhorar. </p> </td> 
   <td colname="col3"> <p> Adicione o parâmetro de URL <span class="codeph"> "cs=1"</span> aos pixels da Advertising Cloud para que a sincronização DSP possa ocorrer, o que aumenta as taxas de correspondência do público-alvo. </p> <p>Isso pode ser feito com mais facilidade com a Extensão de lançamento da Advertising Cloud. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>DTM - posição de retorno de chamada pageBottom</b> </p> <p>Peso: 0 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/t_add_header_fooder_code.html" format="html" scope="external"> Informações adicionais</a> </p> 
    <draft-comment>
      TEa9df69942f404055a64262889c8b21d3 
    </draft-comment> </td> 
   <td colname="col2"> <p>O Gerenciamento dinâmico de tags exige a função <span class="codeph"> _satellite.pageBottom()</span> . Adicione o script em linha imediatamente antes da tag body de fechamento para garantir a funcionalidade adequada do DTM. </p> <p> <p>Observação: É prática recomendada que a tag seja a <i>última</i> tag no <span class="codeph"> &lt;body&gt;</span>. Se for encontrada dentro da tag <span class="codeph"> &lt;body&gt;</span> , ela tem uma chance de funcionar, mas como não é a prática recomendada, ela pode funcionar incorretamente ou com resultados inesperados ou indesejados. </p> </p> </td> 
   <td colname="col3"> <p>Adicione o script em linha imediatamente antes da tag de fechamento <span class="codeph"> &lt;/body&gt;</span> para garantir a funcionalidade adequada do DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>DTM - Auto-hospedado</b> </p> <p>Peso: 0 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> A biblioteca do DTM está sendo hospedada na instância Akamai da Adobe em <span class="filepath"> assets.adobedtm.com</span>. </p> <p> A hospedagem própria é a abordagem recomendada para carregar o DTM, pois oferece maior controle do desempenho do site por meio do controle de cache, reduzindo as dependências de scripts de terceiros e maior controle do processo de publicação. As bibliotecas do DTM podem ser hospedadas e gerenciadas por meio de sua própria hospedagem na Web ou CDN. </p> </td> 
   <td colname="col3"> <p>Auto-hospedagem é a abordagem recomendada para carregar o DTM em uma página. Embora a hospedagem do DTM por meio do Akamai CDN funcione na maioria dos casos, a hospedagem própria melhora o desempenho da página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b> Serviço da Experience Cloud ID - Use apenas uma AdobeOrg</b> </p> <p>Peso: 0 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/mcvid_id_request.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>Em uma implementação MCID normal, uma única AdobeOrg deve ser usada. </p> </td> 
   <td colname="col3"> <p>Valide se existem várias AdobeOrg IDs para essa implementação. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Iniciar - posição de retorno de chamada pageBottom</b> </p> <p>Peso: 0 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/experience-cloud/launch/t_quick-start.html" format="html" scope="external"> Informações adicionais</a> </p> 
    <draft-comment>
      TE48c499b022f545c5bccc6f8bde169685 
    </draft-comment> </td> 
   <td colname="col2"> <p>A inicialização deve ter uma função de <span class="codeph"> retorno de chamada </span>pageBottom definida por último no corpo da página se implantada sincronicamente </p> <p> <p>Observação: É prática recomendada que a tag seja a <i>última</i> tag no <span class="codeph"> &lt;body&gt;</span>. Se for encontrada dentro da tag <span class="codeph"> &lt;body&gt;</span> , ela tem uma chance de funcionar, mas como não é a prática recomendada, ela pode funcionar incorretamente ou com resultados inesperados ou indesejados. </p> </p> </td> 
   <td colname="col3"> <p>Adicione o script em linha imediatamente antes da tag de fechamento <span class="codeph"> &lt;/body&gt;</span> para garantir a funcionalidade adequada do DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Iniciar - AutoHospedado</b> </p> <p>Peso: 0 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/experience-cloud/launch/t_quick-start.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>A biblioteca de inicialização está sendo hospedada na instância Akamai da Adobe em <span class="filepath"> assets.adobedtm.com</span>. </p> <p>A hospedagem própria é a abordagem recomendada para o carregamento do Launch, pois oferece maior controle do desempenho do site por meio do controle de cache, reduzindo as dependências de scripts de terceiros e maior controle do processo de publicação. As bibliotecas de inicialização podem ser hospedadas e gerenciadas por meio de sua própria hospedagem na Web ou CDN. </p> </td> 
   <td colname="col3"> <p>Embora a hospedagem de lançamento via Akamai CDN funcione na maioria dos casos, recomenda-se que a hospedagem automática seja implementada como a primeira etapa para melhorar o desempenho da página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Iniciar - deve ser implantado de forma assíncrona</b> </p> <p>Peso: 0 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/experience-cloud/launch/t_quick-start.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>O lançamento deve ser implantado de forma assíncrona para obter o desempenho ideal. </p> </td> 
   <td colname="col3"> <p>Inclua o parâmetro async no script em linha para garantir a funcionalidade assíncrona Launch adequada </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b> Target - Conteúdo em mboxDefault</b> </p> <p>Peso: 0 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/target/ov2/r_target-atjs-mboxcreate.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> O conteúdo deve existir em mboxDefault ao usar o at.js. </p> </td> 
   <td colname="col3"> <p>Verifique se o conteúdo está disponível. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Configuração {#configuration}

Esta referência fornece mais informações sobre os testes que o Auditor realiza para configuração.

Os testes de configuração verificam configurações, valores ou possíveis conflitos na implementação. O auditor avalia as tags em relação a outras regras e práticas recomendadas.

<table id="table_A8A1FC360482447185C8460A18426638"> 
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
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Advertising Cloud - Os nomes de conversão usam somente caracteres alfanuméricos</b> </p> <p>Peso: 3 </p> </td> 
   <td colname="col2"> <p>O parâmetro <span class="codeph"> ev_conversion_property_name</span> deve conter apenas valores numéricos e decimais, EXCETO para o parâmetro "<span class="codeph"> ev_transid</span>" (o valor <span class="codeph"> ev_transid</span> pode conter valores de texto ou numéricos) </p> <p>Procure por pixels <span class="codeph"> everesttech.net</span> que contenham um parâmetro de URL que comece com <span class="codeph"> ev_</span>. </p> <p>Exemplo: </p> <p><span class="codeph"> http://pixel.everesttech.net/1180/t?ev_page_load=1&amp;ev_revenue=$12&amp;ev_transid=1hf74i47 </span> </p> </td> 
   <td colname="col3"> <p> Certifique-se de que seus parâmetros de propriedade de transação contenham apenas valores numéricos e decimais. </p> <p> <p>Aviso:  Qualquer outro tipo de valor pode causar perda de dados. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Advertising Cloud - Os nomes de conversão usam caracteres com segurança de URL</b> </p> <p>Peso: 3 </p> </td> 
   <td colname="col2"> <p> Os nomes de propriedades de conversão não devem conter um E comercial ou um ponto de interrogação. </p> <p> Exemplo: </p> <p><span class="codeph"> http://pixel.everesttech.net/1180/t?ev_revenue&amp;order=12&amp;ev_transid=</span> </p> </td> 
   <td colname="col3"> <p>Verifique se os parâmetros de propriedade de transação não contêm um E comercial não codificado ou um ponto de interrogação. Elas quebram o formato do URL. </p> <p> <p>Aviso: Parâmetros de propriedade que contêm um E comercial não codificado ou um ponto de interrogação (por exemplo: <span class="codeph"> ev_formComplete?=1</span> ou <span class="codeph"> ev_formComplete&amp;Submit=1</span>), pode resultar em perda de dados. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Advertising Cloud - ID de transação implementada corretamente</b> </p> <p>Peso: 1 </p> </td> 
   <td colname="col2"> <p> O nome da propriedade <span class="codeph"> ev_transid=</span> não deve estar vazio. </p> <p>Exemplo: </p> <p> <span class="codeph"> http://pixel.everesttech.net/1180/t?ev_page_load=1&amp;ev_revenue= 12&amp; ev_transid=</span> </p> </td> 
   <td colname="col3"> <p>O nome da propriedade <span class="codeph"> ev_transid=</span> não deve ser deixado sem um valor (<span class="codeph"> ev_transid=</span>). Se isso for deixado sem um valor, pode haver perda de dados de transação. Atribua um valor a <span class="codeph"> ev_transid=</span> ou remova o parâmetro do pixel. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Analytics - Instanciado no DOM</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/impl_testing.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> O código do Adobe Analytics não está instalado ou não está sendo executado. Retorna 0 quando nenhum código de análise for encontrado na página da Web. </p> </td> 
   <td colname="col3"> <p>Verifique se a tag do Analytics está implementada na página e se não está bloqueada por atividades de script subsequentes. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Analytics - Instanciado uma vez</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/" format="https" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> O código do Adobe Analytics foi detectado mais de uma vez na página. . Retorna 0 quando nenhum código de análise for encontrado na página da Web. </p> </td> 
   <td colname="col3"> <p>Verifique se há apenas uma tag do Analytics na página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Analytics - Versão mais recente</b> </p> <p>Peso: 3 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/appmeasurement/release" format="https" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> Suas páginas não estão executando a versão mais recente da biblioteca de códigos do Analytics. As bibliotecas de código que alimentam as tecnologias da Experience Cloud estão sendo constantemente atualizadas e aprimoradas para aproveitar as melhorias de desempenho e fornecer os recursos mais recentes. Retorna 0 quando nenhum código de análise for encontrado na página da Web. </p> </td> 
   <td colname="col3"> <p>Instale a versão mais recente da biblioteca do Analytics. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>DTM - tags de terceiros são carregadas de forma assíncrona após DOM pronto</b> </p> <p>Peso: 3 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/load_order.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>Para obter um equilíbrio entre uma boa experiência do usuário e a coleta de dados precisos, as tags de terceiros devem ser acionadas no DOM pronto. Isso garantirá que esses scripts de rastreamento sejam executados sem afetar a funcionalidade do site. </p> </td> 
   <td colname="col3"> <p>Resolva esse problema ajustando todas as regras que executam pixels de terceiros para serem acionados no DOM Ready. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Serviço da Experience Cloud ID - Versão mais recente</b> </p> <p>Peso: 2 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/macid.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> Suas páginas não estão executando a versão mais recente da biblioteca de códigos do Serviço de ID de visitante, <span class="codeph"> visitorAPI.js</span>. As bibliotecas de código que alimentam as tecnologias da Experience Cloud estão sendo constantemente atualizadas e aprimoradas para aproveitar as melhorias de desempenho e fornecer os recursos mais recentes. </p> </td> 
   <td colname="col3"> <p>Instale a versão mais recente da biblioteca do serviço de ID de visitante. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Iniciar - Versão mais recente</b> </p> <p>Peso: 2 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/experience-cloud/launch/t_quick-start.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>Essas páginas não estão executando a versão mais recente da biblioteca de códigos do Launch (Turbine). As bibliotecas de código que alimentam as tecnologias da Experience Cloud estão sendo constantemente atualizadas e aprimoradas para aproveitar as melhorias de desempenho e fornecer os recursos mais recentes. </p> </td> 
   <td colname="col3"> <p> Atualize a biblioteca do Launch recriando e publicando a biblioteca do Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Target - Versão mais recente</b> </p> <p>Peso: 2 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/target/dtm/update-target-tool.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> Suas páginas não estão executando a versão mais recente da biblioteca de códigos do Target. As bibliotecas de código que alimentam as tecnologias da Experience Cloud estão sendo constantemente atualizadas e aprimoradas para aproveitar as melhorias de desempenho e fornecer os recursos mais recentes. </p> </td> 
   <td colname="col3"> <p>Instale a versão mais recente da biblioteca do Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Target - mboxDefault precede mboxCreate </b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/target/ov2/r_target-atjs-mboxcreate.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>O uso correto de <span class="codeph"> mboxCreate</span> é semelhante a: </p> <p> <span class="codeph"> &lt;div class="mboxDefault"&gt;&lt;!-Conteúdo do cliente—&gt;&lt;/div&gt;&lt;script&gt;mboxCreate('myMboxName')&lt;/script&gt;</span> </p> </td> 
   <td colname="col3"> <p>Certifique-se de incluir uma tag <span class="codeph"> &lt;div class="mboxDefault"&gt;&lt;/div&gt;</span> antes de chamar <span class="codeph"> mboxCreate()</span>. O at.js não adicionará um para você. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Target - DOCTYPE válido</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/target/ov2/r_target-atjs-mboxcreate.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> Um DOCTYPE inválido foi detectado. Nenhuma mbox será acionada neste cenário. </p> <p>Para at.js, DOCTYPE deve estar no modo Padrões ou o Target não funcionará. </p> </td> 
   <td colname="col3"> <p>Atualize o DOCTYPE na página. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Consistência de tags {#tag-consistency}

Esta referência fornece mais informações sobre os testes executados pelo auditor para garantir a consistência das tags.

Os testes de consistência do auditor procuram inconsistências em todas as páginas digitalizadas. Esses são valores ou configurações que devem ser os mesmos em todas as páginas do site para garantir uma coleta de dados precisa.

<table id="table_4F9ED873BAF741D19BFB0F297B3A1FDB"> 
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
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Analytics - Versão de código consistente </b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/choose-implementation-method.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> Mais de uma versão do código do Analytics foi encontrada. </p> </td> 
   <td colname="col3"> <p>Substitua todas as instâncias do Analytics pela versão atual. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Presença de tag {#tag-presence}

Esta referência fornece mais informações sobre os testes que o Auditor realiza para a presença de tags.

O Auditor avalia se a tag existe e se está no lugar certo no código da sua página.

<table id="table_98A2E3F7B3154EEFA76D0CAE2FE97CAB"> 
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
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Advertising Cloud - Presença de código</b> </p> <p>Peso: 5 </p> </td> 
   <td colname="col2"> <p> A tag da Advertising Cloud não está disponível no DOM. </p> </td> 
   <td colname="col3"> <p>Implemente a tag da Advertising Cloud usando a Extensão de lançamento da Advertising Cloud. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Advertising Cloud - Pixel de segmento implementado</b> </p> <p>Peso: 5 </p> </td> 
   <td colname="col2"> <p> Atualize seus pixels de segmento da Advertising Cloud para as novas tags somente de imagem da Advertising Cloud. O uso de tags de segmento AMO obsoletas pode resultar em perda de dados. </p> </td> 
   <td colname="col3"> <p>Implemente o pixel do segmento da Advertising Cloud usando a Extensão de lançamento da Advertising Cloud. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Analytics - Carregado no DOM</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/" format="https" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> A tag do Adobe Analytics não foi detectada. </p> </td> 
   <td colname="col3"> <p>Instale a versão mais recente do Analytics. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b> DTM - Biblioteca carregada</b> </p> <p>Peso: 5 </p> <p>Informações adicionais: </p> <p> 
     <ul id="ul_7E706EBC2E4649A69732E6982E116E22"> 
      <li id="li_9AF0257E39C347A9AE6D8D8FFBD66B38"><a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/c_Troubleshooting.html" format="html" scope="external"> Solução de problemas do DTM</a> </li> 
      <li id="li_7B422BCCD2654B0A9059799FB5276BE8"><a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/t_add_header_fooder_code.html" format="html" scope="external"> Adicionar o código do cabeçalho e do rodapé</a> </li> 
     </ul> </p> </td> 
   <td colname="col2"> <p> Um objeto _satellite global não foi encontrado no DOM. O Gerenciamento dinâmico de tags não está instalado ou não está sendo executado. </p> </td> 
   <td colname="col3"> <p>Verifique se a biblioteca do DTM está implementada na página e se não está bloqueada por atividades de script subsequentes. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b> DTM - Um código incorporado</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/code.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> Os sites de produção devem carregar apenas uma biblioteca do DTM. </p> </td> 
   <td colname="col3"> <p>Verifique se apenas a biblioteca de produção está sendo carregada na página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>DTM - o retorno de chamada pageBottom existe em &lt;body&gt;</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/t_add_header_fooder_code.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> O retorno de chamada <span class="codeph"> _satellite.pageBottom()</span> não foi encontrado dentro do <span class="codeph"> &lt;body&gt;</span> da página, que é exigido pelo Gerenciamento dinâmico de tags. </p> <p>Esse teste falhará se a <span class="codeph"> chamada </span>pageBottom não for encontrada na página, ou se estiver na tag <span class="codeph"> &lt;head&gt;</span> (ou em algum outro local inesperado). Ele só passará se <span class="codeph"> pageBottom</span> for encontrado em algum lugar dentro da tag <span class="codeph"> &lt;body&gt;</span> . Se não estiver na página, não funcionará e os outros dois testes <span class="codeph"> pageBottom</span> também falharão. </p> </td> 
   <td colname="col3"> <p>Adicione o script em linha imediatamente antes da tag de fechamento <span class="codeph"> &lt;/body&gt;</span> para garantir a funcionalidade adequada do DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>DTM - tag pageBottom ativada</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/t_add_header_fooder_code.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> A tag pageBottom <span class="codeph"></span> do DTM não foi detectada. </p> <p>Isso pode ocorrer se a chamada estiver em uma declaração <span class="codeph"> if</span> que resulta em algo semelhante a <span class="codeph"> if (false) {_satellite.pageBottom()}</span>. Então, embora possa existir e estar corretamente colocada, a etiqueta ainda pode não disparar. </p> </td> 
   <td colname="col3"> <p>Instale a chamada <span class="codeph"> pageBottom</span> em cada página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Serviço da Experience Cloud ID - Presença do código</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/mcvid-overview.htmlimplementation-guides.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>O código do Serviço da Experience Cloud ID não foi encontrado. A Experience Cloud ID (MCID) é altamente recomendada para garantir que você obtenha o máximo de valor das soluções da Experience Cloud e seja essencial para o gerenciamento de ID nas soluções da Experience Cloud. </p> </td> 
   <td colname="col3"> <p> Instale a versão mais recente da MCID. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Serviço da Experience Cloud ID - Presença de cookie</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/mcvid-implementation-guides.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> O cookie <span class="codeph"> AMCV_</span> não foi encontrado. É necessário instanciar um objeto de visitante do código <span class="codeph"> VisitorAPI.js</span> . </p> </td> 
   <td colname="col3"> <p> Se esta for uma implementação do DTM, verifique se a AdobeOrg ID foi inserida corretamente na ferramenta MCID. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Serviço da Experience Cloud ID - valor da MID presente</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/mcvid_cookies.html#concept_37156268512445F287CD4BBB2839FFAA__section_C55AF54828DC4CCE89F6118655D694C8" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> O valor MID não foi encontrado no cookie <span class="codeph"> AMCV_</span> . </p> </td> 
   <td colname="col3"> <p>Teste novamente para verificar se há latência de API MCID. Se a condição persistir, entre em contato com o Atendimento ao cliente da Adobe. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b> Iniciar - Biblioteca carregada</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/experience-cloud/launch/t_quick-start.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> Um objeto _satellite global não foi encontrado no DOM. O Launch não está instalado ou não está sendo executado. </p> </td> 
   <td colname="col3"> <p>Verifique se a biblioteca de inicialização está implementada na página e não está bloqueada pelas atividades subsequentes de script. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Iniciar - Não tem vários scripts incorporados</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/experience-cloud/launch/t_quick-start.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>Não deve haver vários scripts incorporados carregados na página. Os sites de produção devem carregar apenas uma biblioteca de inicialização. </p> </td> 
   <td colname="col3"> <p>Verifique se apenas a biblioteca de produção está sendo carregada na página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Iniciar - o retorno de chamada pageBottom existe em &lt;body&gt;</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/experience-cloud/launch/t_quick-start.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> O retorno de chamada <span class="codeph"> _satellite.pageBottom()</span> não foi encontrado dentro do <span class="codeph"> &lt;body&gt;</span> da página, que é exigido pelo Launch. </p> <p>Esse teste falhará se a <span class="codeph"> chamada </span>pageBottom não for encontrada na página, ou se estiver na tag <span class="codeph"> &lt;head&gt;</span> (ou em algum outro local inesperado). Ele só passará se <span class="codeph"> pageBottom</span> for encontrado em algum lugar dentro da tag <span class="codeph"> &lt;body&gt;</span> . Se não estiver na página, não funcionará e os outros dois testes <span class="codeph"> pageBottom</span> também falharão. </p> </td> 
   <td colname="col3"> <p>Adicione o script em linha imediatamente antes da tag de fechamento <span class="codeph"> &lt;/body&gt;</span> para garantir a funcionalidade de inicialização correta. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b>Inicialização - o retorno de chamada pageBottom não deve existir quando implantado de forma assíncrona</b> </p> <p>Peso: 5 </p> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/experience-cloud/launch/t_quick-start.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>O retorno de chamada <span class="codeph"> _satellite.pageBottom()</span> foi encontrado na página, o que não deve ocorrer quando o Launch é implantado de forma assíncrona. </p> </td> 
   <td colname="col3"> <p>Remova o script<span class="codeph"> _satellite.pageBottom()</span> para ativar a funcionalidade de inicialização correta. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b> Target - Presença de código</b> </p> <p>Peso: 5 </p> <p><a href="https://docs.adobe.com/content/help/en/target/using/implement-target/implementing-target.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p>O Target deve ser definido no DOM. </p> </td> 
   <td colname="col3"> <p>Instale a versão mais recente do Target (at.js). </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 
    <draft-comment>
      1.0.1 
    </draft-comment> <p><b> Target - Biblioteca carregada em &lt;head&gt;</b> </p> <p>Peso: 4 </p> <p><a href="https://docs.adobe.com/content/help/en/target/using/implement-target/implementing-target.html" format="html" scope="external"> Informações adicionais</a> </p> 
    <draft-comment>
      TE61c380082a4b4706b28a84aa047599a7 
    </draft-comment> </td> 
   <td colname="col2"> <p> A biblioteca do Target deve ser carregada na tag <span class="codeph"> &lt;head&gt;</span> . </p> </td> 
   <td colname="col3"> <p> Verifique se a biblioteca do Target está carregada na tag <span class="codeph"> &lt;head&gt;</span> . </p> </td> 
  </tr> 
 </tbody> 
</table>
