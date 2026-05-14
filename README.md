
#Cadastro de produto

estoque_principal = {}

def cadastrar_produto(nome_produto, detalhes_produto, especificacoes):

    estoque_principal[nome_produto]={
        "detalhes": detalhes_produto,
        "especificacoes": especificacoes
       
    }
    print(f"Produto '{nome_produto}'")
    print(f"Detalhes do produto: {detalhes_produto}")
    print(f"Especificações do produto: {especificacoes}\n")

# Produto 1: Camisetas Básicas
cadastrar_produto(
    "Camisetas Básicas",
    [100, 49.9],
    "Algodão 100%, gola reforçada, costura dupla, tamanhos P ao GG"
)

# Produto 2: Camisetas Premium
cadastrar_produto(
    "Camisetas Premium",
    [60, 79.9],
    "Algodão penteado 30.1, toque macio, modelagem slim."
)

# Produto 3: Calca Jeans
cadastrar_produto(
    "Calca Jeans",
    [60, 149.9],
    "Jeans elastano, corte reto, lavagem premium, zíper metálico"
)

#Produto 4: Vestido Casual

cadastrar_produto(
    "Vestido Casual",
    [35, 129.9],
    "Viscose, postura reforçada e modelagem confortável"
)

#Produto 5: Moletom 

cadastrar_produto(
    "Moletom",
    [30, 179.9],
    "Moletom felpado 3 cabos, capuz ajustável, punhos reforçados"
)

#Produto 6: Jaqueta Cortavento
cadastrar_produto(
    "Jaqueta Cortavento",
    [40, 249.9],
    "Tecido impermeável, forro interno, fechamento em zíper"
)

print(" Estoque Final ")
print(estoque_principal)
