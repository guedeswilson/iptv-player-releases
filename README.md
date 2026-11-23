# IPTV Player para Fire TV Stick

> **Aviso:** este app não fornece canais, filmes, séries nem listas. Ele só reproduz o conteúdo da conta Xtream que você já tem com o seu provedor. Você é responsável por usar uma conta e um conteúdo legais.

## O que é

Um player IPTV para Fire TV Stick, para contas no padrão Xtream Codes (servidor, usuário e senha). Tem Ao Vivo com guia, Filmes, Séries, Continuar assistindo, Favoritos, Busca e várias contas.

Testado no Fire TV Stick 4K (2018, Fire OS 6) e no Fire TV Stick 4K Max (Fire OS 8).

## Instalar pelo Downloader

<!-- A CONFERIR NA TAREFA 13: os caminhos de menu abaixo ainda não foram conferidos nos aparelhos (Fire OS 6 e Fire OS 8). Corrigir pelos screencaps antes de considerar este texto final. -->

1. Instale o app **Downloader** pela loja da Amazon.
2. Libere a instalação de apps de fontes desconhecidas:
   - **Fire OS 6:** Configurações › Meu Fire TV › Opções do desenvolvedor › Apps de fontes desconhecidas.
   - **Fire OS 7 e 8:** Configurações › Meu Fire TV › Opções do desenvolvedor › Instalar apps desconhecidos › Downloader.
   - Se "Opções do desenvolvedor" não aparecer, abra Configurações › Meu Fire TV › Sobre e aperte OK 7 vezes no nome do aparelho.
3. Abra o Downloader e digite este link:

   ```
   https://github.com/guedeswilson/iptv-player-releases/releases/latest/download/iptv.apk
   ```

   Ele sempre baixa a versão mais recente. Instale e abra o app.

## Primeiro uso

Preencha os dados da sua conta: um apelido (opcional), o servidor (por exemplo `http://servidor.example.com:8080`), o usuário e a senha. O app testa o login antes de salvar.

## Atualizações

<!-- A CONFERIR NA TAREFA 13: os caminhos de menu desta seção também. -->

- Quando há versão nova, o app avisa ao abrir e pergunta "Atualizar agora?".
- Na primeira atualização, o Fire TV pede para permitir que o IPTV Player instale apps.
- No Fire TV Stick 4K de 2018, se o app sumir da tela inicial depois de atualizar, reinicie o aparelho (Configurações › Meu Fire TV › Reiniciar).
- Também dá para procurar uma versão nova nas Configurações do app › Verificar atualização.
- As versões e as notas de cada uma ficam na página de [releases](https://github.com/guedeswilson/iptv-player-releases/releases) deste repositório.

## Privacidade

- As contas ficam só no aparelho. A senha é cifrada pelo Android Keystore, exceto no Fire OS 5.
- Com servidor `http://`, a senha vai sem criptografia pela rede, como em qualquer player.
- O app só fala com o seu servidor e com o GitHub (para procurar atualização).

---

Este repositório só distribui o app. O código não é público.
