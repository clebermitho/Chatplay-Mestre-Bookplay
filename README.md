# ChatPlay Mestre · BookPlay e PaguePlay

Extensão para o ChatPlay do CRM. Funciona nos dois endereços: **crm.bookplay.com.br** e **crm.pagueplay.com.br**,
com as regras da BookPlay.

> **Importante:** o ChatPlay é oficial e foi feito pela TI. O ChatPlay Mestre é uma **extensão à parte**,
> que não foi feita pela TI e pode sair do ar a qualquer momento. Confira sempre a mensagem antes de enviar.

## O que ela faz

- **Calculadora de propostas** com os valores do cliente aberto e a mensagem pronta (botão ao lado das mensagens rápidas).
- **Abordagem automática** no «Sim» de iniciar: apresentação, acordo, quebra de acordo ou negociação em andamento,
  com o **valor exato do acordo** e a **Opção 3** (melhor desconto para quitação hoje) no acordo e na quebra.
- **Dados do cliente**: CPF, telefone e protocolo com botão de copiar.
- **Sinalizados com aviso**: som, card e notificação quando o cliente escreve, mesmo depois de finalizado.
- **Retomar conversas** em lote, **pasta** de cada cliente na fila, **contagem** de tempo e **papel de parede**.
- **Trava de setores (opcional, vem desligada)**: em Ajustes, escolha quais setores travar (Play em dia, Play 1 a Play 6) e o horário. No «Sim» de iniciar, cliente de um setor travado é segurado com uma tela vermelha.

## Como instalar

1. Instale o [Tampermonkey](https://www.tampermonkey.net/) no navegador.
2. Clique neste link e depois em **Instalar**:
   **[ChatPlay-Mestre-BookPlay.user.js](https://raw.githubusercontent.com/clebermitho/Chatplay-Mestre-Bookplay/main/ChatPlay-Mestre-BookPlay.user.js)**
3. Abra o ChatPlay no CRM. Em **Ajustes** (ícone de engrenagem no painel), preencha o seu nome.

Deixe ligado no Tampermonkey **só um** ChatPlay Mestre. Quem já tinha o ChatPlay Mestre instalado à mão:
instalar por este link substitui o antigo e mantém as configurações.

## Atualizações

Quando sai uma versão nova, o próprio ChatPlay Mestre mostra um card **«Nova versão do ChatPlay Mestre»** no canto da tela:
clique em **Atualizar agora**, depois em **Atualizar** na aba que abrir, e recarregue o ChatPlay.

Mesmo sem clicar, o Tampermonkey confere este endereço uma vez por dia e atualiza sozinho.
Para buscar na hora: ícone do Tampermonkey › **Painel** › **Utilitários** › **Verificar atualizações de scripts**.
