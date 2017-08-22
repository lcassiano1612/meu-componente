# Criando um componente
O tutorial para criar seu primeiro componente vai estar aqui: linkmedium

Estou usando este cara aqui como referencia: https://codelabs.developers.google.com/codelabs/polymer-first-elements/#0

###### O que vou usar:

- Ubuntu 16.04;
- Sublime Text;
- Terminal;


# Configurando o ambiente

1. Vamos baixar o nodejs, eu estou usando a versão node v6.11.2, e instalar através do comando:
``` 
sudo apt-get update
sudo apt-get install nodejs
```
2. Apos o node vamos instalar o bower e o polymer-cli globalmente:
```
npm install -g bower polymer-cli
```
3. Clone o projeto abaixo:
```
https://github.com/googlecodelabs/polymer-first-elements.git
```
4. Vamos acessar o projeto ```polymer-first-elements``` e executar o ```bower```:
```
cd polymer-first-elements
bower install
```
5. Agora vamos rodar o servidor local que o proprio Polymer oferece:
```
polymer serve
```

No seu terminal vai ficar desta maneira:

<img> 

Pronto agora você pode acessar o caminho abaixo e iniciar o projeto com tudo configurado!
```
localhost:8080/components/icon-toggle/demo/
```