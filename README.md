<p align="center">
<img with="240" height="200" src="https://github.com/Cominfbr/Marca/blob/Master/logo_transparent.png" alt="Logo CominfBR">
</p>
<h1 align="center">Cominfbr Site</h1>

## Sobre

Este projeto é um site estático gerado automaticamente pelo <a href="https://jekyllrb.com/">Jekyll<a>, um gerador de páginas estáticas, para facilitar a configuração do site e das páginas e a manutenção do código.
Além do Jekyll, utilizamos o Github Pages, um serviço de build, deploy e gestão de projetos, para Continuous Deploy e HTTPS.
Utilizamos o dunders, um <a href="https://github.com/CloudCannon/urban-jekyll-template">Urban theme</a>, para agilizar a criação do nosso tema para o Jekyll.

## Requisitos

Para rodar este site localmente será necessário a instalação das seguintes dependências:

- Ruby
- Jekyll

Para a instalação do Ruby, recomendamos a utilização de um gerenciador de versões, como o RVM e para a instalação do Jekyll basta seguir a documentação do Jekyll.

Caso você não consiga instalar alguma das dependências, pode abrir uma issue neste repositório para lhe auxiliarmos.

Rodando localmente
Clone nosso projeto para o seu ambiente de desenvolvimento.
```
git clone git@github.com:cominfbr/cominfbr.github.io.git
```

Execute o comando bundle para instalar as dependências do Jekyll e do dunders.
```
bundle
```

Agora basta rodar o comando para subir o site em sua máquina, o jekyll s.
```
jekyll s
```

O site estará disponível em `localhost:4000`.

Deploy para produção
Todo merge feito em nossa branch master gera um deploy automático no Github Pages.

Estrutura de arquivos
Images

Nossas imagens, fontes, etc.

sitemap.xml

As partials do nosso site, os "pedaços" do site.

- footer.html: o footer do template
- /blog: o blog da página
- /postagens : o postagens do blog
- LICENSE

O scaffolding para o Jekyll gerar nosso site.

Outros arquivos

- CNAME: mapeamento do nosso domínio para o DNS
- _config.yml: o arquivo de configuração do nosso site
- index.html: o index do site
- robots.txt: muito importante para SEO, confira aqui

## Contribuidores

| [![ Carlos Vítor](https://github.com/carlosvitr.png?size=100)](https://github.com/carlosvitr) |
| -----------------------------------------------------------------------------------------------|
| [Carlos Vítor](https://github.com/carlosvitr)                                                  |

---
## Licença

Cominfbr.github.io © <a href="https://cominfbr.cf/">Cominfbr</a> 2018-2021 Lançado sob a <a href="https://github.com/Cominfbr/cominfbr.github.io/blob/master/LICENSE">licença MIT</a>. De autoria e manutenção de <a href="https://github.com/carlosvitr">Carlos Vítor</a> com a ajuda de <a href="https://github.com/Cominfbr/cominfbr.github.io/pulse">colaboradores</a>.
> Github: <a href="github.com/cominfbr">@Cominfbr</a> • Twitter: <a href="twitter.com/cominfbr">@Cominfbr</a> • LinkedIn: <a href="linkedin.com/company/cominfbr">Cominf-br</a>
