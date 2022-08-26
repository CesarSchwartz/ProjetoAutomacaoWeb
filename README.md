# ProjetoAutomacaoWeb

INTRODUÇÃO:

Imagina que você trabalha na área de compras de uma empresa e precisa fazer uma comparação de fornecedores para os seus insumos/produtos.
Nessa hora, você vai constantemente buscar nos sites desses fornecedores os produtos disponíveis e o preço, afinal, cada um deles pode fazer promoção em momentos diferentes e com valores diferentes.
objetivo: Se o valor dos produtos for abaixo de um preço limite definido por você, você vai descobrir os produtos mais baratos e atualizar isso em uma planilha.
Em seguida, vai enviar um e-mail com a lista dos produtos abaixo do seu preço máximo de compra.


OBJETIVO DO PROJETO:

Criar um codigo capaz de buscar de forma automatica produtos selecionados em varios sites, assim tendo maior chance de achar as melhores ofertas, essa busca pode receber
parâmetros personalizados como:(preço minimo, preço maximo e Termos banidos exemplo:" Termos banido consiste em um filtro no nome do produto para evitar pegar uma versão
errada daquele mesmo produto."). Após a busca o código cria uma planilha com todos os resultados encontrados e manda por e-mail para o destinatário.


BIBLIOTECAS UTILIZADAS:

selenium,
webdriver_manager,
win32com.client,
time.

ETAPAS DO PROJETO:

1 ETAPA - Importar Bibliotecas.

2 ETAPA - Iniciando Selenium e Importando o Arquivo de Produtos que Usará na Busca.

3 ETAPA - Criando a Função que Fará a Busca no Google Shoping.

4 ETAPA - Criando a Função que Fará a Busca no Buscapé.

5 ETAPA - Automatizando o Processo de Busca De Todos os Produtos do Arquivo.

6 ETAPA - Criando Arquivo Com Todas as Ofertas Encontradas.

7 ETAPA - Criando e Enviando o E-mail com o Arquivo que Contém as Ofertas
