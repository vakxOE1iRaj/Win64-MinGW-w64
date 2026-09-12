# Acessando a documentação

### Reminder

Anotacao pessoal, sem relacao direta com o restante do texto.


O professor abriu a página inicial do site da biblioteca e usou o botão de leitura da documentação. Ali, dentro do menu de guias, aparece a lista com os tipos de navegação:

![types of navigations in dcoumentation](images/tipos-de-navegacao.png)


# Tipos de navegação

A imagem abaixo mostra a navegação por abas inferiores, com os botões na parte de baixo do aplicativo:

![bottom tabs](images/abas-inferiores.png)

Também foi citada a navegação por pilha, muito comum, em que as telas se comportam como elementos de uma pilha.

A aula observou que é normal um aplicativo móvel ser mais simples que um aplicativo web, com menos funcionalidades para ficar direto.

A imagem seguinte mostra um exemplo de abas no topo:

![material top](images/abas-no-topo.png)

Navegação por gaveta: segundo a aula, é o tipo em que um menu é puxado pela lateral do aplicativo.

![drwaer navigation](images/gaveta.png)

A orientação foi não misturar vários tipos de navegação no mesmo aplicativo, para não confundir quem usa.


# O que é um navegador de telas

Segundo a aula, é o componente que escolhe entre as telas por meio de rotas — as setas entre o navegador e as telas na imagem abaixo:

![navigator and screens - illustration](images/navegador-e-telas.png)


# Criando a primeira rota

A orientação foi criar um arquivo para cada estratégia de navegação:

![file to routing strategy](images/arquivo-de-rotas.png)

Na imagem, repare no arquivo de rotas da pilha.

Os ícones mostrados na imagem do editor vêm de uma extensão de ícones de material.

# Instalando a biblioteca de navegação por pilha

Como mostra o repositório do curso, algumas dependências já estavam instaladas. A biblioteca de navegação não instala tudo de uma vez: existe um pacote adicional por tipo de navegação.

O comando para instalar a navegação por pilha está na documentação oficial:

```
npm install @react-navigation/stack
```

Também criei um projeto de teste numa das pastas de teste do repositório.