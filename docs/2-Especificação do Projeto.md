# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do diagrama de personas (identifiquem, no mínimo, 2 personas), histórias de usuários (identifiquem, no mínimo, 3 histórias de usuários por persona), requisitos funcionais, requisitos não funcionais e artefatos produzidos para levantamento de dados).

## Personas

## Personas

**1. A Gestora Escolar**

|**Marta Morais**|
|:---:|
|<img src="https://github.com/ICEI-PUC-Minas-PPC-CC/Template-MentoringII/blob/main/docs/img/camilafiaes.png" width="200" height="200"/>|
|**Perfil:** Marta, 48 anos, diretora de uma escola de médio porte. <br><br>**Contexto:** Ela reconhece a importância da inclusão, mas enfrenta o desafio prático de não saber exatamente o que fazer ou por onde começar para adequar a infraestrutura física e os recursos pedagógicos da instituição, equilibrando essa demanda com as limitações orçamentárias. <br><br>**Necessidade no projeto:** Busca diretrizes claras, viáveis e um passo a passo estruturado sobre quais melhorias priorizar para tornar o ambiente escolar acessível sem incorrer em falhas legais ou operacionais.|

**2. Os Pais ou Responsáveis**

|**Roberto e Ana**|
|:---:|
|<img src="https://github.com/ICEI-PUC-Minas-PPC-CC/Template-MentoringII/blob/main/docs/img/camilafiaes.png" width="200" height="200"/>|
|**Perfil:** Roberto e Ana, 39 e 41 anos, pais de um aluno com deficiência visual. <br><br>**Contexto:** Sentem-se constantemente angustiados e exaustos pela necessidade de lutar diariamente para que o filho tenha acesso a materiais adaptados, como livros em Braille e leitores de tela nas aulas. Enfrentam barreiras tanto em escolas públicas quanto em privadas, que muitas vezes aceitam a matrícula, mas terceirizam a responsabilidade pelo suporte pedagógico adequado. <br><br>**Necessidade no projeto:** Buscam a garantia de que as instituições disponham de métodos claros de acolhimento e suporte especializado, assegurando que seus filhos tenham autonomia, segurança e aprendizado em igualdade de condições.|

**3. O Estudante**

|**Lucas**|
|:---:|
|<img src="https://github.com/ICEI-PUC-Minas-PPC-CC/Template-MentoringII/blob/main/docs/img/camilafiaes.png" width="200" height="200"/>|
|**Perfil:** Lucas, 11 anos, aluno matriculado no ensino fundamental que é cego. <br><br>**Contexto:** É o indivíduo diretamente negligenciado quando a escola falha em prover acessibilidade sensorial. Sofre com a ausência de sinalização tátil nos pisos, falta de livros em Braille, ausência de softwares de leitura de tela nos computadores da escola e materiais didáticos impressos comuns, o que limita severamente sua participação nas atividades e sua autonomia no ambiente escolar. <br><br>**Necessidade no projeto:** É o beneficiário final de todas as soluções propostas. Representa a urgência de transformar o ambiente escolar em um espaço universalmente acessível, onde ele possa transitar com segurança, aprender por meio de recursos táteis e tecnológicos, e interagir plenamente com os colegas.|

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes/beneficiários ideais que sua solução almeja.

Para selecionar as imagens de suas personas, utilize o site: https://this-person-does-not-exist.com/pt

## Histórias de Usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA` | QUERO/PRECISO... `FUNCIONALIDADE` | PARA... `MOTIVO/VALOR` |
|---|---|---|
| Marta (Gestora Escolar) | ter um roteiro claro e priorizado de adaptações arquitetônicas e pedagógicas | saber por onde começar sem cometer falhas legais ou operacionais |
| Marta (Gestora Escolar) | um guia que diferencie soluções viáveis para escolas públicas e privadas | adequar as melhorias à realidade orçamentária e de gestão da minha instituição |
| Marta (Gestora Escolar) | orientações sobre capacitação continuada da equipe pedagógica | garantir que os professores saibam atender adequadamente os alunos com deficiência |
| Roberto e Ana (Pais/Responsáveis) | ter a garantia de que a escola oferece materiais adaptados, como livros em Braille e leitores de tela | assegurar que meu filho acompanhe as aulas em igualdade de condições com os colegas |
| Roberto e Ana (Pais/Responsáveis) | um canal claro de comunicação com a escola sobre o suporte pedagógico oferecido | não precisar cobrar ou negociar diariamente pelos direitos do meu filho |
| Roberto e Ana (Pais/Responsáveis) | saber que a escola não terceiriza a responsabilidade pelo suporte especializado | ter confiança de que meu filho está seguro e amparado dentro da instituição |
| Lucas (Estudante) | contar com sinalização tátil nos pisos e ambientes da escola | me deslocar com autonomia e segurança pelo espaço escolar |
| Lucas (Estudante) | ter acesso a livros em Braille e softwares de leitura de tela nos computadores | acompanhar o conteúdo das aulas no mesmo ritmo que meus colegas |
| Lucas (Estudante) | participar das atividades escolares com os mesmos recursos que os demais alunos | interagir plenamente com meus colegas e não me sentir excluído |

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

Nesta seção, caso seu grupo vá realizar algum tipo de levantamento de dados/entrevistas, descreva o(s) artefato(s) produzidos para tal. Também deverá ser descrita qual estratégia será utilizada para este levantamento. Por exemplo: como os questionários serão aplicados? (_in loco_, via disponibilização pela _web_ etc), qual material/estratégia de divulgação será utilizado? 

Não se preocupe em descrever os resultados agora, eles deverão ser descritos apenas na seção "Detalhamento preliminar" (Etapa 03).
