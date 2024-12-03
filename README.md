# PDMI6_TP03
- TP 03 da matéria de dispositivos móveis
LogisticaRastreamento
Descrição
LogisticaRastreamento é um aplicativo de rastreamento de pacotes desenvolvido com .NET MAUI. Ele permite que os usuários insiram um código de rastreamento para obter informações detalhadas sobre o status do pacote, incluindo histórico de eventos.

Estrutura do Projeto
MainPage.xaml: Página principal onde o usuário insere o código de rastreamento.
ResultadosPage.xaml: Página que exibe os detalhes do pacote e o histórico de eventos.
PacoteViewModel.cs: ViewModel que gerencia os dados dos pacotes e a lógica de busca.
Styles.xaml: Arquivo de recursos que contém os estilos usados nas páginas.
Funcionalidades
Entrada de Código de Rastreamento: Permite ao usuário inserir um código de rastreamento.
Exibição de Detalhes do Pacote: Mostra informações como ID do pacote, status, data de envio e data prevista de entrega.
Histórico de Eventos: Lista os eventos históricos do pacote.
Alerta de Pacote Não Encontrado: Exibe um alerta caso o código de rastreamento não seja encontrado.
Estrutura de Arquivos
LogisticaRastreamento/
│
├── Models/
│   └── PacoteModel.cs
│
├── ViewModels/
│   └── PacoteViewModel.cs
│
├── Views/
│   ├── MainPage.xaml
│   ├── ResultadosPage.xaml
│   └── Styles.xaml
│
└── App.xaml

Como Executar
Clone o repositório:
Abra o projeto no Visual Studio.
Compile e execute o projeto em um emulador ou dispositivo físico.
Exemplo de Uso
Abra o aplicativo.
Insira o código de rastreamento no campo de entrada.
Clique no botão "Rastrear".
Veja os detalhes do pacote e o histórico de eventos na página de resultados.
Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

