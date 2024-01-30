# Explorando o Language Studio
Análise de Sentimentos com Language Studio no Azure AI
### Crie um recurso de idioma
- No portal do Azure em https://portal.azure.com:
- Na página Criar Idioma , configure-o com as seguintes configurações:
  - Assinatura : sua assinatura do Azure.
  - Grupo de recursos : selecione ou crie um grupo de recursos com um nome exclusivo.
  - Região : Leste dos EUA.
  - Nome : Insira um nome exclusivo.
  - Nível de preços : F0 grátis ou S se F0 grátis não estiver disponível
  - Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo : Selecionado.
- Selecione Revisar + criar e depois Criar e aguarde a conclusão da implantação.
### Configure seu recurso no Azure AI Language Studio
- abra o Language Studio em https://language.cognitive.azure.com
- Quando solicitado com Select an Azure resource , faça as seguintes configurações:
  - Diretório do Azure : diretório padrão, o diretório que você está usando
  - Assinatura do Azure : selecione a assinatura que você está usando
  - Tipo de recurso : Idioma
  - Nome do recurso : selecione o recurso de serviço de idioma que você acabou de criar
- Em seguida, selecione Concluído.
### Analise avaliações no Language Studio
- Na página inicial Bem-vindo ao Language Studio , selecione a guia Classificar texto e, em seguida, selecione o bloco Analisar sentimento e extrair opiniões .
- Em Selecionar idioma do texto , selecione Inglês .
- Em Selecione seu recurso do Azure , selecione seu recurso.
- Em Digite seu próprio texto, carregue um arquivo ou use um de nossos textos de exemplo , copie e cole a seguinte revisão:
- Marque a caixa para confirmar que a demonstração incorrerá em uso e poderá incorrer em custos e selecione Executar .
- Revise a saída. Observe que o documento é analisado quanto ao sentimento, assim como cada frase . Selecione Frase 1 para mostrar a análise de sentimento dessa frase.

## Exemplos

<img src='./inputs/img/img 3.png' width='850'/>
<img src='./inputs/img/img 4.png' width='850'/>
<img src='./inputs/img/img 2.png' width='850'/>
<img src='./inputs/img/img 5.png' width='850'/>
<img src='./inputs/img/img 1.png' width='850'/>


