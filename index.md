---
layout: default
---

<p class="anuncio">
Dia <strong>20/Out</strong> na UFPR, faremos um evento local para o
<a href="https://hacktoberfest.digitalocean.com/"> Hacktoberfest</a>.
Venha participar<br>

<a href="https://goo.gl/forms/J62F29jMm5Gpl85m2">Inscrições abertas</a>
até dia 16/10, 23:59.
</p>

Para ver detalhes da organização, acesse
[aqui](https://github.com/hacktoberfestcwb/2018/).

*Aviso: detalhes do evento ainda estão sendo discutidos, como a agenda e as
apresentações. Se quiser **apresentar** ou participar das discussões vá ao site acima.*

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
    <td rowspan="2">Workshops*</td>
    <td rowspan="2">Workshops*</td>
  </tr>
  <tr>
    <td class="text-right">15:00</td>
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

## Workshop

Ainda não fechamos os workshops. Gostaríamos de fazer um de git básico para iniciantes,
e talvez um intermediário. Se você tiver disponibilidade, entre em contato no
[GitHub](https://github.com/hacktoberfestcwb/2018/).

## Projetos

Lista de projetos para participar. Lembre-se que buscar **issues** e comunicar o
interesse em fazer o Pull Request, para evitar múltiplas pessoas fazendo a mesma coisa.
Se não houverem issues abertas, mas você achar que pode contribuir de alguma maneira,
crie um issue para discutir.

{% for x in site.data.projetos %}
- [**{{ x.name }}**]({{ x.url }})
{% endfor %}
