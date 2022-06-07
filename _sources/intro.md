# Boas-vindas

<div class="admonition warning" name="html-warning">
<p class="title">Aviso</p>
**Este livro está em construção!**
</div>

Sejam bem-vindos(as) ao livro **Análise de dados e estatística com Python para não programadores**. Este livro tem como objetivo oferecer uma introdução à programação em Python e suas diversas bibliotecas para análise de dados e estatística.

Esta é a versão interativa do livro. A versão em `.pdf` será feita quando o livro estiver completo em sua primeira versão.

## Motivação

Há atualmente uma proliferação de livros e materiais didáticos de ensino de estatística, análise e ciência de dados, além de programação em Python. Contudo, como disse Fogarty (2019, p. vi), ["as equações de erro padrão e regressão linear não mudaram; a matemática da estatística introdutória pode ser achada em centenas de outros livros; o que precisamos são de livros que guiem estudantes e praticantes através de procedimentos passo-a-passo de análise de dados em ciências sociais"](https://uk.sagepub.com/en-gb/eur/quantitative-social-science-data-with-r/book257236).

Além disso, é difícil encontrar um livro, site ou curso que tenha como foco alunos de *stricto sensu* (mestrado e doutorado) em gestão do conhecimento, administração e áreas afins com proposta equilibrada - isto é, cujo foco esteja no fluxo de trabalho de pesquisa próximo a estas áreas. Pesquisadores em formação nessas áreas encontram bons materiais, mas de forma fragmentada: bons conselhos em livros de metodologia científica, exemplos de casos de análise em livros de estatística e bases de programação em livros de informática. Fica a cargo do leitor juntar esses conhecimentos num processo de tentativa e erro e incorporá-los em suas ferramentas analíticas em um fluxo de trabalho.

Como professores de programas de mestrado e doutorado interdisciplinares, somos sempre desafiados a nivelar o conhecimento de análise de dados de alunos provenientes das mais variadas áreas. Assim, além de alunos com sólida formação em programação, sempre há alunos de ciências sociais aplicadas, engenharia e áreas correlatas com pouco ou nenhum conhecimento de programação que necessitam aprender uma linguagem de programação e noções de estatística, bem como manipulação e análise de dados em um curto espaço de tempo. 

A motivação primária para este livro é, portanto, esta:
> **Fornecer uma introdução rápida, mas suficientemente densa, a análise de dados e estatística por meio de programação em Python e suas bibliotecas, que possa ser utilizada em um semestre letivo, sob a perspectiva de leitores sem conhecimento prévio de programação e estatística**.

Uma motivação secundária é de organizar de forma mais estruturada materiais de ensino criados anteriormente pelos autores (como por exemplo [Python para Análise de Dados](https://github.com/fellipemartins/python_curso). 

Finalmente, outra motivação não menos importante é a nossa participação na cultura fonte livre (*open source*). Como parte desse movimento, acreditamos que o conhecimento deve ser livremente compartilhado e por isto, este livro é de uso aberto conforme a licença [**MIT**](https://opensource.org/licenses/MIT). Por este motivo, este material pode ser de interesse a pessoas interessadas em análise de dados com Python, mesmo fora do escopo de pesquisadores em ciências sociais aplicadas.


## Por que Python?

Escolher uma linguagem de programação é um tópico muito desafiador e complexo para quem nunca programou. Primeiro, existem muitas linguagens de programação - todas elas compartilham a característica de serem Turing-completas, ou seja, todas capazes de fazer cálculos (com mais ou menos trabalho para o programador). Além disto, para cada nicho de aplicação há, via de regra, mais de uma linguagem usada por praticantes desses nichos. Por causa disto, buscar apoio para tal escolha pode ser confuso pelo excesso de informações conflitantes além de, muitas vezes, ser um assunto polêmico. Independentemente da escolha da linguagem, existem diversos prós e contras e para cada uma delas, uma horda de defensores e detratores. 

No caso de estatística e análise de dados não é diferente. Neste nicho, algumas linguagens têm recebido muita atenção, em especial estas três mais conhecidas: R, Python e Julia. 

- **R**: Linguagem particularmente forte na área de estatística e análise de dados;
- **Python**: Linguagem multipropósito especialmente forte em análise de dados e aprendizado de máquina;
- **Julia**: Linguagem jovem com potencial de crescimento em diversas aplicações, incluindo ciência de dados e estatística.

De forma genérica, qualquer uma dessas três serve para fazer o básico de análise de dados. A principal desvantagem do R é que ela é muito fechada no nicho de análise e estatística, e a adoção da linguagem fora desse nicho é quase irrisória. Julia, por outro lado, é uma linguagem nova e, por causa disto, algumas aplicações e métodos comuns às ciências sociais têm pouco suporte (mas é algo que tende a mudar com o crescimento da linguagem e o processo de portabilidade).

Assim, Python é uma escolha mais conservadora - genérica o suficiente para não obstruir o desenvolvimento do analista, e com suporte suficiente das principais bibliotecas de estatística e análise de dados para ciências sociais aplicadas. Além disto, a escolha da linguagem Python também passa por uma questão probabilística. Para pessoas com o perfil com as formações citadas anteriormente, é mais provável é que haja alunos algum conhecimento de Python, seguido de R e depois outras linguagens. 

Isto não quer dizer que Python seja, necessariamente, uma linguagem melhor - não vamos entrar nessa discussão nem fomentar mais polêmica. Trata-se de uma ferramenta introdutória excelente para iniciantes em programação. Assim, enxergamos o Python como uma possível porta de entrada. Uma coisa é certa, como em aprendizado de linguagens naturais, após aprender uma linguagem de programação, aprender outras se torna uma tarefa muito mais fácil e a migração para R e Julia ou incorporação delas muito mais viável.

(colaborar)=
## Como colaborar com este projeto

Há diversas formas de colaborar com este projeto:
- Dar uma estrela no [repositório GitHub do livro](https://github.com/fellipemartins/python_analise_dados);
- Utilizar esse livro em seus projetos e estudos;
- Apontar eventuais problemas no texto, código, etc.;
- Indicar este livro para outras pessoas;
- Fazer sugestões, pedidos no [repositório GitHub do livro](https://github.com/fellipemartins/python_analise_dados).



## Autores

Este livro foi escrito por Fellipe Martins e Leonardo Vils. 

Fellipe Martins
* [Currículo Lattes](http://lattes.cnpq.br/7912881403948084)
* email: fellipemartins@uni9.pro.br
* [Programa de Pós-Graduação em Informática e Gestão do Conhecimento (UNINOVE)](https://www.uninove.br/cursos/mestrado-e-doutorado/presencial/mestrado-e-doutorado-em-inform%C3%A1tica-e-gest%C3%A3o-do-conhecimento)
* Linha de Pesquisa: Tecnologia da Informação e Conhecimento

> Fellipe Martins é professor do quadro permanente do Programa de Pós-Graduação (mestrado / doutorado) em Informática e Gestão do Conhecimento na Universidade Nove de Julho. Doutor em Administração (Estratégia) e Mestre em Engenharia de Produção (Gestão e Otimização da Produção) pela Universidade Nove de Julho - SP. Bacharel em Línguas Estrangeiras Aplicadas às Negociações Internacionais pela Universidade Estadual de Santa Cruz - BA. Ex-bolsista do Governo do Departamento de Charente-Maritime (França) para estudos na Université de La Rochelle (2006-2007). Co-líder do tema de pesquisa em estratégia comportamental na Associação Nacional de Pós-Graduação em Administração (ANPAD / ESO-1). Líder do tema de pesquisa em transformação digital no Congresso Brasileiro de Gestão do Conhecimento (KM Brasil).

Leonardo Vils
* [Currículo Lattes](http://lattes.cnpq.br/3969955798466284)
* email: leonardovils@uni9.pro.br
* [Programa de Pós-Graduação em Gestão de Projetos (UNINOVE)](https://www.uninove.br/cursos/mestrado-e-doutorado/presencial/mestrado-e-doutorado-profissional-em-administracao-gestao-de-projetos)
* Linha de Pesquisa: XXX

> Leonardo Vils é economista com Mestrado e Doutorado em Administração de Empresas pela Universidade Nove de Julho. Professor permanente do programa de Pós-Graduação em Cidades Inteligentes e Sustentáveis e do Programa de Pós-Graduação em Gestão de Projetos da Universidade Nove de Julho. Tem como linhas de pesquisa Psicologia Ambiental e Território Construído e Economia Comportamental e Inovação em Projetos. Experiência de mais de 25 anos em cargos executivos de empresas de grande porte. Autor de sete livros.

<div class="admonition warning" name="html-warning">
<p class="title">Aviso</p>
**Este livro representa única e exclusivamente a opinião dos autores e de forma alguma é relacionado com instuições, associações, empresas ou quaisquer outros vínculos empregatícios e/ou científicos dos autores.**
</div>

Colaboraram com este projeto:
- [Cristiano Martins](http://lattes.cnpq.br/2134033520588291).
- [Déborah Foroni](http://lattes.cnpq.br/4356168879181955).


## Agradecimentos

Fellipe Martins: 

*Gostaria de agradecer aos seus professores de estatística, métodos quantitativos e metodologia de pesquisa: Dr. Fábio Pereira, Dr. Dirceu da Silva, Dr. Evandro Lopes, Marcelo Gabriel e Dr. Wagner Cezar Lucato. Além disto, agradeço a meus professores de programação em Python, Caio Salgado, Deborah Foroni, Luiz Favaro e Carlos Prado.*

Leonardo Vils 




## Como citar este conteúdo

**ABNT (NBR)**:
MARTINS, F. S.; VILS, L. Análise de dados e estatística com Python para não programadores. Disponível em: <https://fellipemartins.github.io/python_nao_programadores/>. Acesso em: XX fev. 2021.

**APA**:
Martins, F. S.; Vils, L. (2022, Feb XX). Análise de dados e estatística com Python para não programadores. https://fellipemartins.github.io/python_nao_programadores/


Ou formato BibTeX (LaTeX):
```bibtex
@misc{martins2021pythonnaoprogramadores,
  author = {MARTINS, Fellipe Silva; VILS, Leonardo},
  title = {Análise de dados e estatística com Python para não programadores},
  url = {https://fellipemartins.github.io/python_nao_programadores/},
  year = {2022},
  month = {June}
}
```
