+++
draft = true
date = 2024-12-05
authors = ["Thiago Campos"]
title = "Estado da Privacidade no iOS"
description = "Descrição da Notícia/Artigo (Não será visual, mas será usada em Meta Tags)" 
[taxonomies]
categorias = ["artigos"]
assuntos = ["apple", "privacidade"]
[extra]
keywords = ["Apple", "iOS", "iPhone","iPadOS", "Privacidade", "Segurança"]
mastodon = ["@thigcampos.mastodon.social"]
longDate = "05 de Dezembro, 2024"
+++
Aclamado por sua robusta proteção de dados e aderência às melhores práticas de segurança, o iOS se destaca como uma das opções mais confiáveis em termos de segurança e privacidade para o usuário comum, apesar de ser um sistema fechado, desenvolvido e mantido por uma das maiores corporações do mundo. Mesmo em um ambiente já considerado seguro, ajustes e configurações adicionais podem elevar ainda mais o nível de proteção oferecido pelo sistema.

<!-- more -->

> **Nota**: É importante ressaltar que o **iOS** garante um nível adequado de segurança para a maioria dos usuários. No entanto, para aqueles que necessitam de padrões mais rigorosos de privacidade e proteção, uma alternativa interessante seria explorar versões personalizadas do **Android**, como o [GrapheneOS](https://grapheneos.org/).

### iCloud

Uma parte relevante das preocupacões com segurança e privacidade ao utilizar o **iOS**, está no uso dos serviços de nuvem da Apple. O **iCloud**, por padrão, armazena a maior parte das suas informações em seus servidores, protegendo-as com chaves que a Apple tem acesso; uma tabela disponibilizada na [documentação da Apple](https://support.apple.com/pt-br/102651) informa de maneira bem transparente quais dados são ou não protegidos por criptografia de ponta a ponta. Ao não manter os seus dados salvos com esse tipo de criptografia, suas informações ficam passíveis de serem acessadas sob: aplicação das leis locais e vazamentos de dados.

Dado o cenário, recomenda-se a ativação da [Proteção Avançada de Dados do iCloud](https://support.apple.com/pt-br/108756) que aplica a criptografia de ponta a ponta em praticamente todos os seus dados, com exceção para: **e-mails**, **contatos** e **calendários**. A ativação só será permitida mediante cumprimento de alguns pré-requisitos, incluindo possuir um contato de recuperação da conta ou chave reserva.

Ademais, recomenda-se também limitar a sincronização dos dados com o **iCloud**, garantindo que apenas o essencial seja enviado para os servidores da Apple. 

### iCloud+

O serviço de assinatura do **iCloud** inclui algumas funcionalidades focadas em privacidade, como: 

[Retransmissão Privada](https://support.apple.com/pt-br/guide/icloud/mm7dc25cb68f/icloud):  Um serviço de proxy que retransmite todo o seu tráfego do Safari, suas consultas DNS e tráfego não criptografado em seu dispositivo através de dois servidores: um servidor da Apple e outro de um provedor terceirizado (incluindo Akamai, Cloudflare e Fastly). Em teoria, isso deve impedir que qualquer provedor da cadeia, incluindo a Apple, tenha visibilidade total de quais sites você visita enquanto estiver conectado.

[Ocultar Meu E-mail](https://support.apple.com/pt-br/guide/icloud/mm9d9012c9e8/icloud): Um serviço de aliasing de e-mail da Apple. Você pode criar aliases de e-mail gratuitamente ao fazer login com a Apple em um site ou aplicativo, ou gerar aliases ilimitados sob demanda. Ocultar Meu E-mail tem a vantagem de usar o domínio `@icloud.com` para seus aliases, que podem ser menos prováveis de serem bloqueados em comparação com outros serviços de aliasing de e-mail.

Ainda que sejam úteis, os serviços são limitados quando comparados com serviços parecidos de empresas terceiras.
