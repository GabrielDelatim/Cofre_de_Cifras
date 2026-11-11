# Cofre de Cifras
Aplicação web para criptografar e descriptografar textos diretamente no navegador, reunindo algoritmos modernos de criptografia e métodos clássicos para fins educacionais.

O projeto oferece uma interface minimalista e intuitiva, permitindo proteger informações por meio de senhas ou pares de chaves criptográficas, sem necessidade de enviar os dados para um servidor.

Funcionalidades

AES-256-GCM: criptografia simétrica autenticada com proteção por senha.

Derivação de chaves (PBKDF2): transformação de senhas em chaves criptográficas, com diferentes níveis de iteração.

RSA híbrido: utilização de RSA-OAEP com SHA-256 para proteção de uma chave AES, permitindo criptografia assimétrica de textos.

Geração de chaves: criação de pares de chaves públicas e privadas.

Cifras clássicas: César, Vigenère, Atbash e ROT13, além de XOR e Base64 para fins didáticos.

Gerenciamento de resultados: copiar, reutilizar e limpar textos processados.

Interface responsiva: suporte a diferentes tamanhos de tela e temas claro e escuro.

Tecnologias utilizadas

HTML5

CSS3

JavaScript

Web Crypto API

Segurança e privacidade

O processamento criptográfico é realizado localmente no navegador, utilizando recursos da Web Crypto API.

As senhas e os textos não são enviados para servidores externos pela aplicação. As chaves privadas devem ser armazenadas com segurança pelo próprio usuário.

Observação: os métodos clássicos e a codificação Base64 não oferecem proteção criptográfica adequada para informações confidenciais. Para essa finalidade, recomenda-se utilizar AES-256-GCM ou RSA híbrido.

Execução

A aplicação funciona diretamente em navegadores modernos com suporte à Web Crypto API. Salve ou abra o arquivo HTML em um ambiente compatível com contexto seguro.

Objetivo

O projeto tem como objetivo explorar conceitos de criptografia, manipulação de dados e desenvolvimento web, reunindo conhecimentos técnicos em uma aplicação prática e acessível.
