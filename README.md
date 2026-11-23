# IPTV Player para Fire TV Stick

> **Aviso:** este app não fornece canais, filmes, séries nem listas. Ele só reproduz o conteúdo da conta Xtream que você já tem com o seu provedor. Você é responsável por usar uma conta e um conteúdo legais.

## O que é

Um player IPTV para Fire TV Stick, para contas no padrão Xtream Codes (servidor, usuário e senha). Tem Ao Vivo com guia, Filmes, Séries, Continuar assistindo, Favoritos, Busca e várias contas.

Testado no Fire TV Stick 4K (2018, Fire OS 6) e no Fire TV Stick 4K Max (Fire OS 8).

## Instalar pelo Downloader

<!-- Fire OS 6 e 8 conferidos em 23/11/2026. Fire OS 7 não conferido. -->

1. Instale o app **Downloader** pela loja da Amazon.
2. Libere a instalação de apps de fontes desconhecidas:
   - **Fire OS 6:** Configurações › Meu Fire TV › Opções para desenvolvedores › Aplicativos de fontes desconhecidas (deixe ATIVADO).
   - **Fire OS 7 e 8:** Configurações › Meu Fire TV › Opções para desenvolvimento › Instalar aplicativos desconhecidos › Downloader (deixe ATIVADO).
   - Se "Opções para desenvolvedores" (ou "para desenvolvimento") não aparecer, abra Configurações › Meu Fire TV › Informações e aperte OK 7 vezes no nome do aparelho.
3. Abra o Downloader, clique na barra de endereço no alto e digite este link:

   ```
   https://github.com/guedeswilson/iptv-player-releases/releases/latest/download/iptv.apk
   ```

   Ele sempre baixa a versão mais recente. Instale e abra o app.

## Primeiro uso

Preencha os dados da sua conta: um apelido (opcional), o servidor (por exemplo `http://servidor.example.com:8080`), o usuário e a senha. O app testa o login antes de salvar.

## Atualizações

<!-- Fire OS 6 e 8 conferidos em 23/11/2026. Fire OS 7 não conferido. -->

- Quando há versão nova, o app avisa ao abrir e pergunta "Atualizar agora?". Escolha **Atualizar**; quando o Fire TV mostrar a tela de instalação, vá até **Instalar** e aperte OK.
- No Fire OS 7 e 8, na primeira atualização, o app pede para permitir a instalação e abre Opções para desenvolvimento. Entre em **Instalar aplicativos desconhecidos**, aperte OK em **IPTV Player** até ficar ATIVADO, aperte Voltar duas vezes e escolha **Atualizar** de novo.
- No Fire TV Stick 4K de 2018 (Fire OS 6), o app costuma sumir de "Seus aplicativos e jogos" depois de atualizar. Reinicie o aparelho (Configurações › Meu Fire TV › Reiniciar) e ele volta.
- Também dá para procurar uma versão nova nas Configurações do app › Verificar atualização.
- As versões e as notas de cada uma ficam na página de [releases](https://github.com/guedeswilson/iptv-player-releases/releases) deste repositório.

## Privacidade

- As contas ficam só no aparelho. A senha é cifrada pelo Android Keystore, exceto no Fire OS 5.
- Com servidor `http://`, a senha vai sem criptografia pela rede, como em qualquer player.
- O app só fala com o seu servidor e com o GitHub (para procurar atualização).

---

Este repositório só distribui o app. O código não é público.
