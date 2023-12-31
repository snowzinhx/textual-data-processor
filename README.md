# Documentação do Projeto: Processador de Dados Textuais

## Indice
1. [Visão geral](#visão-geral)
2. [Instalação](#instalação)
3. [Uso básico](#uso-básico)
4. [Contribuição](#contribuição)
5. [Licença](#licença)

## Visão Geral

O Processador de Dados Textuais é construído em cima das bibliotecas Node.js ***fs*** e ***path***, e segue uma estrutura modular que permite a transformação eficiente de dados não estruturados em objetos chave-valor bem organizados. Suas principais funcionalidades incluem:

- Identificação e leitura de arquivos de texto em um diretório especificado.
- Processamento e análise dos dados contidos nos arquivos, convertendo-os em objetos estruturados.
-  Criação de objetos chave-valor a partir dos dados processados.

## Instalação

1. Certifique-se de ter o Node.js instalado em sua máquina.
2. Clone o repositório
~~~bash
git clone https://github.com/snowzinhx/data-text-processor.git
~~~
3. Navegue até o diretório do projeto e instale as dependências:
~~~Javascript 
cd processador-de-dados-textuais
npm install
~~~

## Uso Básico
1. ### Importe o Módulo:
~~~Javascript
import DataProcessor from './caminho/para/DataProcessor';
~~~
2. ### Crie uma Instância:
~~~Javascript
const dataPath = '/caminho/para/seus/dados';
const processor = new DataProcessor(dataPath);
~~~
3. ### Processamento de Arquivos:

Utilize o método processFiles() para processar os arquivos e obter os objetos de dados: 
~~~Javascript
const processedData = processor.processFiles();
console.log(processedData);
~~~

## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir para o projeto, siga estas etapas:

1. Faça um fork do repositório e clone-o em sua máquina.

2. Crie um novo branch para suas modificações:
~~~bash
git checkout -b minha-contribuicao
~~~
3. Faça as modificações desejadas e adicione documentação quando apropriado.
4. Faça commit das suas alterações:
~~~bash
git commit -m "Minha contribuição: descrição das alterações"
~~~
5. Envie as alterações para o seu fork:
~~~bash
git push origin minha-contribuicao
~~~
6. Abra um pull request explicando suas alterações e aguarde a revisão.

## Licença


[The MIT License (MIT)](LICENSE)

Copyright (c) 2023 - Snowzinhx
