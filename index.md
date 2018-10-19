---
layout: default
image: /assets/thumbnail.jpg
---

<p class="anuncio">
Dia <strong>20/Out</strong> na UFPR, faremos um evento local para o
<a href="https://hacktoberfest.digitalocean.com/"> Hacktoberfest</a>.
Venha participar<br>

As inscriçes para o Hacktoberfest Curitiba 2018 já foram <strong>encerradas</strong>!!  

As atividades da parte da manhã são abertas para o público em geral. Porém, somente pessoas inscritas previamente poderão ter acesso ao evento na parte da tarde.  
Da mesma forma, apenas pessoas inscritas previamente poderão ter acesso aos computadores e internet para a realização das atividades!
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

Os workshops serão:  
-**GIT do Zero** (14:00hrs). Para iniciantes.  
-**GIT pra Quem Sabe** (14:00hrs). Para intermediários.  


Se você tiver disponibilidade para dar algum workshop, entre em contato pelo
[GitHub](https://github.com/hacktoberfestcwb/2018/).

## Projetos

Lista de projetos para participar. Lembre-se que buscar **issues** e comunicar o
interesse em fazer o Pull Request, para evitar múltiplas pessoas fazendo a mesma coisa.
Se não houverem issues abertas, mas você achar que pode contribuir de alguma maneira,
crie um issue para discutir.

{% for x in site.data.projetos %}
- [**{{ x.name }}**]({{ x.url }})
{% endfor %}
