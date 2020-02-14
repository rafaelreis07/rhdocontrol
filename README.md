Microserviço para controle de entrega de documentos de colaboradores.


Atores:

	Colaborador -> Prestador de serviços (Consultor). 
		Deverá, após autenticado no serviço, subir os documentos:
		NF (Estudar a para subir o XML da NF eletronica)
		GPS quitada com apresentação da folha de pagamento (de funcionários ou pró-labore)
		GFIP / SEFIP
		Certidão negativa do FGTS
		Certidão negativa de débitos relativos aos tributos federais e à dívida ativa da união
		Comprovante de cadastro na prefeitura de São Paulo (caso empresa tenha domicilio fora do muniçípio de SP)
		Comprovante de pagamento do ISS do mês anterioro para domicílios fora do Município de São Paulo
	
	Analista de RH -> Funcionário do RH responsável pelo agendamento dos pagamentos das NFs
	
Serviço:

	Os documentos deverão ser enviados pelos colaboradores, diretamente na interface do serviço, em frequencia mensal, porém alguns documentos não serão obrigatóriamente enviados mensalmente, pois tem validade por vários meses.
	A liberacão do pagamento das faturas dos colaboradores ficará condicionada ao envio dos documentos, portanto o serviço deverá prover um painel de controle para o Analista de RH.
	O serviço deverá enviar um email de alerta para uma lista de distribuição, no dia 15 de cada mes, contendo informações sobre a importação dos documentos, bem como o link para o serviço. Os documentos devem ser enviado até o dia 20 de cada mês. Outra notificação por email deverá ser enviado para o colaborador que não houver enviado os documentos após o dia 20.
	O serviço não deverá manter uma base de dados com informações específica sobre os colaboradores.
