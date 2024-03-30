
# ENTRADAS
 - 1 Homem
 - 1 Barco com dupla capacidade (Transporte)
 - 1 Lobo (Pertence)
 - 1 Cabra (Pertence)
 - 1 Maço de alfafa (Pertence)
 
# REQUISITOS
  - 1 homem e 1 dos pertences
  - LOBO + CABRA = X
  - CABRA + ALFAFA = X
  

# LÓGICA

  1. Homem transportar a CABRA até DESTINO e deixa lá;
            LOBO + ALFAFA sozinhos = NULL;

  2. Homem retorna ao INICIO;
  3. Homem leva LOBO até DESTINO só que não deixa lá;
            ALFAFA sozinha = NULL;
  
  4. Homem troca o LOBO com a CABRA;
  5. Homem retorna ao INICIO com a CABRA;
            LOBO sozinho no destino= NULL;
            CABRA no bote;
  
  6. Homem troca CABRA com a ALFAFA;
  7. Homem transporta ALFAFA até o DESTINO e deixa lá; 
            CABRA sozinha no inicio = NULL;
            LOBO + ALFAFA no destino = NULL
  
  8. Homem retorna ao inicio;
  9. Homem tranporta CABRA finalmente ao DESTINO;
            Todos transportados e nenhum ferido/danificado.
  
      