---
description: Esta referência fornece mais informações sobre os testes que o Adobe Experience Platform Auditor realiza para garantir a consistência de tags.
seo-description: This reference provides more information about the tests Adobe Experience Platform Auditor performs for tag consistency.
seo-title: Tag consistency
title: Consistência de tags
uuid: 16271dd6-3587-4f33-92f8-54ec4a3d6469
exl-id: 681cf2f8-e022-4fb0-a06a-b4986710f501
source-git-commit: 286a857b2ff08345499edca2e0eb6b35ecf02332
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 100%

---

# Consistência de tags

Esta referência fornece mais informações sobre os testes que o Adobe Experience Platform Auditor realiza para garantir a consistência de tags.

Os testes de consistência do Platform Auditor procuram inconsistências em todas as páginas digitalizadas. Esses são valores ou configurações que devem ser os mesmos em todas as páginas do site para garantir uma coleta de dados precisa.

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
    <!--
      1.0.1 
    --> <p><b>Analytics - Versão de código consistente </b> </p> <p>Peso: 5 </p> <p><a href="https://docs.adobe.com/content/help/pt-BR/analytics/implementation/home.html" format="html" scope="external"> Informações adicionais</a> </p> </td> 
   <td colname="col2"> <p> Mais de uma versão do código do Analytics foi encontrada. </p> </td> 
   <td colname="col3"> <p>Substitua todas as instâncias do Analytics pela versão atual. </p> </td> 
  </tr> 
 </tbody> 
</table>
