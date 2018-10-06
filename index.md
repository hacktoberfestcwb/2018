---
layout: default
---

<div class="title">
  <img src="{{ site.baseurl }}/assets/logo-hack.png">
  CWB
</div>

Dia **20/Out** na UFPR, faremos um evento local para o
[Hacktoberfest](https://hacktoberfest.digitalocean.com/).
Venha participar.

Para ver detalhes da organização, acesse
[aqui](https://github.com/abelsiqueira/hacktoberfest-cwb-2018).

<h1 class="bg-emph">Site em construção, as informações aqui podem mudar a qualquer
momento. Vá ao site da organização acim para ver informações mais atuais</h1>

Inscrição

## Agenda

<table>
  <tr class="bg-emph">
    <th class="text-right">Hora</th>
    <th class="text-center">Sala 1</th>
    <th class="text-center">Sala 2</th>
  </tr>
  <tr>
    <td class="text-right">9:30</td>
    <td colspan="2">Abertura</td>
  </tr>
  <tr>
    <td class="text-right">10:00</td>
    <td colspan="2">Introdução a Software aberto e livre</td>
  </tr>
  <tr>
    <td class="text-right">11:00</td>
    <td colspan="2">
      <a href="#apre">Apresentações de projetos</a>
    </td>
  </tr>
  <tr>
    <td class="text-right">14:00</td>
    <td rowspan="2">Workshop de git e GitHub para iniciantes</td>
    <td>Tópicos avançados de git (como errar certo)</td>
  </tr>
  <tr>
    <td class="text-right">15:00</td>
    <td>???</td>
  </tr>
  <tr>
    <td class="text-right">16:00</td>
    <td colspan="2" rowspan="3">Período livre para trabalho</td>
  </tr>
  <tr>
    <td class="text-right">17:00</td>
  </tr>
  <tr>
    <td class="text-right">18:00</td>
  </tr>
  <tr>
    <td class="text-right">18:30</td>
    <td colspan="2">Fechamento</td>
  </tr>
  <tr>
    <td class="text-right">19:00</td>
    <td class="bg-emph" colspan="2">Happy Hour</td>
  </tr>
</table>

<h2 id="apre">Apresentações</h2>

Para aqueles buscando onde trabalhar e fazer seus Pull Requests, teremos apresentações
de desenvolvedores, coordenadores e interessados sobre projetos open source.
As apresentações serão curtas: 5 a 10 minutos, e bastante introdutórios, mas servem para
as pessoas conhecerem alguém do projeto para conversar posteriormente.

{% for x in site.data.apresentacoes %}
- **{{ x.name }}** (*{{ x.title }}*);
{% endfor %}

## Projetos

Lista de projetos para participar. Lembre-se que buscar **issues** e comunicar o
interesse em fazer o Pull Request, para evitar múltiplas pessoas fazendo a mesma coisa.
Se não houverem issues abertas, mas você achar que pode contribuir de alguma maneira,
crie um issue para discutir.

{% for x in site.data.projetos %}
- [**{{ x.name }}**]({{ x.url }})
{% endfor %}
