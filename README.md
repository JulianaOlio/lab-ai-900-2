# lab-ai-900-2
Laboratórios AI-900

2ª Atividade: Analisar texto com o Language Studio

a - Criar um recurso de linguagem:
 - Abrir o portal do Azure em https://portal.azure.com, entrando com a conta da Microsoft associada à sua assinatura do Azure.
 - Clique no botão +Criar um recurso e pesquise Serviço de linguagem.
 - Selecione criar um plano de serviço de linguagem. Você será levado a uma página para Selecionar recursos adicionais.
 - Mantenha a seleção padrão e clique em Continuar para criar seu recurso.
 - Na página Criar idioma, configure-o com as seguintes configurações:
      Assinatura: sua assinatura do Azure.
      Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo.
      Região: Selecione a região geográfica mais próxima. Se estiver no leste dos EUA, use "Leste dos EUA 2".
      Nome: Insira um nome exclusivo.
      Tipo de preço: F0 ou S Livre se F0 Livre não estiver disponível
      Ao marcar esta caixa, reconheço que li e entendi todos os termos abaixo: Selecionado.
      Selecione Examinar + criar, Criar e aguarde a conclusão da implantação. 

b - Configurar seu recurso no Azure AI Language Studio:
 -   Em outra guia do navegador, abra o Language Studio em https://language.cognitive.azure.com e entre.
 -   Quando solicitado com Selecionar um recurso do Azure, faça as seguintes configurações:
        Diretório do Azure: Diretório padrão, o diretório que você está usando
        Assinatura do Azure: selecione a assinatura que você está usando
        Tipo de recurso: Idioma
        Nome do recurso: selecione o recurso do serviço de linguagem que você acabou de criar
        Em seguida, selecione Concluído.
     
c - Analisar avaliações no Language Studio:
 - Na página inicail do Language Studio, selecione a guia Classificar texto e, em seguida, selecione o bloco Analisar sentimento e minerar opiniões.
 - Em Selecionar idioma do texto, selecione Inglês ou outro idioma, comforme exemplo que for testar.
 - Selecione seu recurso.
 - Insira um texto, carregue um arquivo ou use um de nossos textos de amostra, copie e cole a seguinte avaliação:

Exemplo de texto, comforme exericio do lab:
Tired hotel with poor service
The Royal Hotel, London, United Kingdom
5/6/2018
This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.
Marque a caixa para confirmar que a demonstração incorrerá em uso e poderá incorrer em custos e selecione Executar.

   - Revisar a saída. TEremos o retorno da análise de sentimentos considerando, positivo, neutro e negativo.
   - Aqui o retorno para este texto foi:
     ![image](https://github.com/user-attachments/assets/c6a39b6f-0276-49ae-bc4a-3dc128e93047)

     
