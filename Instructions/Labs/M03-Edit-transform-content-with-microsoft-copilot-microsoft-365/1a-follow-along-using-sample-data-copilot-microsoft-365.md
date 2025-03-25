# Exercício – Acompanhar usando dados de amostra com o Microsoft 365 Copilot

No restante do módulo, criaremos prompts para o Microsoft 365 Copilot que fazem referência aos seguintes arquivos:

- [Graphic Design Institute - Employee Benefits.docx](https://go.microsoft.com/fwlink/?linkid=2268825)
- [Mystic Spice Premium Chai Market Analysis Presentation.pptx](https://go.microsoft.com/fwlink/?linkid=2268768)
- [Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)

**Observação**: estes são os arquivos que faremos referência ao longo do módulo. Para este laboratório, no entanto, começaremos carregando todos os arquivos no **OneDrive** para garantir que eles estejam acessíveis para prompts do Copilot posteriormente.

## Carregar arquivos no OneDrive

Siga as etapas abaixo para carregar todos os arquivos necessários no **OneDrive**:

1. Faça logon na máquina virtual fornecida pelo provedor de locatários como a conta de **administrador** local com a senha `Pa55w.rd`.
2. Na barra de tarefas do Windows, selecione **Microsoft Edge**.
3. Na barra de endereços, insira `https://www.office.com` .
4. Em **Bem-vindo ao Microsoft 365**, selecione **Entrar**.
5. Na **solicitação de logon**, insira `userx@yourtenant.onmicrosoft.com` (nome de usuário e locatário fornecidos pelo provedor de locatário) e selecione **Avançar**.

    [![Painel de recursos de captura de tela em skillable](../media/lab_resources_password.png)](../media/lab_resources_password.png#lightbox)

6. Na tela **Inserir senha**, insira a senha (fornecida pelo provedor de locatário) para a conta de usuário e selecione **Entrar**.
7. Se solicitado a **Permanecer conectado**, selecione **Não mostrar isso novamente** e, em seguida, **Sim**.
8. No **Microsoft 365**, selecione **Aplicativos**.
9. Em **Aplicativos**, selecione **OneDrive**.
10. No **OneDrive**, no canto superior esquerdo, selecione **+** (adicionar novo) > **Upload de arquivo**.
11. No **Explorador de Arquivos**, selecione **Este PC** > **Disco Local (C:)** e abra a pasta **ResourceFiles.**
12. Selecione todos os arquivos na pasta **ResourceFiles** e selecione **Abrir** para carregá-los no **OneDrive**.
13. Quando o upload for concluído, você deverá ver **Carregado 29 itens para Meus arquivos** na parte inferior central da tela.
14. Deixe o **Edge** aberto e passe para a próxima tarefa.

### Referenciar arquivos

Ao fazer referência a arquivos do Copilot, você pode descobrir que não consegue encontrar alguns arquivos das sugestões fornecidas a você. Isso ocorre, às vezes, porque algumas experiências com o Copilot apenas fazem referência a arquivos da lista de recém-usados, enquanto outras permitem que você navegue diretamente no OneDrive para encontrar o arquivo. Adicioná-los a essa lista é tão fácil quanto abri-los no aplicativo Microsoft 365 apropriado.  Depois de abertos, eles devem aparecer na lista de recém-usados.

> [!IMPORTANT]
> O Microsoft 365 Copilot só funcionará com arquivos salvos no OneDrive. Os arquivos armazenados localmente em seu computador precisarão ser movidos para o OneDrive a fim de ativar o Copilot.

À medida que avança no módulo, você terá a oportunidade de experimentar outros prompts nesses arquivos e é incentivado a fazer isso para explorar e aprimorar suas habilidades nesse sentido.
