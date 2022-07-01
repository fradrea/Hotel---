programa
{
	funcao inicio() 
	{
	    caracter ocupado        = '1'
	    caracter repeticao      = 's'
	    cadeia   vago           = "Livre"
	    cadeia   numerodoQuarto  [21]     
	    inteiro  i            
	    
	         para (i=1;i<21;i++)
	         {
	             vago="livre"
	          
	          se(repeticao== 's')
	          {
	              
	              escreva("Número do quarto:")
	              leia(numerodoQuarto[i])
	              escreva("Livre ou Ocupado?[1] ou [o]=")
	              leia(ocupado)
	               
	                se (ocupado=='1')
	                {
	                    numerodoQuarto[i]="Livre"
	                    vago=numerodoQuarto[i]
	                    
	                }
		            senao se (ocupado=='o')
		            {
		                numerodoQuarto[i]="ocupado"
		                vago=numerodoQuarto[i]
		            }
		            
		            escreva("desejo continuar? [S] ou [N]=")
	}
}
                 para (i=1;i<21;i++)
                 {
                     escreva(i," - ",vago,"\n")
    
                     
}                 
	}                     
                     
                     
                     
                 }
