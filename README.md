# Upload AI - Back-end

Bem-vindo ao repositório do Back-end do projeto Upload AI! Este é o coração do sistema, onde toda a mágica acontece, transformando vídeos em transcrições personalizadas com a ajuda da IA.

## Tecnologias Utilizadas
O Back-end deste projeto foi desenvolvido com as seguintes tecnologias:

- **Fastify**: Um framework web altamente eficiente para Node.js.
- **Prisma**: Um ORM (Object-Relational Mapping) para Node.js e TypeScript.
- **TypeScript (TS)**: Adiciona tipagem estática ao JavaScript para evitar erros e melhorar a produtividade.
- **OpenAI**: Uma biblioteca para interagir com a API da OpenAI.
- **Zod**: Uma biblioteca para validação de esquemas de dados em TypeScript.
- **Dotenv**: Para carregar variáveis de ambiente a partir de um arquivo `.env`.


## Funcionalidades Principais
A API do Back-end do Upload AI oferece as seguintes funcionalidades principais:

- **Transcrição de Vídeo**: A API é capaz de enviar um vídeo para a API da OpenAI e gerar uma transcrição precisa dele.
- **Armazenamento no Banco de Dados**: Após a criação da transcrição, ela é salva no banco de dados para uso posterior.
- **Prompts Personalizáveis**: Os prompts podem ser cadastrados de forma altamente personalizável e aplicados à transcrição para gerar conteúdo diversificado.
- **Geração de Conteúdo**: Os prompts podem ser usados para criar títulos, descrições, resumos ou até mesmo desafios, como a criação de quizzes com base no conteúdo do vídeo.

Com essas funcionalidades, a API do Upload AI permite a automação da geração de conteúdo com base em transcrições de vídeos, facilitando a vida dos criadores de conteúdo e proporcionando uma variedade de opções criativas.
