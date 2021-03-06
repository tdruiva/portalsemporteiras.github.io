---
layout: saibamais
---

# Infraestrutura da Rede Comunitaria

A Rede Portal sem Porteiras, é uma rede comunitária em meio rural no Brasil, é um projeto que visa trazer acesso a uma população que esteve à sombra da conectividade antes e durante a Pandemia. Esta rede comunitária utiliza a topologia mesh, utilizando um firmware baseado no LibrerouterOS. Se trata de um trabalho continuo com estudos tecnológicos, empoderamento das mulheres e melhoria e implementação da comunicação e da economia local. A fim de acrescentar novas ferramentas tecnológicas para melhorar a nossa coexistência social, precisamos que todos tenham o mesmo acesso, uma vez que estas acções e programas dependem da expansão da rede para acontecer.  Actualmente a rede comunitária do bairro oferece acesso gratuito ou a baixo custo a mais de 150 dispositivos por mês, bem como promove iniciativas para uma utilização crítica e activa das TIC. Até agora a maior parte das ligações à rede ocorriam através de dispositivos utilizados na zona central do bairro, com alguns outros nós instalados em zonas mais distantes. Agora que locais como a praça principal e a sede da PSP, respeitando as medidas de isolamento, não devem ser visitados, a rede deve adaptar-se e encontrar uma forma de chegar às pessoas onde elas se encontram. Neste momento de pandemias, em que a maioria das pessoas está em quarentena dentro das suas casas, a necessidade de conectividade e de acções comunitárias em linha aumenta significativamente. A fim de assumir a tarefa de ligar mais pessoas locais à rede, o alcance da rede tem de crescer.

<div class="imgfull">
<img src="{{ site.baseurl }}/assets/images/psp-regioes.png" >
</div>

<section class="container wrap">
 {% for regiao in site.data.regioes %}
    <div class="imgfull">
                <a href="{{ regiao.url}}">
                    <img src="{{ site.baseurl }}/assets/images/mapa/{{ regiao.imagem }}" alt="Imagem da {{ regiao.nome }}"/>
                </a>
    </div>
            {% endfor %}
</section>