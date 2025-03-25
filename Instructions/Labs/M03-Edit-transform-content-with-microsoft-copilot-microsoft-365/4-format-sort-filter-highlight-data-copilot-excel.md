# Formatar, classificar, filtrar e realçar dados usando o Microsoft 365 Copilot no Excel

Com o Microsoft 365 Copilot no Excel, é fácil destacar, classificar e filtrar suas tabelas para direcionar a atenção rapidamente para o que é importante para você. Usando uma única tabela no Excel, você pode ter o Copilot sem esforço:

- Classifique e filtre os dados.

- Aplique formatação condicional simples.

Para começar, formate seus dados em um [formato compatível](https://support.microsoft.com/topic/format-data-for-copilot-in-excel-1604c8eb-57f1-4db1-8363-d53336228c65) e selecione o botão **Copilot** na faixa de opções. Em seguida, diga ao Copilot como você gostaria de manipular a tabela para visualizar melhor partes de seus dados.

No exemplo a seguir, começaremos com um prompt simples e adicionaremos elementos ao longo do caminho. Acompanhe o exemplo usando seus próprios dados.

## Vamos começar a criar

Primeiro, baixe **_[Faibrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_** e salve o arquivo na **pasta do OneDrive**, caso ainda não tenha feito isso.

Abra a planilha no Excel e, em seguida, abra o painel do **Copilot** selecionando o ícone Copilot na guia **Página Inicial** da faixa de opções. Insira os prompts abaixo e acompanhe.

> [!NOTE]
> Prompt inicial:
>
> _Classifique esta tabela._

Neste prompt simples, você começa com o **objetivo** básico: _classificar e filtrar uma tabela do Excel._ No entanto, não há indicação de como você deseja que os dados sejam classificados e qual campo deseja filtrar.

| Elemento | Exemplo |
| :------ | :------- |
| **Prompt básico:** comece com uma **meta** | **_Classifique esta tabela..._** |
| **Prompt razoável:** adicione **contexto** | Adicionar **contexto** pode ajudar o Copilot a entender para que servem os slides e em qual tópico focar. _"...para procurar o vendedor mais impactante."_ |
| **Prompt ainda melhor:** especifique as **fontes** | Supõe-se que a **Fonte** desse prompt seja a tabela com a qual estamos trabalhando no Excel. _"... esta tabela [Table1]…"_ |
| **O prompt ideal:** defina **expectativas** claras | Por fim, adicionar **Expectativas** pode ajudar o Copilot a entender como você deseja que a tabela seja classificada, filtrada e apresentada. _"E destacar os proprietários de campanhas superiores e inferiores com base na receita líquida."_ |

> [!NOTE]
> **Prompt criado**:
>
> _Classifique esta tabela [Table1] para procurar o vendedor mais impactante e destacar os proprietários principais e inferiores da campanha com base na receita líquida_

Esse prompt requer várias etapas para executar uma técnica de prompt chamada **encadeamento**, onde você pede ao Copilot para executar comandos sequenciais e consecutivos para atingir um único objetivo.

**Primeiro prompt**:

```text
Sort this table [Table1] to look for the most impactful salesperson.
```

**Segundo prompt**:

```text
highlight the top and bottom campaign owners based off of net revenue
```

O Copilot tem todas as informações necessárias para lhe dar uma resposta sólida, graças a ter **Objetivo**, **Contexto**, **Fonte** e **Expectativas** neste prompt.

## Explorar mais

Experimente estes prompts simples para destacar, classificar e filtrar seus dados e adicionar outros elementos para melhorar seus resultados:

- Marque em negrito os 10 principais valores na coluna Vendas.

- Destaque os maiores valores em Unidades Vendidas.

- Classifique a taxa de participação da menor para a maior.  

- Filtre para itens que vencem na próxima semana.

> [!IMPORTANT]
> O Copilot só funcionará em arquivos armazenados no OneDrive ou no SharePoint. Se você não conseguir selecionar o botão do Copilot na faixa de opções, tente salvar o arquivo na nuvem primeiro. Para mais informações, consulte [Destaque, classifique e filtre seus dados com o Copilot no Excel](https://support.microsoft.com/office/highlight-sort-and-filter-your-data-with-copilot-in-excel-05302e3f-de42-4475-b235-be9cb3d4e936).
