{% block body %}
<p align="center" style="line-height: 100%"><img src="brasao.png" name="Imagem 1" align="bottom" width="71" height="76" border="0"></p>
<p align="center" style="line-height: 100%"><font face="Arial Narrow, serif" size="2" style="font-size: 10pt"><b>SERVIÇO PÚBLICO FEDERAL</b></font></p>
<p align="center" style="line-height: 100%"><font face="Arial Narrow, serif" size="2" style="font-size: 10pt"><b>{{book.contratante.ministerio}} - {{book.contratante.orgao}}</b></font></p>
<p align="center" style="line-height: 100%"><font face="Arial Narrow, serif" size="2" style="font-size: 10pt"><b>{{book.contratante.unidade_maior}}</b></font></p>
<p align="center" style="line-height: 100%"><font face="Arial Narrow, serif" size="2" style="font-size: 10pt"><b>{{book.contratante.unidade_menor}}</b></font></p>
<p align="center" style="line-height: 100%"><br>
</p>
{% endblock %}

