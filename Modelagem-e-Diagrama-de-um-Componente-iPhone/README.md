# iPhone
```Digite algo, aperte o botão e pronto```
* Sincroniza mídia, contatos, documentos com PC ou Mac, sincroniza dados da web ou do iPhone
* Conecta com wi-fi

  

| Reprodutor Musical                  | Aparelho Telefônico        | Navegador de Internet     |
| :---:                     |   :---:              |    :---:              |
|Toca músicas e vídeos       | App de ligações, conferência    |HTML, e-mail (IMAP, POP)|
|Controles sensíveis ao toque| Correio de voz visual | EDGE  (Safari)                 |
|Speaker                         |Bluetooth              |      Widget              |

## Diagrama

```mermaid
classDiagram
    class IPhone {
        <<abstract>>
        - String modelo
        - String sistemaOperacional
        - int armazenamento
        + void ligarIPhone()
        + void iniciarItunes()
        + void abrirInternetBrowser()
        + void fazerChamada()
    }

    class ReprodutorMusical {
        <<interface>>
        - List listaDeMusicas
        - List listaDeVideos
        - String musica
        + void tocarMusica()
        + void pausarMusica()
        + selecionarMusica(String musica)
    }

    class NavegadorInternet {
        <<interface>>
        - String urlAtual
        + void adicionarNovaAba()
        + void atualizarPagina()
        + void exibirPagiana(String url)
    }

    class AparelhoTelefonico {
        <<interface>>
        - String numeroAtual
        - List historicoDeChamadas
        + void ligar(String numero)
        + void iniciarCorreioVoz()
        + void atender()
    }

    class IPhoneX {
        - String modelo
        - String sistemaOperacional
        + iniciarItunes(): void
        + abrirInternetBrowser(): void
        + fazerChamada(): void
    }

        class IPhone11 {
        - String modelo
        - String sistemaOperacional
        + iniciarItunes(): void
        + abrirInternetBrowser(): void
        + fazerChamada(): void
    }

    IPhone --> ReprodutorMusical
    IPhone --> NavegadorInternet
    IPhone --> AparelhoTelefonico

    IPhone <|-- IPhoneX
    IPhone <|-- IPhone11
```
   
