# Traduções
Repositório de traduções

Para códigos de localidade, verifique aqui: https://stackoverflow.com/questions/7973023/what-is-the-list-of-supported-languages-locales-on-android

## Passos
1. Bifurcar este repositório.
2. Se você já bifurcou e deseja atualizar uma tradução, sempre atualize seu repositório. Verifique esta resposta: https://stackoverflow.com/questions/20984802/how-can-i-keep-my-fork-in-sync-without-adding-a-separate-remote/21131381#21131381
3. Para cada aplicativo, `strings_nn.xml` é a string padrão em inglês. O `nn` é um número para refletir o número de compilação do aplicativo. O valor `nn` ajuda a distinguir se as traduções são atualizadas.
4. Para enviar uma nova tradução, crie um novo arquivo de strings com código de localidade, seguido pelo valor `nn`. Por exemplo, se você estiver fazendo uma tradução para o Turco, crie um arquivo `strings-tr_nn.xml` e coloque suas traduções nesse arquivo.
5. O `strings_nn.xml` original e o seu` strings-xx_nn.xml` devem estar no mesmo diretório.
6. <b>Importante</b>: No arquivo principal de strings, existe uma string `translators_list`. Ajude a si mesmo e adicione seu nome para mostrar que você contribuiu. :)
7. Após a tradução, envie uma solicitação de recebimento.
	<b>Importante</b>: Verifique outras solicitações pull antes de abrir a sua, a fim de minimizar traduções assíncronas

Obrigado.
