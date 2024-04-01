## Uso de Azure AI Search

1. Criar grupo de recurso no https://portal.azure.com/
2. Criar recurso Azure Search AI
3. Criar recurso Azure AI Services
4. Criar recurso de armazenamento
5. Ir para o recurso de storage, e mudar a configuração para prmitir acesso anonimo ao Blob
6. Na página de recurso do storage , selecionar Containers e realizar upload dos arquivos
7. para gerar insights dos documentos, é necessário indexar os documentos pelo recurso criado do Azure Search AI, realizando essa etapa na importação de dados
8. Após importação você pode utilizar o Search Explorer do recurso Search AI e realizar pesquisas nos documentos por sentimentos, locais, etc..
9. O recurso Search AI pode ajudar empresas que trabalham com muitas textos, a encontrarem de forma mais rápida um determinado documento por insights gerados pelo serviço de IA, em Tribunais seria muito útil a ferramenta para pesquisar documentos que incidem maiores frequencias de termos como violência doméstica, homicídios, etc...

