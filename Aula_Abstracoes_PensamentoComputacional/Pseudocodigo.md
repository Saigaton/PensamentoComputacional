INICIO Algoritmo CompraOnline

    abrir_loja_virtual()
    item_desejado <- pesquisar_produto()
    
    SE (produto_disponivel(item_desejado) == VERDADEIRO) ENTAO
        adicionar_ao_carrinho(item_desejado)
        ir_para_o_caixa()
        
        // Finalização
        SE (validar_cartao() == VERDADEIRO) ENTAO
            confirmar_compra()
            exibir_mensagem("Sucesso! Verifique seu e-mail.")
        SENAO
            exibir_mensagem("Erro no pagamento. Tente outro cartão.")
        FIM SE
        
    SENAO
        exibir_mensagem("Infelizmente o produto acabou.")
    FIM SE

FIM Algoritmo