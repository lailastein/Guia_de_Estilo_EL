# Convertento texto para áudio

## Novo arquivo 

1. Para realizar uma conversão clique em **"Novo"** no menu lateral esquerdo da tela.

![image](https://github.com/lailastein/guiadeestilo/assets/157158368/ad648622-2b38-4c99-8ad0-13ac92855945)

2. O primeiro campo deve ser preenchido com o nome que o arquivo gerado terá. Por padrão os nome são iniciados com a sigla do sistema e depois adicionado o nome da funcionalidade.
> Exemplo: TRB - Cálculo Geral

## Formatando texto

3. O texto a ser inserido no próximo campo deve ser formatado utilizando marcadores em html. que ficam disponíveis ao final da página em **"Recursos"**.

![image](https://github.com/lailastein/guiadeestilo/assets/157158368/2a7e1640-125a-4dbc-8a8b-9d072a4ae47a)

Cada marcação possui uma funcionalidade diferente. As mais utilizadas no caso dos POP's são:

| Elemento | Formato | Descrição |
| -------- | ------- | --------- |
| `<break time="3000" />` | | Use o elemento break para inserir pausas ou interrupções entre as palavras e frases. O tempo da pausa deve ser informado em milissegundos, por exemplo: 1000ms para 1 segundo, 5000ms para 5 segundos, etc.|
|address| | O texto é falado como um endereço. Estou na `<say-as interpret-as="address">` Rua João Batista Wernersbach, 67, Centro, Domingos Martins, ES.</say-as> O mecanismo de sintetização de voz pronuncia: "Estou na Rua João Batista Wernersbach, 67, Centro, Domingos Martins, ES".|
|cardinal, number| |O texto é falado como um número cardinal. Há `<say-as interpret-as="cardinal">3</say-as>` alternativas. O mecanismo de sintetização de voz pronuncia: "Há três alternativas".|
|characters, spell-out| |O texto é falado como letras individuais (soletrado). `<say-as interpret-as="characters">GPI</say-as>` O mecanismo de sintetização de voz pronuncia: "G P I".|
|date|dmy, my, dm, d, m, y|O texto é falado como uma data. O atributo format especifica o formato da data (d = dia, m = mês e y = ano). Hoje é `<say-as interpret-as="date" format="mdy">22-06-2022</say-as>`. O mecanismo de sintetização de voz pronuncia: "Hoje é vinte e dois de junho de dois mil de vinte e dois".|
|digits, number_digit| | O texto é falado como uma sequência de dígitos individuais. `<say-as interpret-as="number_digit">123456789</say-as>` O mecanismo de sintetização de voz pronuncia: "1 2 3 4 5 6 7 8 9".|
|fraction|	|	O texto é falado como um número fracionário. `<say-as interpret-as="fraction">3/8</say-as>` de uma polegada. O mecanismo de sintetização de voz pronuncia: "três oitavos de uma polegada".|
|ordinal|	|O texto é falado como um número ordinal. Selecione a `<say-as interpret-as="ordinal">3a</say-as>` opção. O mecanismo de sintetização de voz pronuncia: "Selecione a terceira opção".|
|telephone|	|	O texto é falado como um número de telefone. O atributo format pode conter dígitos que representam um código de país. Alguns exemplos incluem "1" para os Estados Unidos ou "39" para a Itália. O mecanismo de sintetização de voz pode usar essas informações para orientar a pronúncia de um número de telefone. O número de telefone também pode incluir o código do país e, nesse caso, ele tem precedência sobre o código do país indicado no atributo format. Meu número é `<say-as interpret-as="telephone" format="1">(27) 3268-3123</say-as>`. O mecanismo de sintetização de voz pronuncia: "Meu número é código de área vinte sete três dois seis oito três um dois três".|
|time|hms24|	O texto é falado como uma hora. O atributo format especifica se a hora é especificada com um relógio de 24 horas (hms24). Use dois-pontos para separar números que representam horas, minutos e segundos. Estes são alguns exemplos de horas válidos: 12:35, 13:14:32, 08:15 e 22:50:45. Agora são `<say-as interpret-as="time" format="hms24">10:50</say-as>`. O mecanismo de sintetização de voz pronuncia: "Agora são dez horas e cinquenta minutos".
|name|		|O texto é falado como um nome de pessoa. `<say-as interpret-as="name">ED</say-as>`
