# Calendário de entregas

- ``30/01`` Kick-off projeto final;
  - Criar um repositório **público** da equipe;
  - Adicionar a mim como membro do projeto;
  - Criação das classes/pacotes das entidades do projeto.
- ``14/02`` Definições da camada de Modelos;
  - Diagrama de Classes;
  - Diagrama de Entidade-Relacional;
  - Script SQL de criação do banco de dados do projeto.
- ``27/02`` Definições da camada de Visão;
  - Protótipo de telas com base nos requisitos;
  - Definição da identidade visual.
- ``14/03`` Definições da camada de Controle - *parte 01*;
  - Integração com Banco de dados (CRUD básico das entidades);
  - Implementação de Autenticação no sistema;
  - Início da implementação dos demais requisitos;
- ``29/03`` Definições da camada de Controle - *parte 02*;
  - Continuação da implementação dos demais requisitos.
- ``29-30/03`` e ``03-04/04`` Acompanhamento de projeto final;
- ``05/04`` Apresentação dos projetos.

## Requisitos gerais de TODOS os projetos 

- Precisa ter uma página inicial institucional estática, a página inicial;
- Demais páginas precisam ser dinâmicas e abordar os casos de uso;
- Ser responsivo, ter pontos de quebra para celular e Desktop; 
- Identidade visual com palheta de cores (até 05) e fontes;
- Possuir controle de acesso de usuários;
- Ter entre 05 e 10 componentes distintos do [Bootstrap](http://www.getbootstrap.com/). Entende-se como componentes tudo da seção Components;
- Diagrama Entidade-Relacionamento do banco de dados;
- O sistema precisa ter autenticação de usuários.

# Portal do Egresso

Tamanho de Equipe: **3** (+1)

## Descrição narrativa

O sistema de Egressos tem como objetivo acompanhar os egressos dos cursos regulares da Saber.edu quanto à sua inserção no mercado de trabalho, após a conclusão do curso, compreendendo atividades que permitam: (i) integrar os egressos à comunidade acadêmica, mantendo-os em permanente contato com a Saber.edu; (ii) consolidar o vínculo com o egresso, por meio da criação e implementação de ações, tendo em vista o compromisso e a responsabilidade com a comunidade; (iii) promover a realização de atividades extracurriculares de cunho técnico-profissional, buscando a valorização do egresso; (iv) implementar e manter atualizado sistema de comunicação com os egressos, a partir de dados e registros atualizados.

Existem três atores neste sistema, o Egresso, as Empresas e a Saber.edu. Todos os acessos são feitos por CPF, no caso do Egresso, ou CNPJ, no caso das Empresas.

Ao Egresso, o sistema possibilita o cadastro do currículo institucional (dados da formação) e profissional (experiências de trabalho). Além disso, a busca por oportunidades de trabalho  e capacitações também é possível pelos Egressos. Ao entrar no sistema, o Egresso tem uma visão geral das vagas mais recentes que estejam alinhadas ao perfil dele. Esse alinhamento ocorre por meio de correspondências entre hashtags das stacks que ele procura. Ao acessar cada vaga, é mostrado um indicador de Match com base nos requisitos da vaga e do Egresso.

No módulo de Empresa, cabe às Empresas indicarem capacitações e oportunidades. É possível ver quantos (não quais) Egressos escolheram aplicar tanto para as capacitações e oportunidades. Além disso, tanto as capacitações quanto as oportunidades devem possuir descrição textual e classificação por hashtags das stacks. Quando houver um Match entre a uma oportunidade e um Egresso, uma caixa de mensagem deve aparecer para que ambos mantenham um bate-papo pela plataforma.

## Requisitos específicos resumidos

- Fazer cadastro do Egresso (dados institucionais - origem);
- Fazer cadastro de currículo (dados profissionais);
- Fazer cadastro de oportunidades de trabalho (Cadastro pela Empresa/Organização);
- Fazer cadastro de capacitações;
- Dashboard para mostrar dados de empregabilidade;
- Buscar egresso, elementos do cv, oportunidades, capacitações;
- Indicadores de necessidades em déficits;
- Recomendaçao de oportunidades/capacitações ao Egresso;
- Caixa de mensagem entre Empresas e Egressos (Bate-papo).
