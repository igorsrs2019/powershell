 Este script foi criado em powershell, o intuito dele é auxiliar no mapeamento de sites no IIS (Internet Information Services)
O mesmo acessa o diretório físico dos sites e procura pelo arquivo web.config. Informa o total de sites, quantidade que está com o  status "Running" e "Stopped" e exporta um arquivo IISMap.txt onde é um compilado do conteúdo de todos os web.config encontrados no IIS.
