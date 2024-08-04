# Desafio Beedoo

## User Stories

### User Story 1: Criar Curso
**Como** um usuário administrador  
**Quero** criar um novo curso  
**Para que** os alunos possam se inscrever e acessar o conteúdo.

### User Story 2: Excluir Curso
**Como** um usuário administrador  
**Quero** excluir um curso existente  
**Para que** possa remover cursos desatualizados ou incorretos.

### User Story 3: Listar Cursos
**Como** um usuário administrador  
**Quero** visualizar a lista de cursos existentes  
**Para que** possa gerenciar melhor os cursos oferecidos.

### User Story 4: Excluir Curso (Duplicado)
**Como** um usuário administrador  
**Quero** excluir um curso existente  
**Para que** possa remover cursos desatualizados ou incorretos.

## Decisões Tomadas para Criar as User Stories

- **Análise dos Requisitos**: A tela de cadastro de curso deve incluir os seguintes campos:
  - Nome do curso
  - Descrição
  - Instrutor
  - URL da imagem de capa
  - Data de início: Menor ou igual a data de fim;
  - Data de fim: maior ou igual a data de inicio e menor ou igual a data recorrente (atual);
  - Número de vagas
  - Tipo de curso

- **Identificação das Funcionalidades Principais**: Criar, excluir e listar cursos.

- **Consideração de Diferentes Cenários**: 
  - **Sucesso**: Curso criado/excluído/listado corretamente.
  - **Erro**: Dados faltantes, inválidos ou duplicados.

- **Ideias Adicionais para Melhorar a Tela de Cadastro de Curso**:
  - Validação de datas: Garantir que a data de início seja anterior à data de fim e que ambas sejam válidas.
  - Formatação das datas de acordo com o periodo recorrente: O campo de data de fim deverá ter uma condição que impede que seja cadastrado um curso com data inferior a data recorrente (atual).
  - Sugestões automáticas de instrutores:  Autocompletar nomes de instrutores com base em um banco de dados existente.
  - Número máximo de vagas: Definir um limite máximo para o número de vagas e validar no cadastro.
  - Categorias de curso: Permitir a categorização dos cursos para melhor organização.
  - Campos personalizados: Adicionar a opção para criar campos personalizados de acordo com as necessidades do curso.
  - Feedback visual: Fornecer feedback imediato sobre erros ou confirmações de ações.
  - Acessibilidade: Garantir que a tela de cadastro seja acessível para todos os usuários, incluindo aqueles com deficiências.
  - Botão de rascunho: Permitir que o administrador salve um curso como rascunho para continuar o preenchimento posteriormente.
  - Importação em massa: Adicionar a funcionalidade para importar vários cursos de uma vez através de um arquivo CSV ou Excel.
  - Histórico de alterações: Manter um log de todas as alterações feitas nos cursos para auditoria.
  - Notificações: Enviar notificações por email ou SMS para os alunos inscritos em um curso que foi atualizado ou cancelado.
  - Opção de armazenar anexo de imagem no cadastro: Substituir o campo de URL para Anexo e permitir que seja anexado mídia de imagem em formatos JPEG e PNG ou anexar URL.

## LINKS EXTERNOS
[Planilha do casos de teste](https://docs.google.com/spreadsheets/d/1ve3OFYFEhO86Mefpf5ZxSxfTNx7LE5FGQEN_2gqtM6Q/edit?usp=sharing)

[Drive das evidências](https://drive.google.com/drive/folders/1R9zYtkizZJ1ApzNSG7B-RePt3h-S5vtf?usp=sharing)




 

