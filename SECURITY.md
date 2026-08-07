# Security

- Nunca versione arquivos `.env`.
- Utilize no front-end apenas chaves publicáveis do Supabase.
- Mantenha políticas de Row Level Security (RLS) habilitadas e revisadas nas tabelas expostas ao cliente.
- Não armazene `service_role` ou outros segredos administrativos no navegador.

Caso uma credencial seja exposta por engano, faça a rotação da chave no provedor antes de publicar o repositório.
