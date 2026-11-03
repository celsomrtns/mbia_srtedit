# SRT Edit

Editor de legendas no formato `.srt`, executado diretamente no navegador. Com ele, você pode ajustar a sincronia do arquivo inteiro e editar, adicionar ou remover legendas individualmente.

## Como abrir

Abra o arquivo `index.html` em um navegador moderno. Não é necessário instalar dependências, iniciar um servidor ou enviar suas legendas para a internet: o processamento acontece no próprio navegador.

## Como usar

1. Clique em **Abrir arquivo SRT** e escolha uma legenda `.srt`.
2. Para ajustar a sincronia, arraste a barra ou digite um valor em milissegundos. Valores negativos adiantam as legendas; valores positivos atrasam. Confira o ajuste exibido em segundos e milissegundos e clique em **Aplicar ajuste**.
3. Edite o início, o fim e o texto diretamente em cada bloco.
4. Use **+ Adicionar bloco** entre as legendas para inserir uma nova fala naquele ponto. O novo bloco começa no tempo final do bloco anterior e tem duração inicial de dois segundos. Com a lista vazia, o mesmo botão cria o primeiro bloco.
5. Clique em **Remover** para excluir um bloco.
6. Clique em **Salvar SRT** para baixar a legenda editada.

Os blocos são numerados novamente na ordem em que aparecem sempre que a lista é atualizada, e o arquivo exportado recebe índices sequenciais automaticamente.

## Formato dos tempos

Os campos de início e fim aceitam o formato `HH:MM:SS,mmm`, por exemplo `00:01:23,450`. Também são aceitos arquivos SRT que usam ponto em vez de vírgula nos milissegundos.

Ao salvar, os horários são exportados com vírgula e os blocos com numeração sequencial. O arquivo mantém o nome original.

## Aparência

O tema claro ou escuro acompanha automaticamente a preferência de aparência do sistema operacional ou navegador. Para alterná-lo, altere a preferência de tema do dispositivo ou navegador.
