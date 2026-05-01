# Nível 3: A Abstração Computacional

```text
INICIO Algoritmo TrajetoTrabalhoMultiplo
    linhas_necessarias <- [1, 2, 3]
    onibus_pegos <- 0
    
    sair_de_casa(antecedencia_horas=2.5)
    caminhar_para_parada_inicial()

    ENQUANTO onibus_pegos < tamanho(linhas_necessarias) FACA
        linha_atual <- linhas_necessarias[onibus_pegos]
        
        aguardar_onibus(linha_atual)
        fazer_sinal()
        
        SE (validar_cartao_transporte() == VERDADEIRO) ENTAO
            passar_catraca()
            
            SE (onibus_pegos < 2) ENTAO
                viajar_ate_terminal_integracao()
            SENAO
                viajar_ate_parada_trabalho()
            FIM SE
            
            descer_do_onibus()
            onibus_pegos <- onibus_pegos + 1
        SENAO
            exibir_mensagem("Saldo insuficiente. Buscar alternativa.")
            INTERROMPER
        FIM SE
    FIM ENQUANTO

    caminhar_para_empresa()
    exibir_mensagem("Deslocamento concluído. Bom turno!")
FIM Algoritmo
